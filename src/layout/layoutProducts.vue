<template>
  <div>
    <div class="padding-1 bb perfectCentered">Nuestros Productos</div>
    <div class="containerProducts df dfw">
        <DivProducts :key="index" v-for="(item,index) in products" :name="item.name" :img="item.img"/>
    </div>
  </div>
</template>

<script>
import {data} from "../const/const"
import DivProducts from "../components/DivProducts.vue"
console.log(data)
export default{
    components:{
        DivProducts,
    },
    props:{
        title:{
            type:String,
            default:"Centro de Ayuda Seif"
        },
    },
    mounted(){
    },
    data(){
        return{
            products:data.products
        }
    }
}


</script>

<style>
.containerProducts{
    padding: 1em 5em;
}
</style>