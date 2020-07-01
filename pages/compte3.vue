<template>
<div> 
    <div class="alignStep">
        <br><br><br><br>
        Nous vous demandons ces informations afin de pouvoir vous 
        <br>offrir la possibilité d'utiliser notre application à son maximum.
        <br><br>
        Nous n'utiliserons pas vos données à des fins commerciales.
        <br><br><br>
       <input class="checkbox" type="checkbox">    J'ai lu et j'accepte la politique de confidentialité
    </div>
          <br><br><br><br><br>

    <div class="buttonAlign">
      <v-btn  href='/macuisineco' rounded height="70" width="290" color="#9CBA00">Terminer</v-btn>
      <br><br><br><br><br>
    </div>
        <div class="alignText">
        <p> Etape 3 sur 3 </p>
        </div>
        <div class=alignStep>
        <v-img height="40" width="400" contain :src="require('~/components/compte3.png')" />
        </div>  
</div>
</template>

<script>
export default {
  layout: 'connection'
}
</script>
