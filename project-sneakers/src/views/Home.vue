<template>
  <div class="home">
    <Mainpage/>
  </div>
</template>

<script>
// @ is an alias to /src
import Mainpage from '@/components/Mainpage.vue'
import { componentN } from '../data/API.json'

export default{ 
  name: 'Home',
  components: {
    Mainpage
  },
  data () {
    return componentN
  },
}

</script>

<style scoped>

</style>
