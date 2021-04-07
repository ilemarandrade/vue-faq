<template>
  <div>
    <table id="" class="table table_two table-striped table-nowrap" cellspacing="0" width="100%">
        <thead>
            <tr>
                <th>ID Pregunta</th>
                <th>Fecha de creacion</th>
                <th>Modulo</th>
                <th>Pregunta</th>
                <th>Respuesta</th>
                <th>Acciones</th>
            </tr>
        </thead>
        <tbody id='detailaddTicketTable'>
            <tr :v-for="[]">
                <td><td/>
            </tr>   
        </tbody>"

    </table>
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

<style>

</style>