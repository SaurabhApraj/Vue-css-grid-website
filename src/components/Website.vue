<template>
  <div class="container">
    <div class="div1">
      <Header />
    </div>
    <div class="div2">
      <Box />
    </div>
    <div class="div3">
      <Box />
    </div>
    <div class="div4">
      <Box />
    </div>
    <div class="div5">
      <Artical />
    </div>
    <div class="div6">
      <Main />
    </div>
    <div class="div7">
      <Footer />
    </div>
  </div>
</template>

<script>
import Header from "./Header";
import Box from "./Box";
import Artical from "./Artical";
import Main from "./Main";
import Footer from "./Footer";

export default {
  components: {
    Header,
    Box,
    Artical,
    Main,
    Footer
  }
};
</script>

<style scoped>
.container {
  width: 1300px;
  margin: 0 auto;
  height: auto;
  display: grid;
  grid-template-rows: 60px 100px auto 60px;
  grid-template-columns: repeat(3, 1fr) 270px;
  grid-gap: 7px;
}
.div1 {
  grid-column: 1/-1;
}
.div2,
.div3,
.div4 {
  border-radius: 5px;
}
.div5 {
  grid-row: 2/4;
  grid-column: 4/5;
}
.div6 {
  grid-column: 1/4;
}
.div7 {
  grid-column: 1/-1;
}
</style>
