<template>
  <div class="slide-carousel">
    <b-card   alt="Card image" class="bg-dark text-white border-0">
      <div class="card-img-overlay d-flex align-items-center">
        <b-col>
            
          <b-card-title title-tag="h5" class="h2 text-white mb-2">{{ titre1 }}</b-card-title>
          <b-card-text >This is a wider card with supporting text below as a natural lead-in to additional
            content. This content is a little bit longer.</b-card-text>
          <b-card-text class="text-sm font-weight-bold">Last updated 3 mins ago</b-card-text>
        </b-col>

        <b-col>
            
          <b-card-title title-tag="h5" class="h2 text-white mb-2">{{ titre2 }}</b-card-title>
          <b-card-text >This is a wider card with supporting text below as a natural lead-in to additional
            content. This content is a little bit longer.</b-card-text>
          <b-card-text class="text-sm font-weight-bold">Last updated 3 mins ago</b-card-text>
        </b-col>

        <b-col>
            
          <b-card-title title-tag="h5" class="h2 text-white mb-2">{{ titre3 }}</b-card-title>
          <b-card-text >This is a wider card with supporting text below as a natural lead-in to additional
            content. This content is a little bit longer.</b-card-text>
          <b-card-text class="text-sm font-weight-bold">Last updated 3 mins ago</b-card-text>
        </b-col>

      </div>
    </b-card>
  </div>
</template>

<script>
export default {
    name: "slide-carousel",
    props:{
        titre1 : String,
        titre2 : String,
        titre3 : String
    }
}
</script>

<style scoped>
.card-body{
  width: 200px;
  height: 300px;
}
</style>