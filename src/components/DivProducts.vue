<template>
  <div class="divProduct border perfectCentered fd-column">
      
      <img :src="img" class="mb-1">

      <div class="">
          {{name}}
      </div>
      <div class="mb-1">
          <Bottons/>
      </div>
  </div>
</template>

<script>
import Bottons from './Bottons.vue'
import svgExample from "../assets/svgExample.svg" 
export default{
  components: {Bottons},
    props:{
        img:{
            type:String,
            default:""
        },
        name:{
            type:String,
            default:"Titulo"
        } 
    },
    data(){
        return{
            img:svgExample
        }
    }
}


</script>

<style>
img{
    width:4em
}
.divProduct{
    height: 10em;
    width: 10em;
    border-radius: 0.5em;
    margin:2em
}
</style>