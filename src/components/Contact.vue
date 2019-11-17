<template>
  <div class="contact">
    <div class="main-content">
      <h2 class="contact-h2">Get in touch!</h2>
      <p>Start your Coding Journey today!</p>
      <div class="contact-links">
        <h3 class="contact-h3">Find us on Social Media</h3>
        <div class="icons">
          <a href="https://www.facebook.com/rybrockley/" target="blank">
            <i class="fab fa-facebook"></i>
          </a>
          <a href="https://twitter.com/WiganCoders/" target="blank">
            <i class="fab fa-twitter"></i>
          </a>
          <a href="https://github.com/wigan-coders/" target="blank">
            <i class="fab fa-github"></i>
          </a>
        </div>
      </div>
    </div>
    <div class="mid-content">
      <h2 class="email-h2">Not on Social Media</h2>
      <p>Send us an email or give us a call</p>

      <div class="contact-links">
        <h3 class="contact-h3">Email or telephone</h3>
        <div class="icons-2">
          <a href="#" target="blank">
            <i class="fas fa-phone"></i>
            <span class="phone-span">07539294710</span>
          </a>
          <a href="mailto:wigan.coders@gmail.com" target="blank">
            <i class="far fa-envelope"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
  data() {
    return {};
  }
};
</script>

<style>
nav {
  height: 100px;
}
.contact {
  font-family: "Poppins", sans-serif;
  text-align: center;
}
.main-content {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 4%;
}
.main-content p {
  padding: 0;
  margin: 0;
}
.mid-content p {
  padding: 0 auto;
  margin: 0 auto;
}
.mid-content {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 4%;
}
.contact-links {
  background: #e6e8e1;
  width: 100%;
  max-width: 600px;
  margin-top: 5%;
  -webkit-box-shadow: 3px 4px 5px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 3px 4px 5px 0px rgba(0, 0, 0, 0.75);
  box-shadow: 3px 4px 5px 0px rgba(0, 0, 0, 0.75);
  padding: 5px;
  margin-bottom: 15%;
}

.contact-h2 {
  font-size: 40px;
  padding: 0 auto;
  margin: 0 auto;
}
.email-h2 {
  font-size: 40px;
  padding: 0 auto;
  margin: 0 auto;
}
.contact-h3 {
  font-size: 30px;
}

.fab {
  font-size: 50px;
  padding: 10px;
}
.fas {
  font-size: 50px;
  padding: 10px;
}
.far {
  font-size: 50px;
  padding: 10px;
}

.fa-facebook {
  color: #4267b2;
}

.fa-twitter {
  color: #39a2f2;
}
.fa-github {
  color: #000000;
}
.fa-phone {
  color: #000000;
}
.fa-envelope {
  color: #3b3b3b;
}

.icons {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
}
.icons-2 {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: column;
  color: #000000;
}
.icons-2 .phone-span {
  color: #000000;
}
</style>
