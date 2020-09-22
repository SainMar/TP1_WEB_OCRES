<template>
<div class="cv">
    <agile>
        <div class="slide">
            <SlideCarousel titre1="EXPERIENCE PRO" titre2="EXPERIENCE PRO" titre3="EXPERIENCE PRO"/>
        </div>
        
        
        
        <div class="slide">
             <SlideCarousel titre1="EDUCATION" titre2="EDUCATION" titre3="EDUCATION"/>
        </div>
    </agile>
</div>
</template>

<script>

import { VueAgile } from 'vue-agile'
import SlideCarousel from '@/components/slide_carousel.vue'

export default { 
    components: {
        agile: VueAgile,
        SlideCarousel

    }
}

</script>
<style scoped>

</style>