<template>
  <div class="service">
    <div class="wrapper">
      <div style="background: #ADD8E6">
        <h1>
          Strategize.
          <br />Implement.
          <br />Deliver.
        </h1>
      </div>
      <div>
        <img src="../assets/gifs/world.gif" alt />
      </div>
      <div style="background: #0E86D4">
        <h1>
          Teamwork.
          <br />Client Driven.
          <br />Reliable.
        </h1>
      </div>
    </div>
    <div class="expert" id="service">
      <br />
      <br />
      <h1>Our Services</h1>
      <br />
      <br />
      <br />
      <div>
        <div>
          <img src="../assets/svg/webdev.svg" alt height="200" width="100" />
          <h2>Web Development</h2>
          <hr style="border-top: 1px dotted #0066f5; width: 100%; border-bottom-style: none;" />
          <p>We are passionate about transferring your wildest ideas to scaled, efficient and well-performed web platforms successfully functioning in Digital World. With our experience in UI/UX, development, we prototype, build, deliver effortlessly</p>
        </div>
        <div>
          <img src="../assets/svg/mobile.svg" alt height="200" width="100" />
          <h2>Mobile Development</h2>
          <hr style="border-top: 1px dotted #0066f5; width: 100%; border-bottom-style: none;" />
          <p>We are eager to bring live communication, fast access to information and high level of delight to demanding modern customers. Whether it is your first app or fourth one, our expertise in mobile app development will help you succeed with your mobile strategy.</p>
        </div>
        <div>
          <img src="../assets/svg/devops.svg" alt height="200" width="100" />
          <h2>Devops</h2>
          <hr style="border-top: 1px dotted #0066f5; width: 100%; border-bottom-style: none;" />
          <p>
            Infrastructure is very important to maintain reliable operation. At
            <strong>Underscore</strong>, we use our expertise in cloud and server solutions to derive and build high-performing environments that will satisfy any complexity requirements for customer's product.
          </p>
        </div>
        <div>
          <img src="../assets/svg/ui.svg" alt height="200" width="100" />
          <h2>UI/UX Design</h2>
          <hr style="border-top: 1px dotted #0066f5; width: 100%; border-bottom-style: none;" />
          <p>We create user-friendly and development-ready designs of software systems such as web and mobile application mock ups that delight users. A great design is a cost-effective investment and it substantially reduces risks of mistakes and overpays.</p>
        </div>
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
@import url("https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap");
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

.wrapper h1 {
  font-family: "Ubuntu", sans-serif;
  font-weight: 700;
  padding: 22px;
  font-size: 68px;
  color: white;
}

.expert {
  height: 100vh;
  scroll-snap-align: start;
  /* line-height: 100%; */
  /* background: url("../assets/gifs/ring.gif"); */
  background-repeat: no-repeat;
  background-position: bottom;
  /* background-size: 700px; */
}

.expert h1 {
  font-family: "Ubuntu", sans-serif;
  font-weight: 700;
  text-align: center;
  color: #0066f5;
}

.expert h2 {
  font-family: "Ubuntu", sans-serif;
  font-weight: 700;
  font-size: 20px;
  color: #0066f5;
}

.expert div {
  display: flex;
  flex-direction: row;
  padding: 10px;
  justify-content: center;
  flex-wrap: wrap;
}

.expert div div {
  flex: 1 1 150px;
  /* height: 70vh; */
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 12px;
  margin-right: 2em;
  flex-wrap: wrap;
  /* border: 1px dotted #0066f5; */
  transition: 0.9s;
  cursor: pointer;
}

.expert div div:hover {
  box-shadow: 0px 13px 14px #add8e6;
  transition: 0.9s;
  border-radius: 12px;
}
</style>