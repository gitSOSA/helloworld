# HELLOW WORLD!
<!DOCTYPE html>
<html dir="ltr" lang="en">
<head>
	<title>COLORFUL</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initail-scale=1.0">
	<link href="https://fonts.googleapis.com/css2?family=Gugi&display=swap" rel="stylesheet"> 
</head>
<!--SOSA-->
<style type="text/css">
 body{
 	background-color: crimson;
 	height: 100vh;
 	display: grid;
 	place-items:center;
}
.text{
	letter-spacing: 3px;
	font-size: 3em;
	font-family: 'Gugi', cursive;
	text-shadow: 2px -2px  black, -2px 2px  black, 2px 0px  black, 0px 3px  black;
	animation: text 10s ease-in-out infinite;
}
@keyframes text{
	0%{
		color: black;
	}
	10%{
		color: red;
	}
	20%{
		color: orange;
	}
	30%{
		color: yellow;
	}
	40%{
		color: green;
	}
	50%{
		color: blue;
	}
	60%{
		color: indigo;
	}
	70%{
		color: violet;
	}
	80%{
		color: coral;
	}
	90%{
		color: peachpuff;
	}
	100%{
		color: black;
	}
}
.cloud{
	animation-name: float;
	animation-duration: 20s;
	animation-timing-function: ease-in-out;
	animation-iteration-count: infinite;
}
@keyframes float{
	0%{
		bottom: 0%;
		opacity: 0;
	}
	25%{
		bottom: 10%;
		opacity: 0.4;
	}
	50%{
		bottom: 20%;
		opacity: 0.8;
	}
	75%{
		bottom: 40%;
		opacity: 1;
	}
	100%{
		bottom: 60%;
		opacity: 0;
	}
}
</style>
<body>
<h1 class="text">HELLO WORLD!</h1>

<div class="p-spin" style="
background-color: rgba(220,220,220,0.3);
border-radius: 35%;">

	<span class="cloud" style="
position: absolute;
left: 60%;
bottom: 0%;
height: 250px;
width: 350px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 5s;
animation-duration: 15s;"></span>

	<span class="cloud" style="
position: absolute;
left: 50%;
bottom: 0%;
height: 200px;
width: 300px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 15s;
animation-duration: 2s;"></span>

	<span class="cloud" style="
position: absolute;
left: 40%;
bottom: 0%;
height: 150px;
width: 250px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 10s;
animation-duration: 5s;"></span>

	<span class="cloud" style="
position: absolute;
left: 65%;
bottom: 0%;
height: 100px;
width: 200px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 5s;
animation-duration: 10s;"></span>

	<span class="cloud" style="
position: absolute;
left: 30%;
bottom: 0%;
height: 50px;
width: 150px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 10s;
animation-duration: 15s;"></span>

	<span class="cloud" style="
position: absolute;
left: 20%;
bottom: 0%;
height: 50px;
width: 150px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 10s;
animation-duration: 15s;"></span>

	<span class="cloud" style="
position: absolute;
left: 10%;
bottom: 0%;
height: 50px;
width: 150px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 5s;
animation-duration: 5s;"></span>

	<span class="cloud" style="
position: absolute;
left: 35%;
bottom: 0%;
height: 50px;
width: 150px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;
animation-delay: 5s;
animation-duration: 18s;"></span>

	<span class="cloud" style="
position: absolute;
left: 70%;
bottom: 0%;
height: 300px;
width: 400px;
background-color: rgba(220,220,220,0.3);
border-radius: 35%;
opacity: 0;"></span>

</div>
