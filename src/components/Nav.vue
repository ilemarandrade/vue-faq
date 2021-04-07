<template>
  <div id="Nav" v-if="!location" class="perfectCentered bb" >
    <Bottons label="Anadir material de apoyo"/>
  </div>
   <div id="Nav" class="bb" v-else>
    <span>
        {{path}}
    </span>
  </div>
</template>

<script>
import Bottons from "./Bottons.vue"
export default{
    components:{
        Bottons
    },
    props:{
      location:
      {
          type:Boolean,
          default:true,
      },
      path:{
          type:String,
          default:""
      }
    }
}


</script>

<style>
#Nav{
  padding:1em  
}
</style>