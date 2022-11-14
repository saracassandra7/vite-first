<script>
export default {
  name: 'AppTitle',
  data(){
    return{
      titolo: 'La mia prima app con Vite!'
    }
  }
}
</script>

<template>
  <div class="container">
    <h1>{{titolo}}</h1>
  </div>
</template>

<style scoped>
h1{
  color: blue;
  margin: 20px
}
</style>