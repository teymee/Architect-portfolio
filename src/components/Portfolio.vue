<template>
  <div class="portfolio">
    <div
      class="
        title-decorative-2
        wow
        slideInUp
        animated
      "
      data-aos="fade-up"
        data-aos-duration="650"
      
      style="visibility: visible; animation-delay: 0s"
    >
      PORTFOLIO
    </div>

    <div class="gallery">
      <div class="section">
        <div
          class="first pic"
          data-aos="fade-right"
          data-aos-easing="ease-in-sine"
          data-aos-duration="650"
          data-aos-anchor-placement="center-center"
        >
          <img src="../assets/banner.jpg" alt="" />
          <div class="side-note">
            <div class="container">
              <h3>Nice Archtecture work</h3>
            </div>
          </div>
        </div>

        <div
          class="second pic"
          data-aos="fade-left"
          data-aos-easing="ease-in-sine"
          data-aos-duration="650"
        >
          <img src="../assets/banner2.jpg" alt="" />
          <div class="side-note">
            <div class="container">
              <h3>Nice Archtecture work</h3>
            </div>
          </div>
        </div>
      </div>

      <div class="section">
        <div
          class="first pic"
          data-aos="fade-right"
          data-aos-easing="ease-in-sine"
          data-aos-duration="650"
        >
          <img src="../assets/banner3.jpg" alt="" />
          <div class="side-note">
            <div class="container">
              <h3>Nice Archtecture work</h3>
            </div>
          </div>
        </div>
        <div
          class="second pic"
          data-aos="fade-left"
          data-aos-easing="ease-in-sine"
          data-aos-duration="650"
        >
          <img src="../assets/banner4.jpg" alt="" />
          <div class="side-note">
            <div class="container">
              <h3>Nice Archtecture work</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "animate.css";
import AOS from "aos";
export default {
  mounted() {
    AOS.init();
  },
};
</script>

<style scoped>
.portfolio {
  width: 80%;
  margin: auto;
  padding-bottom: 10%;
}
.title-decorative-2 {
  line-height: 1.3em;
  font-size: 250px;
  text-align: left;
  font-weight: 650;
  color: rgba(234, 234, 247, 0.7);
  display: block;
}

.gallery {
  width: 100%;
  margin: auto 3%;
}
.section {
  display: flex;
  justify-content: space-around;
  margin-bottom: 250px;
  height: 500px;
}

.first,
.second {
  width: 45%;
  position: relative;
  object-fit: cover;
}

.second {
  margin-top: -100px;
}

.section img {
  /* display: inline-block; */
  width: 100%;
  height: 650px;
  object-fit: cover;
  filter: brightness(0.7);
  transition: 1s ease-in-out;
}
.section img:hover {
  filter: brightness(0.9);
}
.side-note {
  transition: 1s ease-in-out;
}
.pic:hover .side-note {
  height: 100px;
  width: 60%;
  margin-top: -100px;
  background-color: #dcdce4;
  display: block;
  transition: 1s ease-in-out;
}

.container {
  display: none;
  padding: 20px;
}
.pic:hover .container {
  display: block;
  padding: 20px;
}

.pic:hover .side-note h3 {
  font-size: 25px;
  font-weight: 600;
  font-style: italic;
}
</style>