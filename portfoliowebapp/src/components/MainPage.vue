<template>
  <div>
    <button v-bind:id="button1" @click="showText">Hi</button>
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

    methods: {
        showText(){
             this.testText="Voll der Kuhle text wow"
        } 
    },

}
</script>

<style>

</style>