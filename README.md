<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<!-- <link rel="stylesheet" type="text/css" href="test1.css"> -->
	<link rel="icon" href="picture/logo.png">
	<title>SafeKnow v1.1</title>
	<style>
		*{
	padding: 0;
	margin: 0;
}
.navbar{
	display: inline-flex;
}
.navbar img{
	height: 10vh;
	padding-left: 70px;
	padding-top: 20px;
}
.navbar h3{
	padding-top: 40px;
	padding-left: 20px;
	color: blue;
	font-family: montserat ;
	font-size: 28px;
}
.navs{
	display: inline-flex;
	margin-left: 100px;
}
.navs a{
	padding-top: 40px;
	padding-left: 50px;
	text-decoration: none;
	font-family: monospace;
	font-size: 22px;
}
.navs a:hover{
	text-decoration: underline;
	text-decoration-color: royalblue;
}
.login{
	background-color: white;
	margin-top: 38px;
	margin-left: 60px;
	height: 5vh;
	width: 80px;
	color: royalblue;
	border: 2px solid royalblue;
	border-radius: 3px;
}
.login:hover{
	text-decoration: underline;
	border: none;
	cursor: pointer;
}
.join{
	background-color: royalblue;
	margin-top: 38px;
	margin-left: 60px;
	height: 5vh;
	width: 80px;
	color: white;
	border: 2px solid royalblue;
	border-radius: 3px;
}
.join:hover{
	text-decoration: underline;
	border: none;
	cursor: pointer;
}
.hero{
	/* border: 1px solid red; */
	display: inline-flex;
	margin-top: 40px;
	margin-left: 150px;
	width: 80%;
	margin-right: 10px;
	height: 65vh;
}
.welcome{
	/* border: 1px solid blue; */
	padding-top: 70px;
	width: 40%;
}
.welcome h2{
	color: rgba(109, 142, 240, 0.823);
	font-size: 32px;
}
.welcome b{
	color: rgb(21, 21, 155);
	font-size: 34px;
}
.welcome p{
	padding-top: 50px;
	font-size: 18px;
}
.patner{
	background-color: black;
	color: white;
	border-radius: 25px;
	height: 5vh;
	width: 150px;
	margin-top: 20px;
	margin-left: 10px;
}
.patner:hover{
	background-color: white;
	border: 1px solid black;
	color: black;
	text-decoration: underline;
	text-decoration-color: black;
	cursor: pointer;
}
.heropics1{
	/* border: 1px solid yellow; */
	margin-left: 200px;
	width: 600px;
	height: 20vh;
}

.map img{
	margin-left: 110px;
	padding-top: 15px;
	float: left;
	height: 15vh;
	width: 200px;
}

.police img{
	float: right;
	margin-left: 3px;
	height: 17vh;
	width: 195px;
}
.safer img{
	float: left;
	padding-top: 5px;
	padding-left: 55px;
	height: 19vh;
	width: 265px;
}
.granny img{
	float: right;
	padding-top: 5px;
	margin-left: 3px;
	width: 185px;
	height: 23vh;
}
.meds img{
	float: left;
	height: 18vh;
	padding-top: 5px;
	margin-left: 46px;
	width: 130px;
}
.phone img{
	float: left;
	height: 20vh;
	padding-top: 5px;
	padding-left: 6px;
	width: 140px;
}
.looking img{
	float: right;
	width: 185px;
	padding-top: 5px;
	height: 18vh;
}
.steps{
	/* border: 1px solid blue; */
	margin-top: 80px;
	margin-left: 110px;
	margin-right: 10px;
	width: 80%;
	height: 4	0vh;
}
.steps h2{
	text-align: center;
	color: rgba(7, 7, 131, 0.912);
}

