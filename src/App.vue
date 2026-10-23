<script setup>
const people = ref([
  { name: 'Jan', age: 12 },
   { name: 'Piet', age: 20 }
])

const newName = ref()
const newAge = ref()

function addPerson(){

}
</script>

<template>
  <form></form>
<input v-model.number="newAge">
<input v-model="newName">
<button>toevoegen</button>
</template>