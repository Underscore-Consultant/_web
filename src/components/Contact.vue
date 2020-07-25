<template>
  <div>
    <div class="parent">
      <div style="">
          <br><br><br><br>
          <span>underscore.consultant@gmail.com</span>
          <br>
          <span>08142558011 | 08085816733</span>
          <br>
          <span>561, Sabo-Yaba, Alagomeji, Lagos</span>
      </div>
      <div style="background: #0066f5">
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
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
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
    font-family: 'Open Sans', sans-serif;
    color: #0066f5;
}

label {
  font-size: 24px;
}

input,
textarea {
  border-style: none;
  padding: 15px;
  outline: none;
  /* box-shadow: 12px 12px 16px 0 #ffffff,
         -8px -8px 12px 0 #00ffff; */
  /* background: transparent; */
  width: 50%;
  transition: 0.9s;
}
button {
  border-style: none;
  background: floralwhite;
  color: #0066f5;
  padding: 10px;
  width: 10%;
  font-weight: 900;
  transition: 0.9s;
}
button:hover {
  background: #add8e6;
  color: floralwhite;
  transition: 0.9s;
}
</style>