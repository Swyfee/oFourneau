<template>
  <div>
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
          >     
          
<v-card-title :class="`${hover? 'class1': 'class2'}`"> Cuisine du monde  </v-card-title>
      
            <v-img
            height="600"
              :src="require('~/components/cuisinemonde.png')" 
            />
          </v-card>
          </div>
          </v-hover>

          <v-hover>
        <div slot-scope="{ hover }" class="mx-auto">
          <v-card
            max-width="374"
            elevation="24"
            outlined
            class="mx-auto my-12"
          >
            <v-card-title 
:class="`${hover? 'class1': 'class2'}`">Cuisine française par régions</v-card-title> 
            <v-img
              height="600"
            :src="require('~/components/cuisineregion.png')" 
            />

          </v-card>
          </div>
          </v-hover>

        <v-hover>
        <div slot-scope="{ hover }" class="mx-auto">
        <v-card
            max-width="374"
            elevation="24"
            outlined
          >
          <v-card-title :class="`${hover? 'class1': 'class2'}`">Cuisine de saison</v-card-title>
            <v-img
              height="600"
            :src="require('~/components/cuisinesaison.png')"
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
