<template>
  <div>
      <label>
          {{label}}
      </label>
      <textarea :placeholder="placeholder">
  </div>
</template>

<script>

export default{
    props:{
        label:{
            type:String,
            default:""
        },
        plaholder:{
            type:String,
            default:"Ingrese algun dato"
        } 
    }
}


</script>

<style scoped>
textarea{
    width:100%;
    height:20vh;
    min-width: 100%;
    max-height: 25vh;
}
</style>