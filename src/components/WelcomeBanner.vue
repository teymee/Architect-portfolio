<template>
  <div class="banner">
    <div class="overlay">
      <nav>
        <div class="logo">LOGO</div>
        <ul>
          <li>About</li>
          <li>Portfolio</li>
          <li>Contact</li>
        </ul>
      </nav>

      <div class="content">
        <div class="text">
          <h4>Hello</h4>
          <h1>I'M IKAY</h1>
        </div>
        <div class="side-rule"></div>
      </div>

      <div class="bottom-bar">
        <div class="subtext">An Architect who loves building and designs</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
nav {
  width: 90%;
  margin: auto auto;
  display: flex;
  padding-top: 30px;
  justify-content: space-between;
  color: rgb(219, 219, 233);
  align-content: center;
  animation: nav 1.5s forwards;
  animation-delay: 1s;
  position: relative;
  top: -100px;
}

@keyframes nav {
  from {
    display: none;
    top: -100px;
  }

  to {
    display: block;
    top: 0px;
  }
}

.logo {
  font-size: 25px;
  font-weight: 500;
}

nav ul {
  display: flex;
  align-content: center;
}

nav li {
  padding-top: 15px;
  padding-left: 50px;
  font-size: 14px;
}

.overlay {
  height: 100vh;
  background-color: rgba(0, 0, 0, 0.4);
  animation: overlay 5s;
}

@keyframes overlay {
  from {
    /* display: none; */
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}

.banner {
  position: relative;
  background-image: url("../assets/banner3.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 10% 80%;
  height: 100vh;
  animation: banner 1s;
}

@keyframes banner {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

.side-rule {
  border-left: 2px solid rgba(219, 219, 233, 0.5);
  height: 400px;
  position: absolute;
  opacity: 0;
  top: 110px;
  margin-left: -3px;
  animation: rule 4s forwards;
  animation-delay: 2s;
}

@keyframes rule {
  0% {
    left: 0px;
    opacity: 1;
  }

  100% {
    left: 1350px;
    opacity: 1;
  }
}

.content {
  width: 90%;
  margin: auto auto;
}

.text {
  color: rgb(229, 229, 238);
  text-align: left;
  line-height: 80px;
  position: absolute;
  top: 120px;
  animation: text 3.5s;
  animation-delay: 2780ms;
  animation-fill-mode: forwards;
  opacity: 0;
}

@keyframes text {
  0% {
    left: -150px;
  }

  100% {
    left: 8px;
    opacity: 1;
  }
}

.text h4 {
  font-size: 30px;
  padding-left: 10px;
  font-style: italic;
}

.text h1 {
  font-size: 140px;
  font-weight: 700;
}

.socials {
  margin: auto;
}

.bottom-bar {
  display: flex;
  justify-content: space-around;
  align-content: center;
  position: absolute;
  bottom: 0;
  left: 0;
  background-color: rgb(204, 204, 219);
  height: 130px;
  width: 50%;
  animation: bar 2s forwards;
  animation-delay: 5s;
  bottom: -200px;
  opacity: 0;
}

@keyframes bar {
  from {
    bottom: -200px;
  }

  to {
    bottom: 0;
    opacity: 1;
  }
}

.subtext {
  font-size: 30px;
  word-spacing: 10px;
  font-style: italic;
  text-align: center;
  width: 100%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: none;
}

@media screen and (max-width: 420px) {
  .text h1 {
    font-size: 70px;
    font-weight: 700;
  }

  .text {
    position: absolute;
    line-height: 50px;
    top: 200px;
    animation: text 3s;
    animation-delay: 2780ms;
    animation-fill-mode: forwards;
    opacity: 0;
  }

  .side-rule {
    border-left: 2px solid rgba(219, 219, 233, 0.7);
    height: 300px;
    position: absolute;
    opacity: 0;
    top: 130px;
    margin-left: -3px;
    animation: rule 3.5s forwards;
    animation-delay: 2s;
  }

  @keyframes rule {
    0% {
      left: 0px;
      opacity: 1;
    }

    100% {
      left: 95%;
      opacity: 1;
    }
  }

  .banner, .overlay{
    height: 90vh;
    overflow-x: hidden;
  }

  .bottom-bar {
  display: flex;
  justify-content: space-around;
  align-content: center;
  position: absolute;
  bottom: 0;
  left: 0;
  background-color: rgb(204, 204, 219);
  height: 80px;
  width: 80%;
  animation: bar 2s forwards;
  animation-delay: 5s;
  bottom: -200px;
  opacity: 0;
}
}
</style>
