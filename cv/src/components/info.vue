<template>
   <div class="info">
        <b-card header="Information about me"  border-variant="dark" align="center">
            <b-col>
                <b-card-text>
                    Telephone : {{tel}} 
                    Adresse : 20, rue Notre Dame de Nazareth 75003 Paris
                    Email : arthur.saint-martin@edu.ece.fr
                </b-card-text>
            </b-col>
        </b-card>   
   </div>
</template>
 
<script>
export default {
    name : "info",
    props:{
        tel : String
    }

}
</script>