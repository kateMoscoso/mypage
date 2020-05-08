<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-center">
        <vuetify-logo />
          <v-col class="py-0">
            <v-list-item
              color="rgba(0, 0, 0, .4)"
              dark
            >
              <v-list-item-content>
                <v-list-item-title class="title">Katherin Moscoso León</v-list-item-title>
                <v-list-item-subtitle>Software Engineer</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
          </v-col>
      </div>
      <v-card>
        <v-card-title class="headline">
          Welcome to my profile web
        </v-card-title>
        <v-card-text>
          <p>
            I'm a software engineer. I'm looking for an company that offer constant learning culture which encourages employee training and work with agile software development.
Currently, learning Vue with Nuxt
          </p>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
          >
            Nuxt Documentation
          </a>
          <br>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
          >
            Nuxt GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    VuetifyLogo
  }
}
</script>
