<template>
<div>
    <br><br><br>
<div class="text-center">
<v-row
          align="center"
          justify="center"
          background = "none"
          style="height: auto;"
        >
          <v-btn href='/recette' class="recetteCard" rounded height="100" width="300"  color="#FF9900"><h2>Retour</h2></v-btn>
            <v-card class="centreAccueil" height="540px" max-width="1000" 
            elevation="24"
            outlined
            shaped
            color="#E8E7E6">
<v-card-title> <h2>Boeuf Bourguignon: Etape 1</h2></v-card-title>
<v-card-text><h3>Dans un premier temps, pelez les oignons et découpez les en fines rondelles</h3></v-card-text>

  </v-card> 
          <v-btn href='/etape2' class="recetteCard" rounded height="100" width="300"  color="#FF9900"><h2>Etape 2</h2></v-btn>
</v-row>
<br>
<div class="text-center"><h3>Etape 1 sur 8</h3></div>
<v-row align="center"
          justify="center"
          background = "none"
          style="height: auto;">
    <div><v-img height="20" contain :src="require('~/components/barreorange.png')" /></div> &nbsp;&nbsp;
    <div><v-img height="20" contain :src="require('~/components/barreblanche.png')" /></div> &nbsp;&nbsp;
    <div><v-img height="20" contain :src="require('~/components/barreblanche.png')" /></div> &nbsp;&nbsp;
    <div><v-img height="20" contain :src="require('~/components/barreblanche.png')" /></div>

</v-row>
</div> 
</div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
