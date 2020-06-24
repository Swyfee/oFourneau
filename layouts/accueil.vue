<template>
  <v-app>
    <v-app-bar
      color='#FFDD63'
      app
      height="220"
    >
    <div class="centreAccueil">
      <div >
        <v-img height="100" max-width contain :src="require('~/components/logo.png')"   />
      </div>
        <div>
          <v-btn 
           width="250"
            height="80"
            class="ma-4" 
            color='#FAAF03'
            v-for="(item, i) in items"
            :key="i"
            :to="item.to"
          >
           <v-toolbar-item-title v-text="item.title"/>
        </v-btn >
        </div>
    </div>
    </v-app-bar>

          <v-main  class="accueil">
            <v-container>
              <nuxt />
            </v-container>
          </v-main>
    <v-navigation-drawer
      v-model="rightDrawer"
      :right="right"
      temporary
      app
    >
      <v-list>
        <v-list-item @click.native="right = !right">
          <v-list-item-action>
            <v-icon light>
              mdi-repeat
            </v-icon>
          </v-list-item-action>
          <v-list-item-title>Switch drawer (click me)</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-footer
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          title: 'Recettes',
          to: '/recette',
          color: "#F59603"
        },
        {
          title: 'Découverte',
          to: '/decouverte',
          color: "#F59603"
        },
        {
          title: 'Ma Cuisine',
          to: '/macuisine',
          color: "#F59603"

        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js',
      hover: false,   
    };
  }
}
</script>
