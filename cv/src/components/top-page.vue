<template>
  <b-container class="top-page">
    <b-row class="text-center">
        <b-col cols="4">
                <b-img src="../assets/photo-moi.jpg" fluid alt="Responsive image" rounded="circle"></b-img>
        </b-col>
        <b-col class="info" cols="8"> 
           <h1>{{ nom }}</h1>
           <p>{{ description }}</p>
        </b-col>
    </b-row>
  </b-container>
</template>


<script>
export default {
  name: 'top-page',
  props: {
    nom : String,
    description: String,
    //img : "../assets/photo-moi.jpg"
  }
}
</script>
<style scoped>
.info{
    padding-top:150px;
}
</style>