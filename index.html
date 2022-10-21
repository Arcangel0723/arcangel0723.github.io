<!DOCTYPE html>
<!-- saved from url=(0054)https://drapak.ca/cpg/2.05H-CakeyClicker-LastName.html -->
<html>
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
		<title>Cakey Clicker</title>
		<meta name="author" content="Gabriel Denney-Martell">
		<meta name="description" content="A simple clicker game made with JS">
		
		<!--
			Created:	25. February 2018										- Drapak
			Modified:	3. October 2018		- changed assignment number 		- Drapak
						9. October 2018		- changed cakeID to cakeId			- Drapak
						12. Oct 2018		- added specific style criteria		- Drapak		
						4. Oct 2022			- started assignment				- Gabe
						5. Oct 2022			- fixed rainbow button				- Gabe
						6. Oct 2022			- changed up the style				- Gabe
			Finished:	6. Oct 2022
		-->
		
		<style>

			body{
				background-color: #222222;
				color: #BBBBBB;
				font-family: Georgia, 'Times New Roman', Times, serif;
			}
			#cakeId{ 
				display: block;
				margin-left: auto;
				margin-right: auto;
				margin-top: 20%;
				width: 100px;
				z-index: 2;
			}
			#name{
				color: grey;
			}
			#scoreHolder{
				visibility: hidden;
				color: #bbbbbb;
			}
			#scoreHolder{
				z-index: 3;
			}
			@keyframes rainbow {
				/* an animation that goes from red to green to blue to white */
				0% {
					color: #FF0000
				}
				33.33% {
					color: #00FF00
				}
				66.66% {
					color: #0000FF
				}
				100% {
					color: #FFFFFF
				}
			}
			#rainbow {
				/* applying an animation that rotates through some colors then reverses */
				animation-name: rainbow;
				animation-duration: 5s;
				animation-iteration-count: infinite;
				animation-timing-function: linear;
				animation-direction: alternate;
			}
			#playerName {
				text-align: center;
				font-size: 80px;
			}
			ul {
				list-style-type: none;
			}
			#informationBox {
				position: absolute;
				left: 100px;
				top: 100px;
				background-color: azure;
				border-radius: 10px;
				border-color: #800815;
				border-style: solid;
				padding-left: 50px;
				padding-top: 20px;
				padding-bottom: 20px;
				padding-right: 50px;
			}
			#informationText{
				color: black;
			}
			#scoreHolder {
				position: fixed;
				top: 50px;
				right: 50px;
				font-size: x-large;
				color: chartreuse;
			}
			#score {
				color: #BBBBBB;
			}
			
		</style>

	</head>

	<body>		
		<h1 id=title>Cakey Clicker</h1>

		<div id=playerName></div>

		<div id=informationBox>
			<p id=informationText>
				Enter your name here! Submit it, or press the rainbow button
				to make your name <span id=rainbow>rainbow</span>! <br>
				After that, click on the cake! How high of a score can you get?
			</p>
			<ul>
				<li>
					<input id=nameQuery type="text" value="Anonymous"></input>
				</li>
				<li>
					<button id=submitName>Submit!</button>
				</li>
				<li>
					<button id=submitRainbow>Rainbow!</button>
				</li>
			</ul>
		</div>

		<div id=scoreHolder>
			<ul>
				<li>
					Score!
				</li>
				<li id=score>
					0
				</li>
			</ul>			
		</div>		

		<img id="cakeId" src="http://drapak.ca/cpg/img/cake.svg">

		<script>

			//stores player name
			var playerName = "anonymous";
			//stores score
			var score = 0;
			//stores the size of the cake
			var cakeSize = 100;
			//is the name going to be rainbow or not
			var isRainbow;
			//stores whether the player has submitted a name or not
			var submitName = false;

			//sets isRainbow to true
			function setRainbow()
			{
				getName(true)
			}

			//when the player hits the submit button, their name is taken from the text field
			//then if the player decided to make their name rainbow the variable isRainbow
			//is set to true so it will add an id that contains a css rainbow animation
			//after that, various things are hidden and revealed
			function getName(isRainbow)
			{
				//gets player name from text field
				playerName = document.getElementById( "nameQuery" ).value;
				//if the player clicks on the rainbow button then isRainbow will become an id
				if (isRainbow == true){
					isRainbow = "id=rainbow";
				}
				//if the player submits a blank name or just a space then the name is set to
				//Anonymous, because otherwise the name will appear as nothing
				if (playerName == "" || playerName == " "){
					playerName = "Anonymous";
				}
				//adds a title telling the player to click as much as they want
				//if isRainbow is set to id=rainbow then that id applies to the span
				//one major problem is people can inject whatever code they want,
				//but I don't know how to mitigate that yet
				document.getElementById( "playerName" ).innerHTML = "Click away, " + "<span " +
				isRainbow + ">" + playerName + "</span>" + "!";
				//sets visibility of various elements
				document.getElementById( "scoreHolder" ).style.visibility = "visible";
				document.getElementById( "informationBox" ).style.visibility= "hidden";
				//lets player click the cake
				submitName = true;
			}

			//increases the cakes size and score
			function increaseScore()
			{	
				if(submitName == true){
					//increments score and cake size variables
					score = score + 100;
					cakeSize = cakeSize + 10;
					//changes the score
					document.getElementById( "score" ).innerHTML = parseInt(score);
					//increases cake size in pixels
					document.getElementById( "cakeId" ).style.width = cakeSize + "px";
				}
				if(score > 1000){
					document.getElementById( "score" ).style.fontSize = "50px";
				}
				if(score > 100000){
					document.getElementById( "scoreHolder" ).style.fontSize = "60px";
					document.getElementById( "scoreHolder" ).style.fontWeight = "bold";
					document.getElementById( "scoreHolder" ).style.color = "#800815";
					document.getElementById( "score" ).style.animationName = "rainbow";
					document.getElementById( "score" ).style.animationDuration = "5s";
					document.getElementById( "score" ).style.animationIterationCount = "infinite";
					document.getElementById( "score" ).style.animationTimingFunction = "linear";
					document.getElementById( "score" ).style.animationDirection = "alternate";
				}
			}

			//when the cake is clicked, calls the function to increase size and score
			document.getElementById( "cakeId" ).onclick = increaseScore;
			//when the rainbow button is clicked, it calls a function to set isRainbow to true
			document.getElementById( "submitRainbow" ).onclick = setRainbow;
			//calls the get name function when the player clicks submit or enter
			document.getElementById( "submitName" ).onclick = getName;
			document.getElementById( "nameQuery" ).onchange = setRainbow;
		
		</script>
	</body>
</html>
