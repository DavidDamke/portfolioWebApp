<template>
  <div>
    <button v-bind:id="button1">Hi</button>
    <text>{{testText}}</text>
  </div>
</template>

<script>

export default {
    data() {
        return {
           testText:" "
        }
    },

function showText(){
     testText="Voll der Kuhle text wow   "
}
}
</script>

<style>

</style>