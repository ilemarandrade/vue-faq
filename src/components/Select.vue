<template>
  <div>
    <label></label>
    <select>
        <options :value="0">{{"Seleccione el "+label}}</options>
        <options :v-for="(item,index) in options" :value="item.val">{{item.label}}</options>
    </select>
  </div>
</template>

<script>
export default{
    props:{
        options:{
            type:Array,
            default:[]
        },
        label:{
            type:String,
            default:""
        } 
    }
}


</script>

<style>

</style>