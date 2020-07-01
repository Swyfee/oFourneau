<template>
<div> 
    <div class="saumonAlign">
        <br><br><br><br>
        Votre adresse E-mail:
        <v-card flat>
            <v-card-title >
                <input class="saumonCard" type="text"/>
            </v-card-title>
        </v-card> 
        Choisissez votre mot de passe:
        <v-card flat>
            <v-card-title >
                <input class="saumonCard" type="text"/>
            </v-card-title>
        </v-card> 
        Confirmez votre mot de passe:
        <v-card flat>
            <v-card-title >
                <input class="saumonCard" type="text"/>
            </v-card-title>
        </v-card> 
        <br>
    </div>
    <div class="buttonAlign">
      <v-btn  href='/compte3' rounded height="70" width="290" color="#FF9900">Continuer</v-btn>
      <br><br><br><br><br>
    </div>
        <div class="alignText">
        <p> Etape 2 sur 3 </p>
        </div>
        <div class=alignStep>
        <v-img height="40" width="400" contain :src="require('~/components/compte2.png')" />
        </div>  
</div>
</template>

<script>
export default {
  layout: 'connection'
}
</script>
