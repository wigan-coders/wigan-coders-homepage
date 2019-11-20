<template>
  <div class="home">
    <div class="home-content">
      <div class="jumbo">
        <p>Welcome to Wigan Coders. Let us help you on your coding journey today!</p>
      </div>
      <h2>Welcome Coders</h2>
      <!-- <button v-on:click="greet()" class="btn">Greet</button> -->
      <div class="top-content">
        <div class="img-1">
          <img src="static/keyboard.jpg" alt="keyboard-image" />
        </div>
        <div class="img-txt-1">
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora ex fugit quae cum temporibus, perspiciatis commodi consequatur eum? Laborum cum commodi quo perferendis maiores natus quod dicta nihil ipsum voluptatem!</p>
        </div>
      </div>
      <div class="mid-content">
        <div class="quote">
          <p>"Talk is cheap, show me the code"</p>
        </div>
      </div>
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
.home {
  font-family: "Poppins", sans-serif;
  color: #726f6f;

}
img {
  border-radius: 10px;
  padding: 5px;
}
h2 {
  text-align: center;
  color: #726f6f;
}
.img-txt-1 {
  padding: 20px;
}
.img-txt-1 p {
  line-height: 35px;
  text-align: center;
}
.home-content {
  margin-top: 4%;
}
.top-content {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
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
.quote {
  background: #f9caca;
  margin-top: 5%;
}
.mid-content p {
  text-align: center;
  padding: 10px;
}
</style>
