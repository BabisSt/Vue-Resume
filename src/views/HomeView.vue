<template>
  <div class="spacer home bg">
    <h1 class=" text-center">Babis Stevis</h1>
    <div class="row mb-5">
      <div class="col">
        <img class="rounded mx-auto d-block"
          src="https://scontent.fath3-3.fna.fbcdn.net/v/t1.6435-1/69766398_2370859342968015_3417714036744126464_n.jpg?stp=dst-jpg_s200x200&_nc_cat=110&ccb=1-7&_nc_sid=7206a8&_nc_ohc=tX2ElV6BS5oAX_CCAZf&_nc_ht=scontent.fath3-3.fna&oh=00_AT85YR2_8-aVoNwb7eNPEER8krGh8lpqqoKEbfarT-HZ5g&oe=6370FFD3" />
      </div>
      <div class="col">
        <h3 class=" text-center ">Computer Engineer <br><br> Web Developer <br><br> Game Developer </h3>
      </div>
      <div class="col-6">
        <p class="text-left">lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum
          has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of
          type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap
          into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release
          of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like
          Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
    </div>

    <div class="row text-center pt-5">
      <div class="col mx-5">
        <a href="mailto:mpamphsfe@gmail.com"><button class="button-64 col-11" role="button"><span class="text">Email Me</span></button></a>
      </div>
      <div class="col">
        <a href="https://www.linkedin.com/in/babis-stevis-ab7861203/" target="_blank"><button class="button-64 col-11" role="button"><span class="text">Linked In</span></button></a>


      </div>
      <div class="col">
        <a href="https://www.cineraporto.com/" target="_blank"><button class="button-64 col-11" role="button"><span class="text">My Site</span></button></a>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {

  }
}
</script>

<style scoped >
h1 {
  padding: 5vw;
  color: aliceblue;
}
p{
  color: aliceblue;
}

h3 {
  color: #2B9C96;
}

.bg {
  width: 100%;
  height: 100vh;
  background-size: 300% 300%;
  background-image: linear-gradient(-45deg,
      #67cec9 0%,
      #1f6d69 25%,
      #19485e 51%,
      #042A3B 75%,
      #000000 100%);

  animation: AnimateBG 30s ease infinite;
}

@keyframes AnimateBG {
  0% {
    background-position: 0% 50%
  }

  50% {
    background-position: 100% 50%
  }

  100% {
    background-position: 0% 50%
  }
}



/* CSS */
.button-64 {
  align-items: center;
  background-image: linear-gradient(144deg,rgb(32, 56, 66),#2B9C96);
  border: 0;
  border-radius: 8px;
  box-shadow: rgba(151, 65, 252, 0.2) 0 15px 30px -5px;
  box-sizing: border-box;
  color: #FFFFFF;
  display: flex;
  font-size: 20px;
  justify-content: center;
  line-height: 1em;
  max-width: 100%;
  min-width: 140px;
  padding: 3px;
  text-decoration: none;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  white-space: nowrap;
  cursor: pointer;
}

.button-64:active,
.button-64:hover {
  outline: 0;
}

.button-64 span {
  background-color:rgb(32, 56, 66);
  padding: 16px 24px;
  border-radius: 6px;
  width: 100%;
  height: 100%;
  transition: 300ms;
}

.button-64:hover span {
  background: none;
}

@media (min-width: 768px) {
  .button-64 {
    font-size: 24px;
    min-width: 196px;
  }
}
</style>