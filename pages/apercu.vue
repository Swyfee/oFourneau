<template>
  <div >
    <br><br>
        <v-row
          align="center"
          justify="center"
          background = "none"
          style="height: auto;"
        >
        <v-btn  href='/recette' class="recetteCard" rounded height="280" width="100"  color="#FF9900"><h2 class="pencher">Retour</h2></v-btn>
    <v-card max-width="3000" height="650px" shaped outlined elevation="24"> 
        <v-row> 
        <v-card
            class="apercuCard"
            max-width="370"
            height="440px"
            shaped
          >
          <v-card-title>Boeuf Bourguignon</v-card-title>
            <v-img
              height="200"
              src="https://assets.afcdn.com/recipe/20131009/56293_w600.jpg"
            ></v-img>

            <v-card-subtitle class="black--text"> <b>Préparation: </b> 10 minutes <br> <b>Cuisson: </b> 1 heure <br> <b>Difficulté: </b> Facile</v-card-subtitle>
            <br>
            <v-card-text>
            </v-card-text>
          </v-card>
          <v-card
            max-width="375"
            height="440px"
            shaped
            class="apercuCard"
          >
            <v-card-title>Liste des Ingrédients :</v-card-title>
            <v-card-subtitle class="black--text">
            <b>800</b> g de boeuf pour Bourguignon<br>
            <b>100</b> g de lardons<br>
            <b>50</b> g de beurre <i>ou </i><b>3</b> cuilières à soupe d'huile<br>
            <b>2/3</b> l de vin rouge<br>
            <b>2</b> oignons<br>
            <b>1</b> gousse d'ail<br>
            <b>2</b> cuillières à soupe de farine<br>
            <b>1</b> bouquet garni<br>
            <b>250</b> g de champignon de Paris<br>
            </v-card-subtitle>

          </v-card>
        
        <v-card
            max-width="370"
            height="440px"
            shaped
            class="apercuCard"
          >
            <v-card-title>Derniers commentaires :</v-card-title>
            <v-card-subtitle class="black--text"> 
                <b>Cindy_Crosset, </b> le 26/05/2020 à 01:37 <br>
                    __________________________________________________ <br>  
                    Délicieux, J'ai suivis les commentaires et j'ai donc rajouté 3 carrotes et ai fait cuire le tout. Résultat: légumes fondants, viande super tendre et sauce parfaite!<br><br>    
                <b>Ed-Warner, </b> le 05/09/2019 à 9:07 <br>
                    __________________________________________________  <br>   
                    Parfait. Vraiment rien à rajouter<br><br>   
                <b>Pascalorto, </b> le 21/11/2019 à 11:45 <br>
                    __________________________________________________  <br>            
                    Simple, efficace.<br><br>  
            
            </v-card-subtitle>            
            <br>
 
          </v-card>
          <div class="recetteCard"/>
          </v-row> 
          <br>
            <v-img height="50" contain :src="require('~/components/vieucompteur.png')" /><br>
            <v-btn href='/etape1' class="btnApercu" rounded height="70px" width="250"  color="#FF9900">Cuisiner !</v-btn>
        </v-card>     
        </v-row> 
  </div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
