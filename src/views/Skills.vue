<template>
	<!-- <div class="skills spacer2">
	  <h1 class="text-center">My Skillset</h1>

		<div class="mx-4 row d-flex justify-content-between text-center">
			<div class="col">
				<h4>Game Developer </h4>
				<h5>Platforms</h5>
				<ul>
					<li>Unity</li>
					<li>Uneral Engine</li>
					<li>Godot</li>
					<li>Blender</li>
					<li>Aseprite</li>
				</ul>
			</div>
			<div class="col ">
				<h3 class="text-center">Engineering</h3>
				<div class="row">
					<div class="col">
						<h5 class="text-center" >Programming <br> Languages</h5>
						<ul class="text-center">
							<li>Javacript</li>
							<li>Html</li>
							<li>Css</li>
							<li>C</li>
							<li>C++</li>
							<li>C#</li>
							<li>Python</li>
							<li>SQL</li>
							<li>Java</li>
							<li>Assemply</li>
						</ul>
					</div>
					<div class="col">
						<h5 class="text-center">Other <br> Skills</h5>
						<ul class="text-center">
							<li>Linux</li>
							<li>WIndows</li>
							<li>Git</li>
							<li>Github</li>
							<li>Jupiter Notebook</li>
							<li>Visual Studio Code</li>
						</ul>
					</div>
				</div>
			</div>
			<div class="col">
				<h4>Languages</h4>
				<ul>
					<li>Greek - Native</li>
					<li>English - Fluent</li>
					<li>Spanish - Beginner</li>
				</ul>
			</div>
		</div>


	</div> -->


	<div class="area">
		<ul class="circles">

			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
		</ul>
		<h1 class="text-center">My Skillset</h1>
		<div class="mx-4 row d-flex justify-content-between text-center">
			<div class="col-2 card">
				<h4>Game Developer </h4>
				<h5>Platforms</h5>
				<ul>
					<li>Unity</li>
					<li>Uneral Engine</li>
					<li>Godot</li>
					<li>Blender</li>
					<li>Aseprite</li>
				</ul>
			</div>
			<div class="col-5 card">
				<h3 class="text-center">Engineering</h3>
				<div class="row">
					<div class="col">
						<h5 class="text-center">Programming <br> Languages</h5>
						<ul class="text-center">
							<li>Javacript</li>
							<li>Html</li>
							<li>Css</li>
							<li>C</li>
							<li>C++</li>
							<li>C#</li>
							<li>Python</li>
							<li>SQL</li>
							<li>Java</li>
							<li>Assemply</li>
						</ul>
					</div>
					<div class="col">
						<h5 class="text-center">Other <br> Skills</h5>
						<ul class="text-center">
							<li>Linux</li>
							<li>WIndows</li>
							<li>Git</li>
							<li>Github</li>
							<li>Jupiter Notebook</li>
							<li>Visual Studio Code</li>
						</ul>
					</div>
				</div>
			</div>
			<div class="col-2 card">
				<h4>Languages</h4>
				<ul>
					<li>Greek - Native</li>
					<li>English - Fluent</li>
					<li>Spanish - Beginner</li>
				</ul>
			</div>
		</div>

	</div>
</template>

<style scoped>
p {
	color: aliceblue;
}

ul {
	color: aliceblue;
}

.important {
	color: #34eb3a
}

.important2 {
	color: #dfeb34
}

.skills {
	font-size: 110%;
}
.card{
  align-items: center;
  padding: 15px;
  background-color: #042A3B;
  box-shadow: 0px 0px 25px rgba(0, 0, 0, 0.8);
  z-index: 1;
  margin: 10px;
}


.context {
	width: 100%;
	position: absolute;
	top: 50vh;

}

.area {
	background: #042A3B;
	background: -webkit-linear-gradient(to left, #2B9C96, #042A3B);
	width: 100%;
	height: 100vh;


}

.circles {
	position: absolute;
	top: 10;
	left: 0;
	width: 100%;
	height: 100%;
	overflow: hidden;

}

.circles li {
	position: absolute;
	display: block;
	list-style: none;
	width: 20px;
	height: 20px;
	background: rgba(43, 156, 150, 0.5);
	animation: animate 25s linear infinite;
	bottom: -150px;

}

.circles li:nth-child(1) {
	left: 25%;
	width: 80px;
	height: 80px;
	animation-delay: 0s;
}


.circles li:nth-child(2) {
	left: 10%;
	width: 20px;
	height: 20px;
	animation-delay: 2s;
	animation-duration: 12s;
}

.circles li:nth-child(3) {
	left: 70%;
	width: 20px;
	height: 20px;
	animation-delay: 4s;
}

.circles li:nth-child(4) {
	left: 40%;
	width: 60px;
	height: 60px;
	animation-delay: 0s;
	animation-duration: 18s;
}

.circles li:nth-child(5) {
	left: 65%;
	width: 20px;
	height: 20px;
	animation-delay: 0s;
}

.circles li:nth-child(6) {
	left: 75%;
	width: 110px;
	height: 110px;
	animation-delay: 3s;
}

.circles li:nth-child(7) {
	left: 35%;
	width: 150px;
	height: 150px;
	animation-delay: 7s;
}

.circles li:nth-child(8) {
	left: 50%;
	width: 25px;
	height: 25px;
	animation-delay: 15s;
	animation-duration: 45s;
}

.circles li:nth-child(9) {
	left: 20%;
	width: 15px;
	height: 15px;
	animation-delay: 2s;
	animation-duration: 35s;
}

.circles li:nth-child(10) {
	left: 85%;
	width: 150px;
	height: 150px;
	animation-delay: 0s;
	animation-duration: 11s;
}



@keyframes animate {

	0% {
		transform: translateY(0) rotate(0deg);
		opacity: 1;
		border-radius: 0;
	}

	100% {
		transform: translateY(-1000px) rotate(720deg);
		opacity: 0;
		border-radius: 50%;
	}

}
</style>