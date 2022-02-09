<template>
  <Cabecera />
  <Busqueda />
  <Bredcrumb />
  <div class="contenedor">
    <div id="imagen_producto">
      <GaleriaProducto />
    </div>
    <div class="espacio"></div>
    <div id="info_producto">
      <InformacionProducto />
    </div>
  </div>
  <div class="contenedor">
    <div id="descripcion">
      <DescripcionProducto />
    </div>
    <div class="espacio"></div>
    <div id="video">
      <VideoProducto />
    </div>
  </div>
  <Footer />
</template>

<script>
import Cabecera from './components/logoCabecera.vue'
import Busqueda from './components/Busqueda.vue'
import Bredcrumb from './components/Breadcrumb.vue'
import GaleriaProducto from './components/GaleriaProducto.vue'
import InformacionProducto from './components/InformacionProducto.vue'
import VideoProducto from './components/VideoProducto.vue'
import DescripcionProducto from './components/DescripcionProducto.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Cabecera, 
    Busqueda, 
    Bredcrumb, 
    GaleriaProducto, 
    InformacionProducto,
    VideoProducto,
    DescripcionProducto,
    Footer
  }
}
</script>

<style>
#app {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 25px;
}
.boton {
  background-color: rgb(161, 60, 207);
  font-size: 1.2rem;
  font-weight: 700;
  color: white;
  padding: 0.7rem 1.2rem;
  border-radius: 1rem;
  border: none;
  cursor:pointer;
}
.contenedor{
  display: flex;
  flex-direction: row;
  width: 1500px;
}
.espacio{
  display: flex;
  flex-grow: 1;
  
}
</style>
