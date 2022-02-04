<template>
  <div class="home">
    <Mainpage/>
    <Affichage/>
    <Apropos/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Mainpage from '@/components/Mainpage.vue'
import Footer from "../components/Footer.vue"
import Affichage from "../components/Affichage.vue"
import Apropos from '../components/Apropos.vue'


export default{ 
  name: 'Home',
  components: {
    Mainpage,
    Footer,
    Apropos,
    Affichage
  },
  
}

</script>

<style scoped>

</style>
