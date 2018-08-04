<template>
  <div>
    <app-header></app-header>  
  <app-navbar></app-navbar>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'
export default {
  components: {
    'app-header': Header,
    'app-navbar': Navbar,
  }
}
</script>

<style>

</style>
