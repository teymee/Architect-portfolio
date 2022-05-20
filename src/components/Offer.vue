<template>
  <div
    class="offer"
    data-aos="fade-up"
    data-aos-duration="600"
  >
    <div class="header">
      <span class="line"></span>
      <h3>WHAT I OFFER</h3>
    </div>

    <div class="offer-list">
      <div class="item">
        <div class="icon">icon</div>
        <div>
          <h4>All of our estimate</h4>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Architecto, magni!
          </p>
        </div>
      </div>
      <div class="item">
        <div class="icon">icon</div>
        <div>
          <h4>All of our estimate</h4>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Architecto, magni!
          </p>
        </div>
      </div>
      <div class="item">
        <div class="icon">icon</div>
        <div>
          <h4>All of our estimate</h4>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Architecto, magni!
          </p>
        </div>
      </div>
      <div class="item">
        <div class="icon">icon</div>
        <div>
          <h4>All of our estimate</h4>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Architecto, magni!
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.offer {
  width: 90%;
  margin: auto;
  margin-top: 10%;
  margin-bottom: 10%;
}
.offer span {
  width: 30%;
  background: #2c3e50;
  height: 2px;
  display: inline-block;
  /* margin-bottom: 7px; */
  margin-right: 20px;
}

.header {
  display: flex;
  width: 30%;
  margin: auto auto;
  align-content: center;
  align-items: center;
  margin-top: 10%;
  margin-bottom: 3%;
}

.header h3 {
  font-size: 30px;
  text-transform: capitalize;
}
.offer-list {
  width: 100%;
  margin: auto;
  display: flex;
  justify-content: space-around;
}
.item {
  width: 20%;
  margin-top: 30px;
  display: flex;
}

.item h4 {
  font-size: 17px;
  font-weight: 600;
  padding-bottom: 10px;
}
.item p {
  font-size: 13px;
  font-weight: lighter;
}

.icon {
  margin-right: 20px;
}
</style>