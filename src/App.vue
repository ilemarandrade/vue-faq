<template>
  <ViewPrincipal/>
</template>

<script>
import ViewPrincipal from './views/viewPrincipal.vue'
export default{
  components:{
    ViewPrincipal
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}
body,p{
  margin:0px
}
.df
{
  display:flex
}
.dfw{
  flex-wrap: wrap;
}
.jtf-center{
  justify-content: center;
}
.perfectCentered{
  display:flex;
  align-items: center;
  justify-content: center;
}
.fd-column
{
  flex-direction: column;
}
.bb{
  border-bottom: 0.2em solid black;
}
.border{
  border: 0.2em solid black;
}
.padding-1{
  padding:1em
}
.mb-1{
  margin-bottom:1em
}
</style>