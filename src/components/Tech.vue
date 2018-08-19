<template>
    <section id="tech">
        <v-container class="pa-5">
            <v-layout row wrap>
                <v-flex xs12 sm6 md4 class="pa-2">
                    <v-card elevation-5 class="text-xs-center pa-2" height="300">
                        <img src="public/frontend.png" alt="frontend" width="80">
                        <h1 class="headline">Frontend Development</h1>
                        <br>
                        <ul class="body-1">
                            <li>HTML5, CSS3 JavaScript</li>
                            <li>VueJS, VuetifyJS, NuxtJS</li>
                            <li>Angular 4</li>
                            <li>Sass, PostCSS</li>
                            <li>Boostrap, MaterializeCSS</li>
                            <li>Pug, Ejs</li>
                        </ul>
                    </v-card>
                </v-flex>
                <v-flex xs12 sm6 md4 class="pa-2">
                    <v-card elevation-5 class="text-xs-center pa-2" height="300">
                        <img src="public/backend.jpg" alt="backend" width="130">
                        <h1 class="headline">Backend Development</h1>
                        <br>
                        <ul class="subheading">
                            <li>NodeJS, ExpressJS</li>
                            <li>PHP, SQL</li>
                            <li>MongoDB</li>
                            <li>MySQL, PostgreSQL</li>
                        </ul>
                    </v-card>
                </v-flex>
                <v-flex xs12 sm6 md4 class="pa-2">
                    <v-card elevation-5 class="text-xs-center pa-2" height="300">
                        <img src="public/cordova.png" alt="backend" width="140">
                        <h1 class="headline">Mobile Development</h1>
                        <br>
                        <ul class="subheading">
                            <li>Cordova</li>
                            <li>Phonegap</li>
                            <li>PWA</li>
                        </ul>
                    </v-card>
                </v-flex>
            </v-layout>
        </v-container>
    </section>
</template>

<style scoped>
ul {
    list-style: none;
}

section {
    background: #f1f1f1;
}
</style>
