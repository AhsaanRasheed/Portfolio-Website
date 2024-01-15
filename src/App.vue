<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

  <Header />
  <RouterView />
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/header.vue';



export default{
  components: {
    Header
  }
}
</script>


<style>
*{
  overflow-x: hidden;
  margin: 0%;
  padding: 0%;
}


</style>