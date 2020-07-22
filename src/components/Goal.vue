<template>
  <div>
    <div class="wrapper">
      <div>
        <img src="../assets/gifs/stress.gif" alt="" class="img-responsive">
      </div>
      <div style="background: #0066f5">
        <h1>
          We are here
          <br />to relieve you
          <br />from startup
          <br />STRESS!
        </h1>
      </div>
    </div>
    <div class="wrapper">
      <div style="background: #0066f5">
        <h1>
          Using
          <br />top grade technologies,
          <br />we guarantee the
          <br />best!
        </h1>
      </div>
      <div>
        <img src="../assets/gifs/create.gif" alt="" class="img-responsive">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Goal⛅"
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300;500&display=swap");
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap');
.wrapper {
  height: 100vh;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  font-size: 38px;
  scroll-snap-align: start;
}

.wrapper div {
  flex: 1 1 150px;
  display: flex;
  align-items: center;
  justify-content: center;
}

h1 {
  font-family: 'Ubuntu', sans-serif;
  font-weight: 700;
  padding: 42px;
  font-size: 68px;
  color: white;
}
</style>