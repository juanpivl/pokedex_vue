<template>
  <div>
    <div class="center">
      <img src="https://pokedexproject1.herokuapp.com/images/Pokedex.png">
      
    </div>
    
    
  </div>
</template>

<script>
export default {
  data(){
    return{
      
    }
  },
  create(){
    this.miMetodo()
  },
  methods:{
    miMetodo(){
      console.log("mi metodo");
    }
  }
}
</script>

<style scoped>
 .center{
  text-align: center;
  margin: 1%;
 }
</style>
