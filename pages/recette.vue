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
        <v-card
            :loading="loading"
            class="mx-auto my-12"
            max-width="374"
          >
            <v-img
              height="250"
              src="https://assets.afcdn.com/recipe/20131009/56293_w600.jpg"
            ></v-img>

            <v-card-title>Boeuf Bourguignon</v-card-title>

            <v-card-text>
              <v-row
                align="center"
                class="mx-0"
              >
                <v-rating
                  :value="4.5"
                  color="amber"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>

                <div class="grey--text ml-4">4.5 (413)</div>
              </v-row>

              <div class="my-4 subtitle-1">
                $ • Italian, Cafe
              </div>

              <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
            </v-card-text>
          </v-card>
          <v-card
            :loading="loading"
            class="mx-auto my-12"
            max-width="374"
          >
            <v-img
              height="250"
              src="https://assets.afcdn.com/recipe/20131009/56293_w600.jpg"
            ></v-img>

            <v-card-title>Boeuf Bourguignon</v-card-title>

            <v-card-text>
              <v-row
                align="center"
                class="mx-0"
              >
                <v-rating
                  :value="4.5"
                  color="amber"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>

                <div class="grey--text ml-4">4.5 (413)</div>
              </v-row>

              <div class="my-4 subtitle-1">
                $ • Italian, Cafe
              </div>

              <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
            </v-card-text>
          </v-card>
        
        <v-card
            :loading="loading"
            class="mx-auto my-12"
            max-width="374"
          >
            <v-img
              height="250"
              src="https://assets.afcdn.com/recipe/20131009/56293_w600.jpg"
            ></v-img>

            <v-card-title>Boeuf Bourguignon</v-card-title>

            <v-card-text>
              <v-row
                align="center"
                class="mx-0"
              >
                <v-rating
                  :value="4.5"
                  color="amber"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>

                <div class="grey--text ml-4">4.5 (413)</div>
              </v-row>

              <div class="my-4 subtitle-1">
                $ • Italian, Cafe
              </div>

              <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
            </v-card-text>
          </v-card>
        
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
