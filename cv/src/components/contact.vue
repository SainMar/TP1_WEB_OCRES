<template>
    <div class="Contact">
        <h1>CONTACT</h1>
        <Info tel="+33 06 89 49 22 32"></Info>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Totam dolores ipsam animi, exercitationem itaque aspernatur doloremque! Tenetur, distinctio incidunt, cupiditate vitae nemo aliquam voluptates delectus aliquid rem ut tempora assumenda.</p>
    </div>
    
</template>

<script>

import Info from '@/components/info.vue'

export default {
    name : "Contact",
    component:{
        Info
    }
}
</script>