<template>
  <div class="new-container">
    <SectionOne class="section1" />
    <SectionTwo />
    <SectionThree class="section3" />
  </div>
</template>

<script>
import SectionOne from "../components/SectionOne.vue";
import SectionTwo from "../components/SectionTwo.vue";
import SectionThree from "../components/SectionThree.vue";

export default {
  name: "HomeView",
  components: {
    SectionOne,
    SectionTwo,
    SectionThree,
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
  height: 98vh;
  display: flex;
}

.section3 {
  position: absolute;
  left: 25%;
  width: 50vw;
  height: 98vh;
}
</style>
