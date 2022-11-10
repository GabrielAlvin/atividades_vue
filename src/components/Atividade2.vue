<template>
    <header>
        {{ msg }}
    </header>

    <ul>
        <li>Diretivas são instruções que o vue da para os elementos HTML</li>
        <li>Diretivas condicionais v-if, v-else-if, v-else e v-show</li>
    </ul>
</template>

<script>
export default {
    name: 'Atividade2',
    props: {
        msg: String
    }
}
</script>

<style scoped>
    header{
        background-color: rgb(216, 186, 15);
    }
</style>