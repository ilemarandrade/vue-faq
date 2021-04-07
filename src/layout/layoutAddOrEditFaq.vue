<template>
  <div>
    <div>{{header}}</div>
    <div id="bodyOfForm">
        <Select/>
        <Select/>
        <Select/>
        <Select/>
        <Input/>
        <Textarea/>
    </div>
  </div>
</template>

<script>
import Select from "../components/Select.vue"
import Input from "../components/Input.vue"
import Textarea from "../components/TextArea.vue"
export default{
    components:{
        Select,
        Input,
        Textarea
    },
    props:{
        header:{
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