<template>
  <div>
      <br><br>
    <v-row>
      <v-col cols="12">
        <v-row
          align="center"
          justify="center"
          background = "none"
          style="height: auto;"
        >
        <v-hover>
        <div slot-scope="{ hover }" class="mx-auto ">
        <v-card
            max-width="374"
            elevation="24"
            outlined
            shaped
            color="#FF9900"
            href='/proposerrecette'
          >         
            <v-card-title
             
    :class="`${hover? 'class1': 'class2'}`">Proposer une recette</v-card-title>
            <v-img
              height="600"
              :src="require('~/components/recette.jpg')" 

            />
          </v-card>
          </div>
          </v-hover>

          <v-hover>
        <div slot-scope="{ hover }" class="mx-auto ">
          <v-card
            max-width="374"
            elevation="24"
            outlined
            shaped
            color="#FF9900"
          >
            <v-card-title
:class="`${hover? 'class1': 'class2'}`">Mon frigo</v-card-title>
            <v-img
              height="600"
            :src="require('~/components/frigo.jpg')" 
            />
          </v-card>
        </div>
          </v-hover>

        <v-hover>
        <div slot-scope="{ hover }" class="mx-auto ">
        <v-card
            max-width="374"
            elevation="24"
            outlined
            shaped
            color="#FF9900"
          >
          <v-card-title
:class="`${hover? 'class1': 'class2'}`">Cuisine de saison</v-card-title>
            <v-img
              height="600"
            :src="require('~/components/cuisinecarnet.jpg')"
            />
          </v-card>
        </div>
        </v-hover>
        
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
