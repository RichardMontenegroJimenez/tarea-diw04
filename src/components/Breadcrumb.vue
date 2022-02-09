<template>
    <section id="breadcrumb">
      <a class="inicio" href="#"> Inicio </a> >
      <a href="#">Ratones</a> > 
      <a class="actual" href="#">Logitech</a> 
  </section>
</template>

<script>
export default {

}
</script>

<style>
#breadcrumb {
    display: flex;
    justify-content: start;
}
section#breadcrumb a, 
section#breadcrumb a:hover, 
section#breadcrumb a:visited{
    text-decoration: none;
    font-size: 1.2rem;
    margin-left: 1rem;
    margin-right: 1rem;
    color: rgb(161, 60, 207);
}
section#breadcrumb a.actual {
    font-weight: 700;
}
section#breadcrumb {
    margin-left: 1rem;
    color: rgb(161, 60, 207)
}
</style>