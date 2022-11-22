<template>
    <header>
        {{ msg }}
    </header>

    <p>Quando você trabalha em um sistema robusto de vue requer coisa mais avançadas, quando você solicita um loop é sempre necessario fazer o uso de uma key para levar menos tempo na execução.</p>

    <p>No exemplo temos a criação de um loop que pega informações do obj todos, temos a key dada pelo id dos items do objeto e na representação os nomes de cada usuario que está no objeto.</p>

    <ul>
        <li v-for="(obj, index) in todos" v-bind:key="obj.id" class="lista-exemplo">
            {{ index }} - {{ obj.name }}
        </li>
    </ul>
</template>

<script>
export default {
    name: 'Atividade3',
    props: {
        msg: String
    },
    data() {
        return {
            todos: [
                {
                    "id": 1,
                    "name": "Gabriel"
                },
                {
                    "id": 2,
                    "name": "Gustavo"
                },
                {
                    "id": 3,
                    "name": "Mariano"
                },
                {
                    "id": 4,
                    "name": "Breno"
                },
                {
                    "id": 5,
                    "name": "Vinicius"
                },
            ]
        }
    }
}
</script>

<style scoped>
header {
    background-color: rgb(17, 190, 89);
}

ul{
    padding: 0; 
}
.lista-exemplo{
    background-color: rgb(17, 190, 89);
    border-radius: 15px;
    margin: 1rem;
    padding: 1rem;
    color: white;
    text-align: center;
    list-style: none;
    width: 300px;
}
</style>