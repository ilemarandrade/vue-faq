<template>
  <div id="layoutSection">
    <Head/>
    <Nav :location="location" />
    <LayoutProducts/>
  </div>
</template>

<script>
import Menu from "../components/Menu.vue"
import Head from "../components/Head.vue"
import Nav from "../components/Nav.vue"
import LayoutProducts from "../layout/layoutProducts.vue"
export default{
    components:{
        Menu,
        Head,
        Nav,
        LayoutProducts
    },
    props:{
        title:{
            type:String,
            default:"Centro de Ayuda Seif"
        },
    },
    data(){
       return{
           location:false
       } 
    }
}


</script>

<style>
#layoutSection{
    margin-left: 6vw;
    height: 100vh;
    width: 94vw;
    border-right: 0.2em solid black;
    border-bottom: 0.2em solid black;
    border-top:0.2em solid black;
}

</style>