<template>
  <body>
    <Header />
    <Main />
    <Footer />
  </body>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Header,
    Main,
    Footer,
  },
}
</script>

<style lang="scss">
@use "./style/general.scss";
@use "bootstrap";

body {
  background-color: #F6F6F6;
}

ul {
  padding: 0;
  margin: 0;
  list-style: none;
}
</style>
