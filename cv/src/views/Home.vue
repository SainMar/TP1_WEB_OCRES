<template>
  <div class="Home">
    <Menu />
    <TopPage nom="Arthur Saint Martin" description="Jeune entrepreneur à suivre 😁"/>
    <CvCarousel />
    <Contact />
    
  </div>
</template>

<script>
// @ is an alias to /src
import TopPage from '@/components/top-page.vue'
import Menu from '@/components/nav_menu.vue'
import CvCarousel from '@/components/cv_carousel.vue'
import Contact from '@/components/contact.vue'

export default {
  name: 'Home',
  components: {
    TopPage,
    CvCarousel,
    Contact,
    Menu
  }
}
</script>
