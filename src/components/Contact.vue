<template>
  <div class="general" data-aos="zoom-in" data-aos-duration="1000">
    <h2>CONTACT</h2>

    <div class="contact">
      <div class="text">
        <h3>Have a Question?</h3>
        <p>Just ask us,we're always</p>
        <p>happy to answer</p>
      </div>
      <div class="inner-form">
        <form action="">
          <div class="first">
            <div>
              <label for="name">Your Name</label>
              <input type="text" />
            </div>

            <div>
              <label for="name">Your Email</label>
              <input type="text" />
            </div>
          </div>

          <div>
            <label for="name">Your Message</label>
            <textarea name="" id="" cols="30" rows="10"></textarea>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    AOS.init();
  },
};
</script>

<style scoped>
.general {
  width: 100%;
  margin: auto auto;
  padding-bottom: 200px;
}

h2 {
  text-align: center;
  margin-bottom: 80px;
  font-size: 70px;
  font-weight: 600;
  letter-spacing: 10px;
}
.contact {
  width: 100%;
}

input,
textarea {
  border: none;
  border-bottom: 1.5px solid rgb(179, 168, 168);
  background: transparent;
  width: 90%;
  margin-bottom: 40px;
  outline: none;
  padding: 10px;
}

input {
  width: 260px;
  padding-top: 9px;
}

label {
  display: block;

  font-size: 13px;
}
.first {
  display: flex;
  width: 90%;
  justify-content: space-between;
}
.contact {
  width: 100%;
  position: relative;
}

.contact {
  display: flex;
  justify-content: space-between;
  align-content: center;
  align-items: center;
    color: #2C3E50;
}

form {
  width: 80%;
  margin: auto 30%;
}
.text h3 {
  font-size: 55px;
  margin-bottom: 10px;
  font-weight: 600;
}
.text {
  top: -20px;
  left: 10%;
  z-index: 1;
}
.text p {
  font-size: 13px;
  padding-bottom: 10px;
}
.inner-form {
  width: 70%;
  position: relative;
  background-color: rgba(249, 249, 249, 0.4);
  padding: 100px;
}

@media screen and (max-width: 420px) {
  .contact {
 display: block;
   overflow-x: hidden;
}
.inner-form {
  width: 100%;
}
form {
  width: 100%;
  margin: auto auto;
}
.first {
  display: block;
  width: 100%;
}
.text h3 {
  font-size: 30px;
 padding-top: 20px;
}

h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 50px;
  font-weight: 600;
  letter-spacing: 5px;
 
}


}
</style>