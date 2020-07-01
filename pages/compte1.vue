<template>
<div> 
    <div class="saumonAlign">
        <br><br><br><br><br>
        Nom:
        <v-card flat>
            <v-card-title >
                <input class="saumonCard" type="text"/>
            </v-card-title>
        </v-card> 
        Prénom:
        <v-card flat>
            <v-card-title >
                <input class="saumonCard" type="text"/>
            </v-card-title>
        </v-card> 
        <br>
    </div>
    <div class="buttonAlign">
      <v-btn  href='/compte2' rounded height="70" width="290" color="#9CBA00">Continuer</v-btn>
      <br><br><br><br><br>
    </div>
        <div class="alignText">
        <p> Etape 1 sur 3 </p>
        </div>
        <div class=alignStep>
        <v-img height="40" width="400" contain :src="require('~/components/compte1.png')" />
        </div>  
</div>
</template>

<script>
export default {
  layout: 'connection'
}
</script>
