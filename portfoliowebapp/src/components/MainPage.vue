<template>
  <div class="mainPage">
    <div class="menu">
      <div class="item"> 
        <div class="itemText">Projects </div>
      </div> 
      <div class="item" >
        <div class="itemText">About me</div>
       </div> 
      <div class="item" >  
        <div class="itemText">CV</div>
    </div>
    </div>
  
    
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
             //this.testText="Voll der Kuhle text wow"
        } 
    },

}
</script>

<style>

.item{
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.itemText:hover{
  color:lightblue;
  border:2px solid blue; 
}
.itemText{
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
}

.menu{
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
  height: 60px;
}
.mainPage{
  vertical-align: center;
  align-items: center;
}

</style>