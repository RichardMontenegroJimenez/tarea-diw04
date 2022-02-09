<template>
  <header>
      <div id="logo">
          <h1>total<span>Gaming</span></h1>
      </div>
      <div id="container">
        <nav id="menu_principal">
            <ul>
                <li><a href="#">INICIO</a></li>
                <li><a href="#">PC GAMING </a></li>
                <li><a href="#">AURICULARES</a></li>
                <li><a href="#">TECLADOS</a></li>
                <li><a href="#">RATONES</a></li>
                <li><a href="#">CONSOLAS</a></li>
            </ul>
        </nav>   
        <div id="login"> 
            <a href="#">Registrarse</a>
            <a href="#">Iniciar sesión</a>
        </div>       
      </div> 
  </header>
</template>

<script>
export default {

}
</script>

<style>
#logo{
    text-align: start;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

#logo h1{
    color: rgb(161, 60, 207);
    font-size: x-large;
}
#logo h1 span{
    color: rgb(231, 160, 28);
    font-size: xx-large;
}
#container{
    background: rgb(231, 160, 28);
    padding: 0.5em;
    display:flex;
    justify-content: space-between;
}
#login a{
    color:rgb(231, 160, 28);
    background: rgb(161, 60, 207);
    padding: 1em;
}
#login a:link{
    text-decoration: none;
}
#login a:hover {
    background:rgb(231, 160, 28);
    color: rgb(161, 60, 207);
}

#menu_principal ul{
    list-style: none;
    display: flex;
    justify-content:space-between
}

#menu_principal ul a{
    color:rgb(161, 60, 207);
    font-weight: bold;
    padding: 2em;
}

#menu_principal a:link {
    text-decoration: none;
}

#menu_principal a:hover {
    background: rgb(161, 60, 207);
    color: rgb(231, 224, 224);
    padding-top: 2em;
}
#menu_principal a:visited {
    text-decoration: none;
}


</style>