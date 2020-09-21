<template>
  <div class="home">
    
    <TopPage nom="Arthur Saint Martin" description="Jeune entrepreneur à suivre 😁"/>
  </div>
</template>

<script>
// @ is an alias to /src
import TopPage from '@/components/top-page.vue'

export default {
  name: 'Home',
  components: {
    TopPage
  }
}
</script>
