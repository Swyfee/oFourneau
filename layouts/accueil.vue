<template>
  <v-app>
    <v-app-bar
      color='#9CBA00'
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
            color=transparent
            v-for="(item, i) in items"
            :key="i"
            :to="item.to"
          >
          <div>
            <br><br>
            <div class="text-center">
              <v-toolbar-item-title  v-text="item.title"/>
            </div>
            <br><br>

              <HR/>
          </div>
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
          title: 'Accueil',
          to: '/',
        },
        {
          title: 'Recettes',
          to: '/recette',
        },
        {
          title: 'Découverte',
          to: '/decouverte',
        },
        {
          title: 'Ma Cuisine',
          to: '/macuisine',
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
