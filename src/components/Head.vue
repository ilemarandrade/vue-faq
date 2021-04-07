<template>
  <div id="Head" class="bb">
    <p>{{title}}</p>
  </div>
</template>

<script>
export default{
    props:{
        title:{
            type:String,
            default:"Centro de Ayuda Seif"
        },
    }
}


</script>

<style scoped>
p{padding: 1em;}
</style>