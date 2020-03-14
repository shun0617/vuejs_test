<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Myhome></Myhome>
    
    

  </div>
</template>

<script>
// @ is an alias to /src
//import Header from '../components/Header.vue'
import Myhome from '../components/Myhome.vue'

export default {
  name: 'home',
  components: {
    Myhome
  }
}
</script>

<style>
* {
    width: 300px;
    margin: 0 auto;
}

</style>
