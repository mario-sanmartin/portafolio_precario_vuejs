<template>
  <Logo />
  <div id="primero">
    <!-- <img src="./static/assets/cris.png" alt="CrisMorris" /> -->
    <div id="segundo-container">
      <h2>Sobre mi</h2>
      <p>
        Soy <i>Mario Fernando San Martin Alarcon</i>, programador y analista de
        sistemas. autodidacta , buscando siempre la mejora continua
        ,personal,entorno y en la busqueda incansable de no aburrirme de
        programar , muy curioso en con todo lo referente a las TI especialmente
        ahora con Javascript y con todo su variopinto de frameworks y su
        backend Node.
      </p>
      <p>Vivo en la Comuna de Penco,ciudad de Concepción.</p>
    </div>
  </div>
</template>

<script>
import Logo from "../components/Covid-men";
export default {
  components: {
    Logo,
  },
};
</script>
<style scoped>

#primero {
  display: flex;
  justify-content: space-between;
   

}

h2 {
   font-family: 'DotGothic16', sans-serif;
}
#segundo-container {
  padding: 40px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

#segundo-container p {
  font-size: 1.25rem;
}
</style>
