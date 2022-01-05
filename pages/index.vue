<template>
  <div>
    <AppHeader />
    <Lookingforhome />
    <Howitworks />
    <Booknow />
    <Featured />
    <Video />
    <Review />
    <Footerr />
  </div>
</template>

<script>
import AppHeader from "../components/AppHeader.vue";
import Lookingforhome from "../components/Lookingforhome.vue";
import Howitworks from "../components/Howitworks.vue";
import Booknow from "../components/Booknow.vue";
import Featured from "../components/Featured.vue";
import Video from "../components/Video.vue";
import Review from "../components/Review.vue";
import Footerr from "../components/Footerr.vue";
export default {
  components: {
    AppHeader,
    Lookingforhome,
    Howitworks,
    Booknow,
    Featured,
    Video,
    Review,
    Footerr,
  },
};
</script>

<style>
body {
  display: flex;
  width: 1440px;
  margin: 0 auto;
  border-radius: 30px;
  font-family: "Poppins";
  font-style: normal;
}
ul {
  list-style-type: none;
}
</style>
