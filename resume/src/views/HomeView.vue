<template>
  <div class="new-container">
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
  color: black;
}

.section1 {
  position: absolute;
  right: 0%;
}

.new-container {
  display: flex;
  height: 98vh;
}
</style>
