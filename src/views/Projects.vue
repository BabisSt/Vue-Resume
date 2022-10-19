<template>
  <div class="bg"></div>
  <div class="bg bg2"></div>
  <div class="bg bg3"></div>
  <h1 class=" text-center">My Projects</h1>
  <div class="mydiv">
    <a href="https://github.com/BabisSt" target="_blank"><button class="button-64 " role="button"><span class="text">My Github page here</span></button></a>
  </div>

  <h3 style="padding-left:50px">Some of my Projects:</h3>

  <div class="row">
    <div class="col-4 card mx-5">
      <a href="https://github.com/meryfanou/EAM" target="_blank"><h4>Ministry of Labour Site.
  </h4></a>
      <p>Javascript Php Html Css</p>
    </div>
    <div class="col-6 card">
  <p>Group project about the fundamentals of accessibility and easy usage of sites. Had to create from ground up the Ministry of Labour site.
  I was in charge of Html , Css and Javascript but I experimented with Php too.
  </p>
    </div>
  </div>

  <div class="row">
    <div class="col-4 card mx-5">
      <a href="https://github.com/BabisSt/LSTM-Neural-Network-and-Notes-on-LSH-HyperCube-Frechet" target="_blank"><h4>LSTM Neural Network and LSH,HyperCube,Frechet.
</h4></a>
      <p>Python - Keras</p>
    </div>
    <div class="col-6 card">
<p>Experimented with epochs batches and loss functions.
Trained and tested the network changing the layers each time.
Implemented an autoencoder for another LSTM network.
Used the networks for previous implemented algorithms such as LSH,HyperCube,Discrete and Continuous Frechet and took notes for their validity.</p>
    </div>
  </div>


  <div class="row">
    <div class="col-4 card mx-5">
      <a href="" target="_blank"><h4>Multi-Threaded Server and Client (System Programming).
</h4></a>
      <p>C</p>
    </div>
    <div class="col-6 card">
<p>The server is multithreaded with pool where they enter queue. We open the threads which can read if the connection is from a worker or client, and when they do not accept requests they add the data to the queue. The thread function can print the statistics it has received and accept the ip, ports and the number of workers. It can also accept queries from the client and print them.
</p>
    </div>
  </div>


</template>

<script>


export default {
  name: 'Projects',
  components: {

  }
}
</script>

<style scoped >
p{
  color:aliceblue
}
.card{
  align-items: center;
  padding: 15px;
  background-color: #042A3B;
  box-shadow: 0px 0px 25px rgba(0, 0, 0, 0.8);
  z-index: 1;
  margin: 10px;
}


.mydiv{
  display: flex;
  justify-content: center;
  margin-top: -50px;
}
h3 {
  color: aliceblue;
}

.bg {
  animation: slide 10s ease-in-out infinite alternate;
  background-image: linear-gradient(-20deg, #042A3B 50%, #2B9C96 50%);
  bottom: 0;
  left: -100%;
  opacity: .5;
  position: fixed;
  right: -50%;
  top: 0;
  z-index: -1;
}

.bg2 {
  animation-direction: alternate-reverse;
  animation-duration: 40s;
}

.bg3 {
  animation-duration: 60s;
}


@keyframes slide {
  0% {
    transform: translateX(-25%);
  }

  100% {
    transform: translateX(25%);
  }
}


/* CSS */
.button-64 {
  align-items: center;
  background-image: linear-gradient(144deg, rgb(32, 56, 66), #2B9C96);
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
  background-color: rgb(32, 56, 66);
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