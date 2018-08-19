<template>
    <div>
        <v-toolbar dark>
            <v-toolbar-side-icon class="hidden-sm-and-up" @click="drawer = !drawer"></v-toolbar-side-icon>
            <v-toolbar-title>
                <h3 class="name"> {{title}} </h3>
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-xs-only">
                <v-btn flat="flat" @click="goTo('#tech')">Techs</v-btn>
                <v-btn flat="flat" @click="goTo('#about')">About Me</v-btn>
                <v-btn flat="flat" @click="goTo('#contact')">Contact</v-btn>
            </v-toolbar-items>
        </v-toolbar>
        <v-navigation-drawer v-model="drawer" absolute dark temporary>
            <v-list>
                <v-list-tile @click="goTo('#tech')">
                    <v-list-tile-content>
                        <v-list-tile-title>TECHS</v-list-tile-title>
                    </v-list-tile-content>
                </v-list-tile>
                <v-list-tile @click="goTo('#about')">
                    <v-list-tile-content>
                        <v-list-tile-title>ABOUT ME</v-list-tile-title>
                    </v-list-tile-content>
                </v-list-tile>
                <v-list-tile @click="goTo('#contact')">
                    <v-list-tile-content>
                        <v-list-tile-title>CONTACT</v-list-tile-title>
                    </v-list-tile-content>
                </v-list-tile>
            </v-list>
        </v-navigation-drawer>
    </div>
</template>

<script>
export default {
    data () {
        return {
            title: 'Juan Diego López',
            drawer: false
        }
    },
    methods: {
        goTo (element) {
            this.drawer = false
            this.$vuetify.goTo(element)
        }
    }
}
</script>

<style scoped>
@font-face {
    font-family: 'Pacifico';
    src: url('../assets/fonts/Pacifico-Regular.ttf');
}

.name {
    font-family: Pacifico !important;
    padding-bottom: 10px;
    font-size: 22px;
}

</style>