.pics{
	margin-top: 50px;
	display: flex;
	height: 20vh;
}
#download{
	padding-left: 200px;
	text-align: center;
	width: 150px;
}
#download h3{
	padding-top: 10px;
	font-size: 22px;
	color: rgba(7, 7, 131, 0.912);
}
#download img{
	width: 100px;
	height: 10vh;
}
#download small{
	font-size: 15px;
	padding-top: 10px;
	color: royalblue;
}
#mobile{
	padding-left: 100px;
	text-align: center;
	width: 150px;
}
#mobile h3{
	padding-top: 10px;
	font-size: 22px;
	color: rgba(7, 7, 131, 0.912);
}
#mobile img{
	width: 60px;
	height: 10vh;
}
#mobile small{
	font-size: 15px;
	padding-top: 10px;
	color: royalblue;
}
#trust{
	padding-left: 100px;
	text-align: center;
	width: 150px;
}
#trust h3{
	padding-top: 10px;
	font-size: 22px;
	color: rgba(7, 7, 131, 0.912);
}
#trust img{
	width: 100px;
	height: 10vh;
}
#trust small{
	font-size: 15px;
	padding-top: 10px;
	color: royalblue;
}
.bodytext{
	background-image: url('picture/path.png');
	background-size: contain;
	background-repeat: no-repeat;
	/* border: 1px solid black; */
	height: 100vh;
}
.problem{
	width: 400px;
	margin-left: 809px;
}
.problem h2{
	font-size: 32px;
	padding-top: 120px;
	text-align: right;
	padding-right: 84px;
	color: rgb(50, 76, 155);
}
.problem p{
	padding-top: 20px;
	padding-right: 30px;
	color: royalblue;
	font-size: 22px;
}
.solution{
	/* border: 1px solid red; */
	width: 400px;
	margin-left: 146px;
}
.solution h2{
	font-size: 32px;
	padding-top: 3px;
	text-align: left;
	padding-left: 30px;
	color: rgb(50, 76, 155);
}
.solution p{
	padding-top: 20px;
	padding-left: 0px;
	color: royalblue;
	font-size: 22px;
}
.empty{
	margin-left: 150px;
	margin-top: 10px;
	width: 1000px;
	height: 25vh;
	background-color: rgb(89, 85, 85);
}
.appd{
    border: 0.1px solid white; 
    margin-top: 10px;
}
.appdd{
    float: right;
    margin-right: 50px;

}
.appdd img{
    width: 500px;
    height: 100hv;
}
.appddbg{
    width: 1345px;
    height: 57vh;
    background-image: url('picture/rectangle.png');
    background-size: cover;
    margin-top: 75px;
}
.appdownload{
	/* border: 1px solid red; */
	margin-left: 90px;
	margin-top: 10px;
	width: 450px;
}
.appdownload img{
    padding-top: 30px;
	padding-left: 150px;
	width: 130px;
	height: 25vh;
}
.appdownload h4{
	font-size: 34px;
	color: white;
	padding-left: 40px;
}
.buttons {
	display: flex;
	padding-top: 20px;
	padding-left: 50px;
}
.buttons button{
	background-color: black;
	color: white;
	border-radius: 25px;
	height: 6vh;
	width: 120px;
	margin-top: 20px;
	margin-left: 30px;
}
/* /* .buttons button img{
	height: 2vh;
	width: 5px;
} */
.buttons button:hover{
	background-color: white;
	border: 1px solid black;
	color: black;
	text-decoration: underline;
	text-decoration-color: black;
	cursor: pointer;
}
.appdownload p{
	padding-left: 60px;
	padding-top: 10px;
	color: white;
	text-align: center;
	font-size: small;
	width: 300px;
}
.screenshot{
	background-image: url('picture/path2.png');
	background-size: 900px;
	background-repeat: no-repeat;
	height: 335vh;
	width: 1250px;
	/* border: 0.1px solid black;  */
	margin-left: 90px;
}
.screenshot1{
	display: flex;
	/* border: 1px solid black; */
	/* height: 50vh; */
}
#sc{
	text-align: center;
	color: grey;
	font-size: 64px;
	padding-top: 20px;
	padding-left: 50px;
}
.onboarding{
	/* border: 0.1px solid red; */
	padding-top: 100px;
	width: 400px;
	color: royalblue;
}
.onboarding h2{
	color: royalblue;
	font-size: 22px;
	text-align: left;

}
.onboardingimg{
	display: flex;
	/* border: 1px solid yellow; */
	margin-left: 70px;
}
.onboardingimg img{
	height: 40vh;
	width: 130px;
	padding-left: 10px;
	padding-top: 20px;
}
.screenshot2{
	display: flex;
	margin-top: 150px;
	/* border: 1px solid black; */
	/* height: 50vh; */
}
.onboarding2{
	/* border: 0.1px solid red; */
	padding-top: 100px;
	margin-left: 250px;
	width: 300px;
	color: royalblue;
}
.onboarding2 h2{
	color: royalblue;
	font-size: 22px;
	text-align: left;

}
.onboarding2img{
	display: flex;
	/* border: 1px solid yellow; */
	margin-left: 10px;
}
.onboarding2img img{
	height: 60vh;
	width: 190px;
	padding-left: 30px;
	padding-top: 20px;
}
.screenshot3{
	display: flex;
	margin-top: 150px;
	/* border: 1px solid black; */
	/* height: 50vh; */
}
.onboarding3{
	/* border: 0.1px solid red; */
	padding-top: 100px;
	width: 350px;
	color: royalblue;
}
.onboarding3 h2{
	color: royalblue;
	font-size: 22px;
	text-align: left;

}
.onboarding3img{
	display: flex;
	/* border: 1px solid yellow; */
	margin-left: 250px;
}
.onboarding3img img{
	height: 40vh;
	width: 130px;
	padding-left: 10px;
	padding-top: 20px;
}
	</style>
