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
          <p>Learning how to code can be a very daunting experience. Here at Wigan Coders, we try to help you understand any technical jargon, and help get you started on the correct path into learning how to code. Our Meet-Up group is led by two full time web developers with industry experience, ensuring you are taught the best in up to date coding practices.</p>
        </div>
      </div>
      <div class="mid-content">
        <div class="first">
            <h4>Let's build the future together!</h4>
            <div class="icons-first">
              <i class="fas fa-tablet-alt"></i>
              <i class="far fa-window-restore"></i>
            </div>
            <div class="second">
              <p>If it's websites or applications you would like to build, or gain knowledge in how this is done, then this is the place for you. We have course is HTML and CSS and very soon to be JavaScript. These three coding practices combined can help us build some beautiful, responsive websites and applications.</p>
          </div>
        </div>
      </div>
    </div>
    <footer class="page-footer grey darken-3">

      <div class="footer-copyright">Copyright Wigan Coders 2019</div>
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
  width: 100%;
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
  width: 100%;
}
ul {
  position: relative;
}
h4 {
  display: block;
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
  width: 100%;
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
.mid-content p {
  text-align: center;
  padding: 10px;
  width: 100%;
}
.mid-content {
  margin-top: 10%;
  width: 100%;
  max-width: 100%;
}

.first {
  text-align: center;
  padding: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  background: #e5e5ea;
  margin: 60px auto 30px auto;
}
.icons-first {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  padding: 20px;
}
.second p {
  line-height: 35px;
  width: 100%;
  max-width: 500px;
  margin-left: 5%;
}
.fa-tablet-alt {
  color: #8c8c99;
  font-size: 50px;
  margin: 20px 20px;
}
.fa-window-restore {
  color: #8c8c99;
  font-size: 50px;
  margin: 20px 20px;
}

@media only screen and (max-width: 600px) {
  .top-content {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  .mid-content {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  .first {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  @media only screen and (max-width: 900px) {
    img {
      width: 100%;
    }
    .top-content {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }
    ul {
      position: relative;
      top: 0 !important;
    }
  }
}
</style>
