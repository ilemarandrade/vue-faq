<template>
  <div>
    <div>
        <img :src="img">
    </div>
    <div>
        {{label}}
    </div>
    <div>
        {{Bottons}}
    </div>
  </div>
</template>

<script>
export default{
    props:{
        img:{
            type:String,
            default:"Boton"
        },
        label:{
            type:String,
            default:""
        },
        Bottons
    }
}


</script>

<style>

</style>