</head>
<body>
	<!-- navbar code -->
	<div class="navbar">
			<img src="picture/logo.png">
			<h3>SafeKnow</h3>
		<div class="navs">	
			<a href="#home">Home</a>
			<a href="#Subscribe">Subscribe</a>
			<a href="#About">About</a>
			<a href="#Contact_us">Contact Us</a>
		</div>
		<button class="login">Login</button>
		<button class="join">Join Us</button>
	</div>

	<!-- hero board codes -->
	<div class="hero">
		<div class="welcome">
			<h2>Welcome <br>to <b>SafeKnow.</b></h2>
			<p>Lorem Ipsum dolor sit amet, consectetur adipiscing elit,
				sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
				Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
			</p>
			<button class="patner">Patner With Us</button>
		</div>

		<!-- heropics code -->
		<div class="heropics1">
			<div class="map"><img src="picture/map.png" alt="map"></div>
			<div class="police"><img src="picture/police.png" alt="police"></div>
			<div class="safer"><img src="picture/safer.png" alt="SaferCliq"></div>
			<div class="granny"><img src="picture/granny.png" alt="granny"></div>
			<div class="meds"><img src="picture/meds.png" alt="medication"></div>
			<div class="phone"><img src="picture/phone.png" alt="phone"></div>
			<div class="looking"><img src="picture/looking.png" alt="looking man"></div>
		</div>	
	</div>

	<div class="steps">
		<h2>Follow these three steps and guarantee <br>your safety with Safercliq</h2>
		<div class="pics">
			<div id="download"><img src="picture/download.png" alt="download"><h3>Download</h3><br><small>lorem Ipsum dolor sit amet, consectetur adipiscing elit</small></div>
			<div id="mobile"><img src="picture/mobile.png" alt="use app"><h3>Use App</h3><br><small>lorem Ipsum dolor sit amet, consectetur adipiscing elit</small></div>
			<div id="trust"><img src="picture/handtrust.png" alt="secure"><h3>Secure</h3><br><small>lorem Ipsum dolor sit amet, consectetur adipiscing elit</small></div>
		</div>
	</div>

	<div class="bodytext">
		<div class="problem">
			<h2>Problems</h2>
			<p>Lorem Ipsum dolor sit amet, consectetur adipiscing elit,
				sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
				Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat
			</p>
		</div>
		<div class="solution">
			<h2>Solutions</h2>
			<p>Lorem Ipsum dolor sit amet, consectetur adipiscing elit,
				sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
				Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat
			</p>
		</div>
	</div>
	<div class="empty">
		<!-- empty -->
	</div>
	<div class="appd">
		<div class="appdd"><img src="picture/phones.png" alt="phones"></div>
        <div class="appddbg">
            <div class="appdownload">
                <img src="picture/logo2.png" alt="logo">
			<h4>Download Our New App</h4>
			<div class="buttons">
				<button>Apple Store</button>
				<button>Google Store</button>
			</div>
			<p>
				Lorem Ipsum dolor sit amet, consectetur adipiscing elit,
				sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
			</p>
            </div>
        </div>
	</div>
	<div class="screenshot">
		<h2 id="sc">Screenshot</h2>
		<div class="screenshot1">
			<div class="onboarding">
				<h2>01 onboarding</h2>
				<p>
					Lorem Ipsum dolor sit amet, consectetur adipiscing elit,
					sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
					Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat	
				</p>
			</div>
			<div class="onboardingimg">
				<img src="picture/onboarding1.png" alt="onboarding">
				<img src="picture/onboarding2.png" alt="onboarding">
				<img src="picture/onboarding3.png" alt="onboarding">
				<img src="picture/onboarding4.png" alt="onboarding">
				<img src="picture/onboarding5.png" alt="onboarding">
			</div>
		</div>
		<div class="screenshot2">
			<div class="onboarding2img">
					<img src="picture/onboarding 6.png" alt="onboarding">
					<img src="picture/onboarding7.png" alt="onboarding">
					<img src="picture/onboarding8.png" alt="onboarding">
			</div>
			<div class="onboarding2">
				<h2>02 Authentication</h2>
				<p>
					Lorem Ipsum dolor sit amet, consectetur adipiscing elit,
					sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
					Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat	
				</p>
			</div>
		</div>
		<div class="screenshot3">
			<div class="onboarding3">
				<h2>01 onboarding</h2>
				<p>
					Lorem Ipsum dolor sit amet, consectetur adipiscing elit,
					sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
					Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat	
				</p>
			</div>
			<div class="onboarding3img">
				<img src="picture/onboarding9.png" alt="onboarding">
				<img src="picture/onboarding10.png" alt="onboarding">
				<img src="picture/onboarding3.png" alt="onboarding">
				<img src="picture/onboarding4.png" alt="onboarding">
			</div>
		</div>
	</div>
</body>
</html>
