<template>
    <h1>Iteration 4</h1>
    <ul>
    <li v-for="conte in contes" :key="conte.titol"><b>Títol</b>: {{conte.titol}} <br> <b>Any</b>: {{conte.any}} <br> <b>Contingut</b>: {{conte.contingut}} <br><br></li>
</ul>
    
</template>

<script setup>
import { ref } from 'vue';
const contes = [
{
        titol: "Els Tres Porquets",    
        any: 1892,
        contingut: "Tres porquets prenen el pèl a un llop."
    }, 
    {
        titol: "La Caputxeta Vermella",    
        any: 1893,
        contingut: "Una nena porta menjar a la seva àvia i té problemes amb un llop."
    }, 
    {
        titol: "En Pere i el Llop",    
        any: 1894,
        contingut: "Un nen es riu de la gent del seu poble i se'l menja un llop."
    }
]



</script>

<style>
ul{
    display: flex;
    flex-direction: column;
}
</style>