<template>
    <v-flex
      xs12
      sm8
      md6
    >
      </div>
      <v-card>
        <v-card-title class="headline">
          This will lead to your recipies
          </v-card-title>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/recipies"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
</template>

<script>
export default {
  layout: 'default'
}
</script>
