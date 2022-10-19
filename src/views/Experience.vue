<template>


<div class="hero">
  <h1 class="text-center" style="z-index:1">Past Experience</h1>
  <div class="header">
    <div class="row">
      <div class="col m-5 card ">
        <h4>Computer Engineer - Game Developer </h4>
        <h5>Softbiz</h5>
        <p>This was part of my internship.<br>
          In my time there I experimented with Web Developer and Game Engines
        </p>

        <p>About Web Developer: <br>
          My main project was a web-scraper implemented with <span class="important">Javascript</span>. I used <span
            class="important2">Node Js</span> and <span class="important2">Puppetter</span> </p>
        <p>About Game Developer: <br>
          I played around with <span class="important2">Unity</span> and <span class="important2">Unreal Engine
            4</span>. I got to know <span class="important">C#</span> as it is the main language of those engines.
        </p>
      </div>
      <div class="col m-5 card">
        <h4>Front-end Developer </h4>
        <h5>Raporto</h5>
        <p>Co-Founder of cinematography related site.</p>
        <p>This is a personal project with a friend. I am in charge of the technical stuff and the maintenance of
          the site. <br>
          I mostly play around with <span class="important">Html</span> <span class="important">Css</span> and <span
            class="important">Javascript</span>, refreshing things and adding components like carousels.</p>
      </div>
    </div>
  </div>
  <div class="cube"></div>
  <div class="cube"></div>
  <div class="cube"></div>
  <div class="cube"></div>
  <div class="cube"></div>
  <div class="cube"></div>
</div>


</template>

<style scoped>
p {
  color: aliceblue;
}
.card{
  align-items: center;
  padding: 15px;
  background-color: #042A3B;
  box-shadow: 0px 0px 25px rgba(0, 0, 0, 0.8);
  z-index: 1;
}
.important {
  color: #34eb3a
}

.important2 {
  color: #dfeb34
}

.experience {
  font-size: 110%;
}
.hero {
  background-color: #042A3B;
  position: relative;
  height: 100vh;
  overflow: hidden;
  font-family: "Montserrat", sans-serif;
}

.hero__title {
  color: #fff;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 50px;
  z-index: 1;
}

.cube {
  position: absolute;
  top: 80vh;
  left: 45vw;
  width: 10px;
  height: 10px;
  border: solid 1px #1f6d69;
  transform-origin: top left;
  transform: scale(0) rotate(0deg) translate(-50%, -50%);
  -webkit-animation: cube 12s ease-in forwards infinite;
          animation: cube 12s ease-in forwards infinite;
}
.cube:nth-child(2n) {
  border-color: #1f6d69;
}
.cube:nth-child(2) {
  -webkit-animation-delay: 2s;
          animation-delay: 2s;
  left: 25vw;
  top: 40vh;
}
.cube:nth-child(3) {
  -webkit-animation-delay: 4s;
          animation-delay: 4s;
  left: 75vw;
  top: 50vh;
}
.cube:nth-child(4) {
  -webkit-animation-delay: 6s;
          animation-delay: 6s;
  left: 90vw;
  top: 10vh;
}
.cube:nth-child(5) {
  -webkit-animation-delay: 8s;
          animation-delay: 8s;
  left: 10vw;
  top: 85vh;
}
.cube:nth-child(6) {
  -webkit-animation-delay: 10s;
          animation-delay: 10s;
  left: 50vw;
  top: 10vh;
}

@-webkit-keyframes cube {
  from {
    transform: scale(0) rotate(0deg) translate(-50%, -50%);
    opacity: 1;
  }
  to {
    transform: scale(20) rotate(960deg) translate(-50%, -50%);
    opacity: 0;
  }
}

@keyframes cube {
  from {
    transform: scale(0) rotate(0deg) translate(-50%, -50%);
    opacity: 1;
  }
  to {
    transform: scale(20) rotate(960deg) translate(-50%, -50%);
    opacity: 0;
  }
}

</style>