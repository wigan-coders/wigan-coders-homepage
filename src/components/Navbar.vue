<template>
  <div class="navbar">
  <nav class="grey darken-3">
      <router-link :to="{name: 'Home' }" class="brand-logo left">Wigan Coders</router-link>
      <ul class="right">
        <li><router-link :to="{name: 'About' }">About</router-link></li>
        <li><router-link :to="{name: 'Contact' }">Contact us</router-link></li>


      </ul>
  </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
    }
  }
}
</script>

<style>
.navbar {
  font-family: 'Poppins', sans-serif;

}

</style>
