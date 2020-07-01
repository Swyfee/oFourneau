<template>
<div>
<div class="searchbar">
    <v-img height="100" contain :src="require('~/components/logo.png')" />
</div>
  <v-card class="connection">
    <v-card-title>
      <input type="text" value="E-mail"/>
    </v-card-title>
  </v-card> 
  <v-card class="connection">
    <v-card-title>
      <input type="text" value="Mot de passe"/>
    </v-card-title>
  </v-card>
    <div class="text-center">
      <v-btn href='/macuisineco' rounded height="70" width="290" color="#9CBA00">Connexion</v-btn>
      <br><br><br>Pas de compte ?
      <br>
            <v-btn href='/compte1' rounded height="50" width="450" color="#9CBA00">S'inscire</v-btn>
    </div>
</div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
