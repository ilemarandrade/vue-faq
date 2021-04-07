<template>
  <button style="stylesButton" class="perfectCentered fd-column">{{label}}</button>
</template>

<script>
export default{
    props:{
        label:{
            type:String,
            default:"Boton"
        },
        stylesButton:{
            type:String,
            default:""
        } 
    }
}


</script>

<style>

</style>