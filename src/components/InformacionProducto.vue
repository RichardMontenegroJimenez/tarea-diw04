<template>
  <section id="producto-datos">
      <h1>Ratón Logitech Pro X Superlight Negro</h1>
      <h2>99,99€</h2>
      <div class="wrapper">
          <button class="btn" @click="cambiarContador('-1')" type="button" name="button">-</button>
          <input class="cantidad" type="text" name="name" :value="contador">
          <button class="btn" @click="cambiarContador('1')" type="button" name="button">+</button>
      </div>
      <br>
      <button class="boton">AÑADIR CARRITO</button>
  </section>
</template>

<script>
export default {
  Name: 'InformacionProducto',
    data () {
        return {
            contador: 1
        }
    },
    methods: {
        cambiarContador(num) {
            this.contador += +num;
            if (!isNaN(this.contador) && (this.contador < 0)) {
              this.contador = 0
            }
        }
    }


}
</script>

<style scoped>
section#producto-datos {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
h1 {
  font-size: 2.2rem;
}
h2 {
  font-size:1.7rem;
  color: rgb(161, 60, 207);
}

.wrapper {
  height: 2rem;
  display: flex;
}

.cantidad {
  border: none;
  text-align: center;
  width: 2rem;
  font-size: 1.2rem;
  border: 1px solid #d8d8d8;
}
.btn {
  border: 1px solid #d8d8d8;
  width: 1.8rem;
}
button:focus, input:focus {
  outline: 0;
}

</style>