# floating_logo
3D floating logo mozilla developer edition  theme




    <meta charset="UTF-8">

    <meta name="generator" content="Software RVG CSS Editor (www.softwarervg.com)">

    <meta name="dcterms.created" content="sa., 28 sep. 2016 01:25:28 GMT">

    <meta name="description" content="css,svg,development,by;Software RVG">

    <meta name="keywords" content="css,svg,Software RVG,3D animation,designs,creative work,artistic work">




    <title>firefox developer edition -svg and css development by Software RVG "
# mde_design

Two CSS combined with one SVG on background gradient circle colors all with mozilla developer edition as main theme."</title>



     <link rel="stylesheet" href="css/normalize.css">

     <link rel="stylesheet" href="css/style.css">

</head>

   <body>

   <div>

<style>



body{

  height: 100%;

  top: 0px;

  bottom: 0px;

}

@keyframes spinmozilla {

  0% { transform: rotate(0); }

  100%   { transform: rotate(-360deg); }

}





/* scene wrapper */

.wrapper{

  position:relative;

  margin: 0 auto;

  display:block;

  margin-top: 60px;

  margin-left:-60px;

  perspective: 1000px;

    perspective-origin: 60% 50%;

  transform: rotate(-10deg);

  

}

.wrapper > div {

  position: relative;

  margin: 0 auto;

  transform-style: preserve-3d;

  height: 0px;

}

.mozilla {

  width: 250px;

  position: absolute;

  top: 0px;

  z-index: 1;

  height: 100px !important;

}

