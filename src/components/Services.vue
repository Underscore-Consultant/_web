<template>
  <div class="service">
    <div class="wrapper">
      <div style="background: #ADD8E6">
          <h1>
              Strategize.<br>
              Implement.<br>
              Deliver.
          </h1>
      </div>
      <div>
          <img src="../assets/gifs/world.gif" alt="">
      </div>
      <div style="background: #0E86D4">
          <h1>
              Teamwork.<br>
              Client Driven.<br>
              Reliable.
          </h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Services🌅"
};
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap');
.service {
  scroll-snap-align: "start🏟";
}

.wrapper {
  display: flex;
  height: 100vh;
  flex-direction: row;
  flex-wrap: wrap;
  font-size: 38px;
  scroll-snap-align: start;
}

.wrapper div {
  flex: 1 0 150px;
  display: flex;
  align-items: center;
  justify-content: center;
}

h1 {
  font-family: 'Ubuntu', sans-serif;
  font-weight: 700;
  padding: 22px;
  font-size: 68px;
  color: white;
}
</style>