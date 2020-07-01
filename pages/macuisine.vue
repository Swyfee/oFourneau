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
      <v-btn href='/macuisineco' rounded height="70" width="290" color="#FF9900">Connexion</v-btn>
    </div>
</div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
