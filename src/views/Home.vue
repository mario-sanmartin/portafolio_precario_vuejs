<template>
  <div class="home">
    <h1 id="i-logo">MS</h1>
    <div class="bottom-logo-text">
      <p class="text-center text-muted">Mario San Martín Alarcón Software Developer.</p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "Home",
  components: {
    // HelloWorld
  },
};
</script>

<style scoped>
.home {
  height: 90vh;
  display: flex;
  justify-content: center;
  flex-direction: column;
}
#i-logo {
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: 2500%;
  text-align: center;
  padding: 0;
}
.boton-logo-text{
  margin-top: -50px;
  text-align: center;
}


</style>
