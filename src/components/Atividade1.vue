<template>
    <header>
        {{ msg }}
    </header>

    <ul>
        <li>Foi uma aula mais para organização e qualidade</li>
        <li>Não use nomes parecidos com elementos HTML</li>
    </ul>
</template>

<script>
export default {
    name: 'Atividade1',
    props: {
        msg: String
    }
}
</script>

<style scoped>
    header{
        background-color: rgb(17, 17, 190);
    }
</style>