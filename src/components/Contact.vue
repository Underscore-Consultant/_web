<template>
  <div id="contact">
    <div class="parent">
      <div style="background: #333;">
        <br />
        <br />
        <br />
        <br />
        <div>
          <span>underscore.consultant@gmail.com</span>
          <br />
          <span>08142558011 | 08085816733</span>
          <br />
          <span>561, Sabo-Yaba, Alagomeji, Lagos</span>
        </div>
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <div class="social">
          <span>
            <a href>
              <img src="../assets/svg/facebooks.svg" alt height="50" width="50" />
            </a>
            <a href>
              <img src="../assets/svg/instagram.svg" alt height="50" width="50" />
            </a>
            <a href>
              <img src="../assets/svg/twitter.svg" alt height="50" width="50" />
            </a>
            <a href>
              <img src="../assets/svg/github.svg" alt height="50" width="50" />
            </a>
          </span>
        </div>
      </div>
      <div style="background: #0047ab">
        <h1>Contact Us</h1>
        <br />
        <label for="text">Name</label>
        <input type="text" />
        <br />
        <label for="email">Email</label>
        <input type="email" />
        <br />
        <label for="text">Message</label>
        <textarea name="Message" id cols="30" rows="10"></textarea>
        <br />
        <button type="submit">Send</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Contact",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Open+Sans&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300&display=swap");
.parent {
  display: grid;
  grid-template-columns: minmax(150px, 25%) 1fr;
  height: 100vh;
  scroll-snap-align: start;
}

.parent div {
  display: flex;
  flex-direction: column;
  padding: 20px;
}

h1,
label {
  color: floralwhite;
  font-family: "Ubuntu", sans-serif;
}

span {
  font-family: "Source Sans Pro", sans-serif;
  color: floralwhite;
}

label {
  font-size: 24px;
}

input,
textarea {
  border-style: none;
  padding: 15px;
  outline: none;
  width: 50%;
  transition: 0.9s;
  color: #666;
  font-family: "Source Sans Pro", sans-serif;
}

input:focus,
textarea:focus {
  border-style: none;
  padding: 15px;
  outline: none;
  border-radius: 30px;
  background: #55b9f3;
  box-shadow: inset 20px 20px 60px #489dcf, inset -20px -20px 60px #62d5ff;
  width: 50%;
  transition: 0.9s;
  color: floralwhite;
  font-family: "Source Sans Pro", sans-serif;
}
button {
  border-style: none;
  background: floralwhite;
  color: #0066f5;
  padding: 10px;
  width: 10%;
  font-weight: 900;
  transition: 0.9s;
  outline: none;
}
button:hover {
  background: #add8e6;
  color: floralwhite;
  border-radius: 50px;
  transition: 0.9s;
}

img {
  padding: 10px;
}
</style>