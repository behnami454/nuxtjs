<template>
  <div class="container">
    <Cardone />
    <Cardtwo
      v-for="Oneei in Onee"
      :key="Oneei.id"
      :Oneeii="Oneei"
     />
     <PageNotFound />
     
     
    


  </div>
</template>

<script>
import { Cardtwo } from "@/assets/data.js"
  export default {
    data(){
      return{
        Onee: Cardtwo
      }
    }
    
    
  }
</script>

<style scoped>


</style>