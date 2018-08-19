<template>
    <v-toolbar dark>
        <v-toolbar-title>
            <h3 class="name"> {{title}} </h3>
        </v-toolbar-title>
        <v-spacer></v-spacer>
        <v-toolbar-items>
            <v-btn flat="flat" @click="$vuetify.goTo('#tech')">Techs</v-btn>
            <v-btn flat="flat" @click="$vuetify.goTo('#about')">About Me</v-btn>
            <v-btn flat="flat" @click="$vuetify.goTo('#contact')">Contact</v-btn>
        </v-toolbar-items>
    </v-toolbar>
</template>

<script>
export default {
    data () {
        return {
            title: 'Juan Diego López'
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
