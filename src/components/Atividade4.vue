<template>
    <header>
        {{ msg }}
    </header>

    <p>A diretiva V-bind te da uma instrução que transforma o atributo em dinâmico. (Todo valor que passarmos dentro do atributo vai ter de ser dinamico)</p>

    <img 
        src="https://thumbs.dreamstime.com/b/homem-cinzento-do-placeholder-da-foto-pessoa-gen%C3%A9rica-silhueta-cinzenta-em-um-fundo-branco-144511705.jpg" 
        alt=""
    >
</template>

<script>
export default {
    name: 'Atividade4',
    props: {
        msg: String
    }
}
</script>

<style scoped>
    header{
        background-color: rgb(190, 28, 17);
    }
    img{
        width: 200px;
    }
</style>