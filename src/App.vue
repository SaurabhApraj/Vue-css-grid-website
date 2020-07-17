<template>
  <div>
    <Website />
  </div>
</template>

<script>
import Website from "./components/Website.vue";

export default {
  name: "App",
  components: {
    Website
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap");
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  font-family: "Josefin Sans", sans-serif;
}
</style>
