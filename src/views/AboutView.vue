<template>

  <div class="header">


<!--
    <h1 class=" text-center">About me</h1>
    <div class="row">
      <div class="col-lg">
        <img class="rounded mx-auto d-block"
          src="https://scontent.fath3-3.fna.fbcdn.net/v/t1.6435-1/69766398_2370859342968015_3417714036744126464_n.jpg?stp=dst-jpg_s200x200&_nc_cat=110&ccb=1-7&_nc_sid=7206a8&_nc_ohc=tX2ElV6BS5oAX_CCAZf&_nc_ht=scontent.fath3-3.fna&oh=00_AT85YR2_8-aVoNwb7eNPEER8krGh8lpqqoKEbfarT-HZ5g&oe=6370FFD3" />
      </div>
      <div class="col-lg">
        <p class="mx-5 text-left">lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum
          has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of
          type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap
          into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release
          of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like
          Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
    </div> -->
    <br><br><br><br><br><br><br><br>


    <div>
      <svg class="waves" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
        viewBox="0 24 150 28" preserveAspectRatio="none" shape-rendering="auto">
        <defs>
          <path id="gentle-wave" d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z" />
        </defs>
        <g class="parallax">
          <use xlink:href="#gentle-wave" x="48" y="0" fill="rgba(43, 156, 150,0.7" />
          <use xlink:href="#gentle-wave" x="48" y="3" fill="rgba(4, 42, 59,0.5)" />
          <use xlink:href="#gentle-wave" x="48" y="5" fill="rgba(43, 156, 150,0.3)" />
          <use xlink:href="#gentle-wave" x="48" y="7" fill="rgba(4, 42, 59,1)" />
        </g>
      </svg>
    </div>
  </div>



</template>

<style scoped>
p {
  color: aliceblue;
}



.header {
  position: relative;
  text-align: center;
  background: linear-gradient(60deg, rgba(43, 156, 150, 1) 0%, rgba(4, 42, 59, 1) 100%);
  color: white;
}

.logo {
  width: 50px;
  fill: white;
  padding-right: 15px;
  display: inline-block;
  vertical-align: middle;
}

.inner-header {
  height: 65vh;
  width: 100%;
  margin: 0;
  padding: 0;
}

.flex {
  /*Flexbox for containers*/
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.waves {
  position: relative;
  width: 100%;
  height: 15vh;
  margin-bottom: -7px;
  /*Fix for safari gap*/
  min-height: 100px;
  max-height: 150px;
}

.content {
  position: relative;
  height: 20vh;
  text-align: center;
  background-color: white;
}

/* Animation */

.parallax>use {
  animation: move-forever 25s cubic-bezier(.55, .5, .45, .5) infinite;
}

.parallax>use:nth-child(1) {
  animation-delay: -2s;
  animation-duration: 7s;
}

.parallax>use:nth-child(2) {
  animation-delay: -3s;
  animation-duration: 10s;
}

.parallax>use:nth-child(3) {
  animation-delay: -4s;
  animation-duration: 13s;
}

.parallax>use:nth-child(4) {
  animation-delay: -5s;
  animation-duration: 20s;
}

@keyframes move-forever {
  0% {
    transform: translate3d(-90px, 0, 0);
  }

  100% {
    transform: translate3d(85px, 0, 0);
  }
}

/*Shrinking for mobile*/
@media (max-width: 768px) {
  .waves {
    height: 40px;
    min-height: 40px;
  }

  .content {
    height: 30vh;
  }

  h1 {
    font-size: 24px;
  }
}
</style>