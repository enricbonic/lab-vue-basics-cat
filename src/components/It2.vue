<template>
    <h1>Iteration 2</h1>
  Suma simple: "{ {2 + 2} }" = {{2 + 2}}
  <br>
  Suma amb funció: La suma de "n1" i "n2" és {{suma(3, 5)}}
  
</template>

<script setup>
function suma(n1, n2){
return n1 + n2
}
</script>

<style>

</style>