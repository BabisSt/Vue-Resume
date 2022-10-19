<template class="bg-dark">
  <!-- Google font-->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet" />

  <Header />
  <router-view />
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>



<style>
@import'~bootstrap/dist/css/bootstrap.css';

h1 {
  padding: 5vw;
  color: aliceblue;
}

h3,
h4,
h5,
h6 {
  color: #2B9C96;
}

body {
  overflow: hidden;
  font-family: "Prompt", sans-serif;
}

.spacer {
  aspect-ratio: 900/560;
  width: 100%;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.spacer2 {
  aspect-ratio: 900/500;
  width: 100%;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.home {
  background-image: url("./assets/stacked-waves-haikei.svg");
}

.about {
  background-image: url("./assets/layered-waves-haikei.svg");
}

.experience {
  background-image: url("./assets/layered-steps-haikei.svg");
}

.skills {
  background-image: url("./assets/blob-scene-haikei.svg");
}
</style>
