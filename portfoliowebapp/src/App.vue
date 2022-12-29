<template>
  <MainPage></MainPage>
</template>

<script>

import MainPage from './components/MainPage.vue';



export default {
  name: 'App',
  components: {
    MainPage,
},
methods: {
  changePage(){
    this.MainPage.call
  }
},
}
</script>

<style>
body{
  background-color: black;
}
</style>
