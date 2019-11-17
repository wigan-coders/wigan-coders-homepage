<template>
  <div class="contact">
    <div class="main-content">
      <h2 class="contact-h2">Get in touch!</h2>
      <p>Start your Coding Journey today!</p>
      <div class="contact-links">
        <h3 class="contact-h3">Find us on Social Media</h3>
        <div class="icons">
          <i class="fab fa-facebook"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-github"></i>
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
}

.contact-links {
  background: #e6e8e1;
  width: 100%;
  max-width: 500px;
  margin-top: 5%;
}
.contact-h2 {
  font-size: 40px;
}
.contact-h3 {
  font-size: 30px;
}

.fab {
  font-size: 50px;
  padding: 10px;
}

.fa-facebook {
  color: #4267b2;
}

.fa-twitter {
  color: #39a2f2;
}

.icons {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  margin-left: 30px;
}
.main-content p {
  padding: 0;
  margin: 0;
}
</style>
