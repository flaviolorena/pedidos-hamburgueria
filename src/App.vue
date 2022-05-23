<template>
  <div>
    <Navbar :logo="logo_src" :alt="alt_name" />
    <router-view />
    <Footer />
  </div>
</template>
<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
export default {
  components: { Navbar, Footer },
  data() {
    return {
      logo_src: "/img/logo.png",
      alt_name: "Make Your Burguer",
    };
  },
};
</script>
<style>
* {
  font-family: "Helvetica";
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.main-container {
  margin: 50px;
  min-height: 250px;
}
h1 {
  text-align: center;
  font-size: 42px;
  color: #222;
}
</style>
