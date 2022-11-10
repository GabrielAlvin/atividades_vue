<template>
  <Atividade1 msg="Conteudo 1"/>
  <Atividade2 msg="Conteudo 2"/>
</template>

<script>
import Atividade1 from './components/Atividade1'
import Atividade2 from './components/Atividade2'

export default {
  name: 'App',
  components: {
    Atividade1,
    Atividade2
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 40px;
  text-align: center;
}

header{
  font-size: 20px;
  color: white;
  padding: 5px;
}

li{
  text-align: left;
}
</style>
