<!Doctype html>
<html land="en">
<head>
   <title>Home</title>
   <link rel="stylesheet" type="text/css" href="home.css">
</head>
   </head>
<body>
       <div class="container"> 
    <img src="logo.jpg" alt="logo" class="logo" height=100px width=100px a href="daysforgirls.org">
    <nav>
     <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="mission.html">About Us</a>
        <li><a href="project.html">Projects</a></li>
        <li><a href="contact.html">Contact Us</a></li>
        </ul>
        </nav>
        </div>
       </section>
       </header>



    <section class="intro">
    	<div class="inner">
    	   <div class="content">
    	   <h1>MSU DAYS FOR GIRLS INTERNATIONAL</h1> 
    	   <a class="btn" href="#"></a>
    	 </div>
    	 </div>
    	 </section>





body { 
margin:0;
background: #222;
font-family: sans-serif;
font-weight:300;

}

.container { 
width:80%;
margin: 0 auto; 
} 

.logo { 
float:left;
margin-left:10px;

 }

nav {  
float: right;

}


nav ul { 
margin: 0;
padding:0;
list-style: none; }


nav li { 
display: inline-block;
margin-left:50px;
padding-top: 25px;
position:relative; }


 nav a { 
color: orange;
text-decoration: none;
text-transform: uppercase;
}


nav a:hover { 
color: white; }


nav a::before { 
content: ' ';
display: block;
height: 5px;
width: 100%;
background-color: orange;

top:0;
width:0%;
transition-timing-function: ease 250ms;
transition: all ease-in-out 250ms;
}

nav a:hover::before { 
width: 100%;
 }






html, body { 
	margin:0;
	padding:0;
	height: 100%;
	width: 100%;
 }


.intro {
	padding:0;
	margin:0;
	height: 100%;
	max-width:100%;
	margin: auto;
	background: url("class.jpg") no-repeat 55% 55%;
	top:0;
	background-size:cover;

}

.intro .inner {
    left: 0;
    line-height: 100px;
 	text-align: center;
 	margin-top:-100px;
    position:absolute;
    top: 50%;
    width: 100%;
}

.content { 
color: orange; 
font-family:arial;
font-size:25px;
}


