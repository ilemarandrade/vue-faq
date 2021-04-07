<template>
  <div>
      <label>
          {{label}}
      </label>
      <input :placeholder="placeholder">
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
input{
    width:100%
}
</style>