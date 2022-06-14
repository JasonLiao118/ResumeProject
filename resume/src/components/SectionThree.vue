<template>
  <div>
    <h1>Jason Liao</h1>
    <h2>Education</h2>
    <img class="img" src="https://siths.edlioadmin.com/pics/STAITHS_LOGO.gif" />
    <h3>Staten Island Technical High School</h3>
    <h4>Expected Class of 2023</h4>
    <h5>GPA: 4.0</h5>

    <div>
      <ul class="bottom-section">
        <li class="bottom-list">AutoCAD Certified</li>
        <li class="bottom-list">Conversational Mandarin and Cantonese</li>
        <li class="bottom-list">Conversational Russian</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionThree",
};
</script>

<style>
.bottom-section {
  margin-top: 10rem;
  display: inline-block;
  color: white;
}

.bottom-list {
  font-size: var(--h4);
  text-align: left;
  color: white;
}

.img {
  width: 30rem;
  background-color: white;
  border-radius: 5rem;
}
</style>
