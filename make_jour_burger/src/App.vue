<template>
  <Navbar />

  <!-- oq estiver em router-view é mutavel, oq tem encima será um padrãop em todas as paginas -->
  <router-view/>
  <Footer />
</template>

<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

export default{
  components:{
    Navbar,
    Footer
}
}

</script>

<style>

</style>
