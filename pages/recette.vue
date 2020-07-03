<template>
  <div >
    <v-card shaped width="600">
      <v-card-title>
        Liste des résultats pour "Boeuf"
      </v-card-title>
    </v-card> 
    <br>
        <v-row
          align="center"
          justify="center"
          background = "none"
          style="height: auto;"
        >
        <v-btn class="recetteCard" rounded height="280" width="100"  color="#FF9900"><h2 class="pencher">Page Précédente</h2></v-btn>
        <v-card
            :loading="loading"
            class="recetteCard"
            max-width="450"
            height="590px"
            shaped
            color="#E8E7E6"
          >
            <v-img
              height="330"
              src="https://assets.afcdn.com/recipe/20131009/56293_w600.jpg"
            ></v-img>

            <v-card-title>Boeuf Bourguignon</v-card-title>
            <v-card-subtitle class="black--text"> <b>Ingrédients: </b> boeuf, lardons, beurre, vin rouge, oignon, ail, farine </v-card-subtitle>
            <br>
            <b class="tiempo1">Temps:</b><b class="tiempo1">Difficulté:</b><br>
            <b class="tiempo2">1h10</b><b class="tiempo2">Facile</b>
            <v-card-text>
                <v-row align="center"
                justify="center"
                >
                <v-btn href='/apercu' rounded height="60" width="165" outlined color="#FF9900"><a class="black--text"> Aperçu </a></v-btn>
                &nbsp; &nbsp; &nbsp; &nbsp;
                <v-btn href='/etape1' rounded height="60" width="165"  color="#FF9900"> Cuisiner !</v-btn>
                </v-row>
            </v-card-text>
          </v-card>
          <v-card
            max-width="450"
            height="590px"
            shaped
            class="recetteCard"
            color="#E8E7E6"
          >
            <v-img
              height="330"
              src="https://assets.afcdn.com/recipe/20131009/56293_w600.jpg"
            ></v-img>

            <v-card-title>Boeuf Bourguignon</v-card-title>
            <v-card-subtitle class="black--text"> <b>Ingrédients: </b> boeuf, lardons, beurre, vin rouge, oignon, ail, farine </v-card-subtitle>
            <br>
            <b class="tiempo1">Temps:</b><b class="tiempo1">Difficulté:</b><br>
            <b class="tiempo2">1h10</b><b class="tiempo2">Facile</b>
            <v-card-text>
                <v-row align="center"
                justify="center"
                >
                <v-btn href='/apercu' rounded height="60" width="165" outlined color="#FF9900"><a class="black--text"> Aperçu </a></v-btn>
                &nbsp; &nbsp; &nbsp; &nbsp;
                <v-btn href='/etape1' rounded height="60" width="165"  color="#FF9900"> Cuisiner !</v-btn>
                </v-row>            </v-card-text>
          </v-card>
        
        <v-card
            max-width="450"
            height="590px"
            shaped
            class="recetteCard"
            color="#E8E7E6"
          >
            <v-img
              height="330"
              src="https://assets.afcdn.com/recipe/20131009/56293_w600.jpg"
            ></v-img>

            <v-card-title>Boeuf Bourguignon</v-card-title>
            <v-card-subtitle class="black--text"> <b>Ingrédients: </b> boeuf, lardons, beurre, vin rouge, oignon, ail, farine </v-card-subtitle>            
            <br>
            <b class="tiempo1">Temps:</b><b class="tiempo1">Difficulté:</b><br>
            <b class="tiempo2">1h10</b><b class="tiempo2">Facile</b>
            <v-card-text>
                <v-row align="center"
                justify="center"
                >
                <v-btn href='/apercu' rounded height="60" width="165" outlined color="#FF9900"><a class="black--text"> Aperçu </a></v-btn>
                &nbsp; &nbsp; &nbsp; &nbsp;
                <v-btn href='/etape1' rounded height="60" width="165"  color="#FF9900"> Cuisiner !</v-btn>
                </v-row>
            </v-card-text>
          </v-card>
          <v-btn rounded height="280" width="100"  color="#FF9900"><h2 class="pencher">Page suivante</h2></v-btn>
        </v-row>      
  </div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
