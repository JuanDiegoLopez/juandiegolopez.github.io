<template>
    <section id="contact">
        <v-container grid-list-xl>
          <v-layout row wrap justify-center align-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent text-xs-center">
                  <a href="https://github.com/JuanDiegoLopez">
                    <img src="@/assets/img/github.svg" alt="github-logo" width="50" class="ma-3">
                  </a>
                  <a href="https://www.linkedin.com/in/juan-diego-l%C3%B3pez-triana-17a63915a/">
                    <img src="@/assets/img/linkedin.svg" alt="github-logo" width="50" class="ma-3">
                  </a>
                  <a href="https://www.facebook.com/JuanDiegoLopz">
                    <img src="@/assets/img/facebook.svg" alt="facebook-logo" width="50" class="ma-3">
                  </a>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact me</div>
                </v-card-title>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>(+57) 3185022214</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Bucaramanga, Santander, Colombia</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>juandlopez@msn.com</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
    </section>
</template>

<style scoped>
section {
  background: #f1f1f1;
}
</style>
