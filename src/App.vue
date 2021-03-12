<template>
  <div id="nav">
    <!-- <Logo/> -->
    <h1 id="page-name-title">MS</h1>
    <div class="top-menu">
      <router-link to="/"><h5>Inicio</h5></router-link> 
      <router-link to="/sobremi"><h5>Sobre Mi</h5></router-link> 
      <router-link to="/habilidades"><h5>Habilidades</h5></router-link> 
      <router-link to="/proyectos"><h5>Proyectos</h5></router-link> 
      <router-link to="/contacto"><h5>Contacto</h5></router-link>
    </div>
  </div>
  <router-view />
</template>

<script>
// import Logo from './components/Logo'
export default {
  components: {
    // Logo
  },
};
</script>

<style scoped>
#page-name-title {
  line-height: 0;
  margin-top: 0.5%;
}

#nav {
    -webkit-box-shadow: 0px -1px 27px 7px rgba(196,196,196,0.46); 
    box-shadow: 0px -1px 27px 7px rgba(196,196,196,0.46);
    display: flex;
    justify-content: space-between;
    padding: 20px;
}

.top-menu {
    display: flex;
}

.top-menu h5 {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.top-menu a {
    margin-left: 10px;
    font-weight: bold;
  color: #2c3e50;
}


#nav {
  padding: 30px;
}



.top-menu a.router-link-exact-active {
  color: #42b983;
}
</style>