.sun .star {

  width: 300px;

  height: 300px;

  background: url(https://www.mozilla.org/media/img/firefox/channel/toggler-dev.e8e6739d0126.png) no-repeat;

  background-size: cover;

  border-radius: 250px;

  margin: 0 auto;

  animation: spinmozilla 40s infinite linear;

}



</style>

<body>





</body>



<ul class="wrapper">

  <div class="sun">

    <div class="star"></div>

  </div>



</div>





  <head>

  

    

    

    <link rel="stylesheet" href="//codepen.io/assets/reset/normalize.css">



    

        <style>

      body {background-image:url('');

  min-height: 450px;	

  height: 100vh;

  margin: 0;

  

	

}



.stage {

  height: 100px;

  width: 500px;

  margin: auto;

  position: absolute;

  top: -100;

  right: 50;

	margin-top:50px;

	margin-left:430px;

	margin-bottom:230px;

  bottom: 0;

  left: 0;

  perspective: 9999px;

  transform-style: preserve-3d;

         

}



.layer {

  width: 100%;

  height: 100%;

  position: absolute;

  transform-style: preserve-3d;

  opacity: 0;

  animation: ಠ_ಠ 5s infinite alternate ease-in-out -7.5s, o_O 0.1s 1;

  animation-fill-mode: forwards;

  transform: rotateY(40deg) rotateX(33deg) translateZ(0);

}



.layer:after {

  font: 200px/0.65 metabold;

  content: 'mozilla';

  white-space: pre;

  text-align: center;

  height: 100%;

  width: 100%;

  position: absolute;

  top: 50px;

  color: whitesmoke;

  letter-spacing: -5px;

  text-shadow: 4px 0 10px rgba(0, 0, 0, 0.13);

}



.layer:nth-child(1):after {

  -webkit-transform: translateZ(0px);

          transform: translateZ(0px);

}



.layer:nth-child(2):after {

  -webkit-transform: translateZ(-2px);

          transform: translateZ(-2px);

}



.layer:nth-child(3):after {

  -webkit-transform: translateZ(-4px);

          transform: translateZ(-4px);

}



.layer:nth-child(4):after {

  -webkit-transform: translateZ(-6px);

          transform: translateZ(-6px);

}



.layer:nth-child(5):after {

  -webkit-transform: translateZ(-8px);

          transform: translateZ(-8px);

}



.layer:nth-child(6):after {

  -webkit-transform: translateZ(-10px);

          transform: translateZ(-10px);

}



.layer:nth-child(7):after {

  -webkit-transform: translateZ(-12px);

          transform: translateZ(-12px);

}



.layer:nth-child(8):after {

  -webkit-transform: translateZ(-14px);

          transform: translateZ(-14px);

}



.layer:nth-child(9):after {

  -webkit-transform: translateZ(-16px);

          transform: translateZ(-16px);

}



.layer:nth-child(10):after {

  -webkit-transform: translateZ(-18px);

          transform: translateZ(-18px);

}



.layer:nth-child(11):after {

  -webkit-transform: translateZ(-20px);

          transform: translateZ(-20px);

}



.layer:nth-child(12):after {

  -webkit-transform: translateZ(-22px);

          transform: translateZ(-22px);

}



.layer:nth-child(13):after {

  -webkit-transform: translateZ(-24px);

          transform: translateZ(-24px);

}



.layer:nth-child(14):after {

  -webkit-transform: translateZ(-26px);

          transform: translateZ(-26px);

}



.layer:nth-child(15):after {

  -webkit-transform: translateZ(-28px);

          transform: translateZ(-28px);

}



.layer:nth-child(16):after {

  -webkit-transform: translateZ(-30px);

          transform: translateZ(-30px);

}



.layer:nth-child(17):after {

  -webkit-transform: translateZ(-32px);

          transform: translateZ(-32px);

}



.layer:nth-child(18):after {

  -webkit-transform: translateZ(-34px);

          transform: translateZ(-34px);

}



.layer:nth-child(19):after {

  -webkit-transform: translateZ(-36px);

          transform: translateZ(-36px);

}



.layer:nth-child(20):after {

  -webkit-transform: translateZ(-38px);

          transform: translateZ(-38px);

}



.layer:nth-child(n+10):after {

  -webkit-text-stroke: 3px #fe642e;

}



.layer:nth-child(n+11):after {

  -webkit-text-stroke: 15px dodgerblue;

   text-shadow: 6px 0 6px #00366b, 5px 5px 5px #002951, 0 6px 6px #00366b;

}



.layer:nth-child(n+12):after {

  -webkit-text-stroke: 15px #0077ea;

}



.layer:last-child:after {

  -webkit-text-stroke: 17px rgba(0, 0, 0, 0.1);

}



.layer:first-child:after {

  color: #fff;

  text-shadow: none;

}



@keyframes ಠ_ಠ {

  100% {

            transform: rotateY(-40deg) rotateX(-43deg);

  }

}



@keyframes ಠ_ಠ {

  100% {

    -webkit-transform: rotateY(-40deg) rotateX(-43deg);

            transform: rotateY(-40deg) rotateX(-43deg);

  }

}

@-webkit-keyframes o_O {

  100% {

    opacity: 1;

  }

}

@keyframes o_O {

  100% {

    opacity: 1;

  }

}

.layer {

  width: 100%;

  height: 100%;

  position: absolute;

  -webkit-transform-style: preserve-3d;

          transform-style: preserve-3d;

  opacity: 0;

  -webkit-animation: ಠ_ಠ 5s infinite alternate ease-in-out -7.5s, o_O 0.1s 1;

          animation: ಠ_ಠ 5s infinite alternate ease-in-out -7.5s, o_O 0.1s 1;

  -webkit-animation-fill-mode: forwards;

          animation-fill-mode: forwards;

  -webkit-transform: rotateY(40deg) rotateX(33deg) translateZ(0);

          transform: rotateY(40deg) rotateX(33deg) translateZ(0);

}

    </style>



    

    

    

    

  </head>





 <body>



<div class="stage">

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

  <div class="layer"></div>

</div>

    

    

    

    

    

  </body>



 <style>

 



/* Main styles */

@import url(http://fonts.googleapis.com/css?family=metabold:800);



.text {

  fill: url(#gr-radial);

}



/* Other styles */



 

    <!--

	body h2 {text-align:center;

      color:#000000;

      background-color:#000000;

      background-image:url('Background Image');

      background-repeat:no-repeat;

    }

    a  { color:#0000FF; }

    a:visited { color:#0000FF; }

    a:hover { color:#ff0000; }

    a:active { color:#0000FF; }

    

body {

  min-height: 450px;

  height: 100vh;

  margin: 0;

  background: radial-gradient(circle,#084B8A,#084B8A,#084B8A,#084B8A,#084B8A,#084B8A,#084B8A,#0B2161,#0B2161);

} }

body svg {

  background: #111111 -webkit-linear-gradient(0deg, #2E2E2E 50%, #151515 50%);

  background: #111111 linear-gradient(90deg, #2E2E2E 50%, #151515 50%);

  background-size: .5em 100%;

  font: 5.1em/1 metabold;

  text-transform: uppercase;

  margin: 0;

} 



body text {

  background: #fff -webkit-linear-gradient(0deg, #000 50%, #151515 50%);

  background: #fff linear-gradient(90deg, #000 50%, #151515 50%);

  background-size: .5.1em 100%;

  font: 5.1em/1 metabold;

  text-transform: lowercase;

  margin: 0;

}



svg {

  position: absolute;

  width: 100%;

  height: 30%;

}



    </style>





<div class:"text"="">

<svg viewBox="0 0 600 300">



 <!-- Gradient -->

  <radialGradient id="gr-radial" cx="50%" cy="50%" r="70%">

    <!-- Animation for radius of gradient -->

    <animate attributeName="r" values="0%;150%;100%;0%" dur="2s" repeatCount="indefinite"></animate>

    <!-- Animation for colors of stop-color -->

    <stop stop-color="#0000FF" offset="1">

      <animate attributeName="stop-color" values="#A9D0F5;#00FFFF;#A9D0F5;#5882FA;#2E2EFE;#0000FF;#08088A;#0000FF;#0000FF;#2E2EFE;#5882FA;#FFFFFF;" dur="20" repeatCount="indefinite"></animate>

    </stop>

    <stop stop-color="rgba(55,55,55,0)" offset="100%"></stop>

  </radialGradient>

  

 

  <!-- Text -->

  <text text-anchor="middle" x="50%" y="25%" dy=".35em" class="text">

	firefox developer edition

 </text>



 </svg></div>

    

	  

  </body>

    

    

    

    

  </body>

</html>					
