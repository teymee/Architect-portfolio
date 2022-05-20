<template >
  <div
    class="about"
    data-aos="fade-up"
        data-aos-duration="600"
  >
    <h2 class="title-decorative">
      <span class="title-decorative-letter">About</span>
    </h2>

    <div class="first">
      <h3>About Me</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab repudiandae
        accusamus quasi optio accusantium, magnam provident hic id eos beatae,
        fugiat quibusdam sit fuga aliquid rem corrupti voluptatibus ut iste non
        laborum deserunt deleniti. Ipsam exercitationem ex eius non esse?
      </p>
      <img src="../assets/pic.jpg" alt="" />
    </div>

    <div class="second">
      <div class="section">
        <div class="details">
          <h2>500</h2>
          <h3>PROJECTS</h3>
        </div>
        <div class="details">
          <h2>500</h2>
          <h3>PROJECTS</h3>
        </div>
      </div>

      <div class="section">
        <div class="details">
          <h2>230</h2>
          <h3>CONTRACTORS</h3>
        </div>
        <div class="details">
          <h2>50</h2>
          <h3>CLIENTS</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* element.style {
  visibility: visible;
  animation-delay: 0s;
}
.animated {
  animation-duration: 1s;
  animation-fill-mode: both;
  opacity: 1;
}

.title-decorative-2 {
  line-height: 1.3em;
  font-weight: 700;
  color: #efeff0;
  font-size: 200px;
  text-align: left;
  display: block;
} */

.title-decorative {
  padding-top: 50px;
}
h2,
.heading-2 {
  font-size: 80px;
}

.title-decorative-word {
  display: block;
  padding: 0.625em 0.625em 0.625em 2.2em;
}

.title-decorative-letter {
  position: absolute;
  left: 0.5em;
  top: -70px;
  font-size: 210px;
  line-height: 1;
  -webkit-text-stroke: 0.7px rgba(15, 15, 18, 0.2);
  color: transparent;
}
.title-decorative {
  position: relative;
  text-transform: uppercase;
}

.about {
  display: flex;
  margin: auto;
  margin-top: 10%;
  padding-bottom: 10%;
  width: 80%;
  justify-content: space-between;
  align-content: center;
}

.background-text {
  font-size: 100px;
  z-index: 1;
}

.first {
  width: 40%;
  margin-top: 3%;
  z-index: 100;
}

.first img {
  margin-top: 30px;
  width: 450px;
}
.first p {
  margin-top: 30px;
  font-size: 14px;
}

.first h3 {
  font-size: 55px;
  text-align: right;
}

.second {
  width: 40%;
  margin-top: 10%;
  display: flex;
  justify-content: space-between;
}

.second h2 {
  font-size: 80px;
  font-weight: 700;
  letter-spacing: 5px;
}

.second h3 {
  font-size: 20px;
  font-weight: 600;
  margin-top: -15px;
}

.details {
  padding-bottom: 70px;
}
</style> 