<template>
  <div class="top-page">
    <b-jumbotron header="Welcome on my CV Website" lead="Bootstrap v4 Components for Vue.js 2">
    <b-row class="top-top-page"></b-row>  
    <b-row class="text-center">
        <b-col cols="4">
                <b-img id="img-profile" src="../assets/photo-moi.jpg" rounded alt="Rounded image"></b-img>
        </b-col>
        <b-col class="info" cols="8"> 
           <h1>{{ nom }}</h1>
           <p>{{ description }}</p>
        </b-col>
    </b-row>

  </b-jumbotron>
  </div>
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
.top-top-page{
  margin-bottom: 150px;
}
.info{
    padding-top:150px;
    
}
#img-profile{
  width: 150px;
  height: auto;
}
.top-page{
  background-color: #F2AA48;
  
}
</style>