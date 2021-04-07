<template>
  <div>
    <div>{{"este es el header"}}</div>
    <div>{{"edonde esta el boton de add filter"}}</div>
    <div>
        <Table/>
    </div>  

  </div>
</template>

<script setup>
import Table from "../components/Table"
export default{
    components:Table,
    props:{
        title:{
            type:String,
            default:"Centro de Ayuda Seif"
        },
    }
}


</script>

<style>

</style>
