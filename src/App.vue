<template>
  <Atividade1 msg="Conteúdo 1"/>
  <Atividade2 msg="Conteúdo 2"/>
  <Atividade3 msg="Conteúdo 3"/>
  <Atividade4 msg="Conteúdo 4"/>
</template>

<script>
import Atividade1 from './components/Atividade1'
import Atividade2 from './components/Atividade2'
import Atividade3 from './components/Atividade3'
import Atividade4 from './components/Atividade4'

export default {
  name: 'App',
  components: {
    Atividade1,
    Atividade2,
    Atividade3,
    Atividade4,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 2rem;
  text-align: center;
}

header{
  font-size: 20px;
  color: white;
  padding: 5px;
  margin-top: 2rem;
}

li{
  text-align: left;
}

p {
    text-align: justify;
}
</style>
