# CPT_GROUP9
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<link rel="stylesheet" href="Group9.css">
		<title>Group 9</title>
	</head>
	<body>
		<div class="container">
			<div class="nav">
				<h1 id="logo">
					<a href="Group9.html">
						<img src="img/logo.jpg" alt="My Home" width="70.50" height="70.50" class="d-inline-block align-text-top">
					</a>  
				</h1>
				<h1 id="logo">GENCHEMATECH</h1>
				<nav>
					<ul>
						<li><a href="Group9.html">HOME</a></li>
						<li><a href="About.html">ABOUT</a></li>
						<li><a href="Contact.html">CONTACT US</a></li>
					</ul>
				</nav>
			</div>
			<div class="content"> 
				<div id="Content"> 
					<a href="General Chemistry.html">
						<div class="Sub content1 zoom"> 
							<h1></h1>
						</div>
					</a>
					<a href="Empowerment Technology.html">
						<div class="Sub content2 zoom"> 
							<h1></h1>
						</div>
					</a>
					<a href="General Mathematics.html">
						<div class="Sub content3 zoom"> 
							<h1></h1>
						</div>
					</a>
				</div>
			</div>
		</div>
	</body>
</html>
*{
	padding: 0;
	margin: 0;
}
.container {
	width: 100%;
	height: 100vh;
	background-image: url('img/bg.jpg');
	background-position: center;
	background-size: cover;
}
.nav {
	height: 10%;
	display: flex;
	align-items: center;
	width: 100%;
	background-color: rgba(255, 255, 255, 0.048);
	padding-left: 8%;
	padding-right: 8%;
	box-sizing: border-box;
	color: white;
}
#logo {
	width: 60px;
	cursor: pointer;
}
nav {
	flex: 1;
	text-align: right;	
}
nav ul li {
	list-style: none;
	display: inline-block;
	margin: 0px 35px;
}
nav ul li a {
	text-decoration: none;
	font-weight: bold;
	font-size: 25px;	
	color: white;
}
.content {
	display: flex;
	height: 85%;
	align-items: center;
	padding-left: 23%;
	padding-right: 23%;
	box-sizing: border-box;
}
p {
	font-size: 20px;
	line-height: 20px;
}
.Content {
	flex-basis: 50%;
}
button {
	width: 165px;
	color: black;
	font-size: 20px;
	padding: 12px 0px;
	margin-top: 30px;
	border: 1px solid black;
	border-radius: 20px;
}
button:hover {
	background-color: rgba(101, 105, 101, 0.822);
	color: white;
}
.Sub {
	width: 310px;
	height: 450px;
	display: inline-block;
	border-radius: 10px;
	padding: 15px 25px;
	box-sizing: border-box;
	cursor: pointer;
	margin: 10px 15px;
	background-position: center;
	background-size: cover;
	transition: transform 0.5s;
}
.Sub h1 {
	background-size: rgba(233, 228, 218, 0.068);
	font-size: 20px;	
}
.content1 {
	background-image: url('img/chem.jpg')
}
.content2 {
	background-image: url('img/Tech.jpg');
}
.content3 {
	background-image: url('img/Math.jpg');
}
#logo {
	margin-left: 20px;
}
.zoom:hover {
	transform: translateY(-20px);
}
#Head {
	text-align: center;
	font-size: 50px;
}
#h2 {
	margin-left: 70px;
	margin-bottom: 7px;	
}
#p {
	margin-left: 70px;
	margin-right: 70px;
	margin-bottom: 25px;	
}
#a {
	margin-left: 70px;
	margin-right: 70px;
	margin-bottom: 25px;	
}
#logoChem {
	width: 60px;
	cursor: pointer;
	color: black;
	margin-left: 20px;
	margin-top: 10px
}
#chem {
	color: black;
	margin-top: 10px
}
#GenChemExVid {
	margin-left: 425px;
	margin-right: 450px;
	margin-top: 50px;

}
<!DOCTYPE html>
<html>
	<head>
		<link rel="stylesheet" href="Group9.css">
		<link rel="stylesheet" href="Settings.css">
		<link rel="stylesheet" href="Text.css">
		<title>Empowerment Technology</title>
	</head>
	<body>
		<div class="container">
			<div class="nav">
				<h1 id="logo">
					<a href="Group9.html">
						<img src="img/logo.jpg" alt="My Home" width="70.50" height="70.50" class="d-inline-block align-text-top">
					</a>  
				</h1>
				<h1 id="logo">GENCHEMATECH</h1>
				<nav>
					<ul>
						<li><a href="Group9.html">HOME</a></li>
						<li><a href="About.html">ABOUT</a></li>
						<li><a href="Contact.html">CONTACT US</a></li>
					</ul>
				</nav>
			</div>
		<div id="About"> 
			<h3 id="Abouth3">About us:</h3>
			<p>THE WEBSITE'S PRIMARY OBJECTIVE IS TO FACILITATË THE CREATION OF A WEBPAGE OR WEBSITE DEDICATED TO THE PRESENTATION OF EXPERIMENTS, POST-LAB WORKSHEETS, 
			<br id="Aboutbr">AND DOCUMENTATION RELATED TO FUNCTIONS IN A SPECIFIC INSTITUTION.AS A WEB DEVELOPER, OUR ROLE INVOLVES LEADING A TEAM IN THE DEVELOPMENT OF THIS PLATFORM, 
			<br id="Aboutbr">WHICH WILL SERVE AS A COMPREHENSIVE RESOURCE FOR THE INSTITUTION'S ACTIVITIES.</p>
			<h3 id="Abouth3">Contributors:</h3>
			<p id="Ap">JENNIBERT M. CABUTE</p>
			<p id="Ap">ROSITA B. MORALLOS</p>
			<p id="Ap">XIANT KENT ALDRIN G. CALUYA</p>
			<p id="Ap">SEAN KAYLEE MANZANO</p>
		</div>
	</body>
