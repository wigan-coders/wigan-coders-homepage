<template>
  <div class="navbar">
    <nav class="grey darken-3">
      <router-link :to="{name: 'Home' }" class="brand-logo left">Wigan Coders
      </router-link>

      <span>Supercharge your coding skills</span>
          <i class="fas fa-laptop-code fa-spin"></i>

      <ul class="right">
        <li>
          <router-link :to="{name: 'About' }">About</router-link>
        </li>
        <li>
          <router-link :to="{name: 'Contact' }">Contact us</router-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {};
  }
};
</script>

<style>
.navbar {
  font-family: "Poppins", sans-serif;
}
nav {
  height: 100px;

}
.nav {
  height: 100px !important;
}
ul {
  position: relative;
  top: 36px;
}

.navbar span {
  position: relative;
  top: 26px;
  left: 6px;
}
.brand-logo {
  position: relative;
  left: 5px;
}
.fa-spin {
  font-size: 30px !important;
}

@media only screen and (max-width: 400px) {
  ul li a{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    position: relative;
    bottom: 48px;
      }
}
</style>
