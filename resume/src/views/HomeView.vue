<template>
  <div class="new-container">
    <h1 class="main-title">Jason Liao</h1>
    <!-- <h2>About Me</h2>
    <p></p> -->
    <SectionOne class="section1" />
    <SectionTwo />
  </div>
</template>

<script>
import SectionOne from "../components/SectionOne.vue";
import SectionTwo from "../components/SectionTwo.vue";

export default {
  name: "HomeView",
  components: {
    SectionOne,
    SectionTwo,
  },
};
</script>

<style>
.main-title {
  position: absolute;
  left: 40%;
  color: black;
}

.section1 {
  position: absolute;
  right: 0%;
}

/* .main-content {
  position: absolute;
  left: 50%;
  width: 50vw;
  align-content: center;
  align-items: center;
  align-self: center;
  justify-content: center;
  z-index: 1;
} */
</style>
