<template>
  <div class="about">
    <div class="about-content">
       <div class="jumbo">
        <p class="jumbo-p">Welcome to Wigan Coders. Let us help you on your coding journey today!</p>
      </div>
    </div>
    <div class="about-content">
      <div class="image">
        <img src="" alt="">
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
  name: 'About',

  methods: {
    changeUsp() {
      const changed = document.querySelector("p");
      console.log(changed.innerHTML);
      console.log('hello');
      }
    },


  data () {
    return {
    }
  }
}
</script>

<style>
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
.about-content {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 4%;
}
.about-content p {
  padding: 0;
  margin: 0;
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

</style>
