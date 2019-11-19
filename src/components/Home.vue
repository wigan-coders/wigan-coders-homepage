<template>
  <div class="home">
    <div class="home-content">
      <div class="jumbo">
        <p>Welcome to Wigan Coders. Let us help you on your coding journey today!</p>
      </div>
      <h2>Welcome Home</h2>
    </div>
    <footer class="grey darken-3">
      <div class="copyright">Copyright 2019</div>
      <div>Created by Ryan Brockley</div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {};
  }
};
</script>

<style>
.home-content {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 4%;
}
nav {
  height: 100px;
}
.nav {
  height: 100% !important;
  max-height: 100px !important;
}
footer {
  color: #e6e8e1;
  height: 100%;
  max-height: 100px !important;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: row;
  padding: 20px;
}
.copyright {
  padding: 5px;
}
.jumbo {
  background: #39a2f2;
  width: 100%;
  padding: 20px;
  color: #fff;
  margin-bottom: 50px;
  text-align: center;
}
.home-content p {
  padding: 0;
  margin: 0;
}
</style>
