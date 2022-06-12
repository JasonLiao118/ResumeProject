<template>
  <div class="main-section">
    <h1 class="sub-title">Experience/ Activities</h1>
    <div class="section-item">
      <h2 class="secondary-title">MSIT Handball</h2>
      <ul>
        <li class="list-item">
          Led the team through practice drills, researched training techniques,
          and promoted games
        </li>
        <li class="list-item">Assisted as a referee in PSAL matches</li>
        <li class="list-item">
          Collaborated with peers to ascend through finals matches.
        </li>
        <li class="list-item">Benefitted the team by recruiting new members</li>
      </ul>
      <p class="list-item">September 2019-Present</p>
    </div>
    <div class="section-item">
      <h2 class="secondary-title">Rite Aid Pharmacy</h2>
      <ul>
        <li class="list-item">Aid in restocking and organizing merchandise.</li>
        <li class="list-item">Customer assistance and guidance</li>
      </ul>
      <p class="list-item">June 2019-August 2019</p>
    </div>
    <div class="section-item">
      <h2 class="secondary-title">Youthbuild Impact</h2>
      <ul>
        <li class="list-item">
          Engaging young students to fight for environmental justice and to
          construct a suitable environment in nature.
        </li>
      </ul>
      <p class="list-item">November 2019-Present</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionTwo",
};
</script>

<style>
.main-section {
  flex-wrap: wrap;
  display: block;
  width: 25vw;
  justify-content: center;
  align-content: center;
  align-items: center;
  position: relative;
  overflow-y: scroll;
  height: 94vh;
}

.section-item :hover {
  transform: scale(1.1);
}

.section-item {
  width: 80%;
  max-height: 60rem;
  background-color: rgb(255, 255, 255);
  text-align: center;
  margin-top: 8rem;
  border-radius: 5rem;
  margin-left: 5rem;
}

.list-item {
  font-size: var(--h4);
  margin-left: 3rem;
  margin-right: 3rem;
  margin-top: 2rem;
  margin-bottom: 3rem;
}

.sub-title {
  font-size: 8rem;
  color: black;
  position: relative;
  width: 25vw;
}

.secondary-title {
  margin: 3rem auto;
}
</style>
