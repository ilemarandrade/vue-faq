<template>
  <div id="menu">
    <div>
        <img :src="img">
      
    </div>
    <div>
        <img :src="img">
        <img :src="img">
        <img :src="img">
    </div>
    <div>
        <img :src="img">
    </div>

  </div>
</template>

<script>
import svgExample from "../assets/svgExample.svg" 

export default{
    components:{
    },
    props:{
        img:{
            type:String,
            default:svgExample
        }
    },
    data(){
        return {image:svgExample}
    }
}


</script>

<style scoped>
img{
    background:green;
    width:3em
}
#menu{
    position:absolute;
    height: 100vh;
    width:6vw;
    background: blue;
    border:0.2em solid black;
    padding:1em
}
</style>