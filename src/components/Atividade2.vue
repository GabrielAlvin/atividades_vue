<template>
    <header>
        {{ msg }}
    </header>

    <ul>
        <li>Diretivas são instruções que o vue da para os elementos HTML</li>
        <li>Diretivas condicionais v-if, v-else-if, v-else e v-show</li>
        <li>Interpolação é feito por 2 x {}</li>
    </ul>

    <h2>Exemplos</h2>

    <div>
        <p v-if="testevif === 1">Teste if</p>
        <p v-else-if="testevif=== 2">Teste else if</p>
        <p v-else>Teste else</p>
    </div>

    <div v-show="testevshow">Teste do v-show</div>
</template>

<script>
export default {
    name: 'Atividade2',
    props: {
        msg: String
    },
    data(){
        return{
            testevif: 1,
            testevshow: true
        }
    }
}
</script>

<style scoped>
    header{
        background-color: rgb(216, 186, 15);
    }
    div{
        text-align: left;
    }
</style>