<template>
<div>
<v-row
          align="center"
          justify="center"
          background = "none"
          style="height: auto;"
        >
    <div class="text-center">
        <v-card class="centreAccueil" max-width="800" 
            elevation="24"
            outlined
            shaped
                        color="#E8E7E6"
>
    <v-card-subtitle class="black--text"><br>
        <h2>Vous n'êtes pas connecté, pour accéder à cette fonctionnalité <br>connectez-vous en cliquant sur le bouton:</h2>
    </v-card-subtitle><br>
    <v-btn href='/macuisine' rounded height="70" width="290" color="#FF9900">Connexion</v-btn>
      <br><br><br><h3>Pas de compte ?</h3>
              <h3> La création de votre compte nous permettra juste de retenir vos préferences.</h3><br>
            <v-btn href='/compte1' rounded height="50" width="450" color="#9CBA00">S'inscire</v-btn><br><br><br>
  </v-card> 
</div> 
</v-row>
</div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
