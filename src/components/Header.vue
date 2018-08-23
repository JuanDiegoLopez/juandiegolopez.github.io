<template>
    <v-parallax src="public/section1.jpg" height="600">
        <v-layout column align-center justify-center class="white--text">
        <v-avatar size="200">
            <img src="public/profile_photo.png" alt="photo.js" height="200">
        </v-avatar>
        <br>
        <h1 class="white--text mb-2 display-1 text-xs-center font-weight-black">Fullstack Developer</h1>
        <h2> with <span>JavaScript 💙</span></h2>
        </v-layout>
    </v-parallax>
</template>

<style scoped>
    h2 span {
    color: #64b5f6;
    }
</style>