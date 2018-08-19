<template>
  <v-app light>
    <v-content>
      <my-navbar></my-navbar>
      
      <my-header></my-header>

      <tech></tech>

      <about></about>

      <contact></contact>
      
      <my-footer></my-footer>
    </v-content>
  </v-app>
</template>

<script>
  import MyNavbar from '@/components/Navbar'
  import MyFooter from '@/components/Footer'
  import MyHeader from '@/components/Header'
  import About from '@/components/About'
  import Contact from '@/components/Contact'
  import Tech from '@/components/Tech'
  
  export default {
      components: { MyNavbar, MyFooter, MyHeader, Contact, About, Tech }  
  }
</script>
