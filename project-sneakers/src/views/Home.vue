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
import { componentN } from '../data/API.json'

export default{ 
  name: 'Home',
  components: {
    Mainpage,
    Footer,
    Apropos,
    Affichage
  },
  data () {
    return componentN
  },
}

</script>

<style scoped>

</style>
