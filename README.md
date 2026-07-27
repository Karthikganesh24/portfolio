# Ex01 Portfolio
## Date:25/07/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
#### HTML CODE:
```
<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Karthik Ganesh | Portfolio</title>

<link rel="stylesheet" href="style.css">

</head>


<body>


<!-- Navigation -->

<header>

<nav>

<h2 class="logo">
Karthik Ganesh <span>.G</span>
</h2>


<ul>

<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#education">Education</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#contact">Contact</a></li>

</ul>

</nav>

</header>





<!-- Hero Section -->

<section class="hero" id="home">


<div class="hero-content">


<h1>
Hi, I'm <span>Karthik Ganesh</span>
</h1>


<h2>
Fullstack  Developer | Game Developer
</h2>


<p>

Information Technology student passionate about
software development, VR applications,
game development and emerging technologies.

</p>



<a href="resume/resume.pdf" 
class="btn" download>

Download Resume

</a>


</div>



<div class="profile">

<img src="image/karthik.jpg">

</div>



</section>







<!-- About -->


<section id="about">


<h1 class="heading">
About Me
</h1>


<p class="text">

I am a motivated Information Technology undergraduate
interested in software development, game development,
virtual reality and real-time applications.

I enjoy creating interactive experiences using
Unity, Unreal Engine and Blender.

</p>


</section>







<!-- Education -->


<section id="education">


<h1 class="heading">
Education
</h1>



<div class="cards">


<div class="card">

<h2>
B.Tech Information Technology
</h2>


<p>

Saveetha Engineering College

<br>

2024 - 2027

<br>

GPA : 7.5

</p>


</div>





<div class="card">

<h2>
Diploma Information Technology
</h2>


<p>

MSPVL Polytechnic College

<br>

2021 - 2024

<br>

Percentage : 84%

</p>


</div>



</div>


</section>








<!-- Internship Experience -->

<section id="experience">


<h1 class="heading">
Internship Experience
</h1>



<div class="cards">


<div class="card internship-card">


<a href="Internship/internship.pdf"
target="_blank">


<h2>
ZITACAD - ZitRaar Technologies Pvt Ltd
</h2>


</a>



<p>
Internship
</p>


<p>
June 2022 - July 2022
</p>



<p>

Zoho Creator, low-code application development,
database management and workflow automation.

</p>


</div>



</div>


</section>




<!-- Projects -->


<section id="projects">


<h1 class="heading">
Projects
</h1>



<div class="cards">



<div class="card">


<h2>
VR Learnspace
</h2>


<p>

Virtual reality based interactive learning platform
with immersive 3D simulations and real-time engagement.

</p>


</div>





<div class="card">


<h2>
College Management System
</h2>


<p>

Web-based college management system developed using
C#, HTML, CSS and MySQL.

</p>


</div>





<div class="card">


<h2>
VR Offroad Game
</h2>


<p>

VR driving game developed using Unreal Engine
with realistic environments and vehicle controls.

</p>


</div>



</div>


</section>








<!-- Skills -->


<section id="skills">


<h1 class="heading">
Technical Skills
</h1>


<div class="skills">


<span>Java</span>

<span>Python</span>

<span>C</span>

<span>HTML</span>

<span>CSS</span>

<span>C#</span>

<span>MySQL</span>

<span>Unity</span>

<span>Unreal Engine</span>

<span>Blender</span>


</div>


</section>








<!-- Leadership -->


<section>


<h1 class="heading">
Leadership
</h1>



<div class="card large">


<h2>
Tech Society - Joint Secretary
</h2>


<p>

2025 - 2027

<br><br>

Conducted workshops and technical events
related to Blender, Unity, Unreal Engine
and VR development.

</p>


</div>


</section>







<!-- Certifications -->

<section id="certifications">


<h1 class="heading">
Certifications
</h1>



<div class="cards">


<!-- Google Certificate -->

<div class="card certificate-card">


<a href="Certifications/technical support fundamentals.pdf" target="_blank">


<h2>
Google Technical Support Fundamentals
</h2>


</a>


<p>
Google via Coursera
</p>


</div>





<!-- AWS Certificate -->


<div class="card certificate-card">


<a href="Certifications/AWS_Academy_Graduate___Cloud_Foundations___Training_Badge_Badge20251114-31-rnawxi.pdf" target="_blank">


<h2>
AWS Academy Graduate
</h2>


</a>


<p>
Cloud Foundations
</p>


</div>



</div>


</section>



<!-- Contact -->


<section id="contact">


<h1 class="heading">
Contact
</h1>


<p>
📧 karthikganesh2062005@gmail.com
</p>


<p>
📱 +91 6385490022
</p>


<p>

<a href="https://github.com/Karthikganesh24">
GitHub
</a>

&nbsp; | &nbsp;

<a href="https://linkedin.com/in/karthik-ganesh20">
LinkedIn
</a>

</p>


</section>


<footer>

<p>
© 2026 Karthik Ganesh
</p>

</footer>



</body>

</html>
```
#### CSS CODE:
```
*{

margin:0;
padding:0;
box-sizing:border-box;

}


html{

scroll-behavior:smooth;

}



body{

font-family:Arial, sans-serif;

background:#020617;

color:white;

}





header{

background:#020617;

position:fixed;

width:100%;

top:0;

z-index:100;

}



nav{

display:flex;

justify-content:space-between;

align-items:center;

padding:20px 10%;

}



.logo{

font-size:32px;

}



.logo span{

color:#38bdf8;

}



nav ul{

display:flex;

gap:25px;

list-style:none;

}



nav a{

color:white;

text-decoration:none;

}





.hero{

min-height:100vh;

display:flex;

justify-content:center;

align-items:center;

gap:100px;

padding:100px 10%;

}



.hero-content{

max-width:600px;

}



.hero h1{

font-size:55px;

}



.hero span{

color:#38bdf8;

}



.hero h2{

margin:20px 0;

color:#94a3b8;

}



.hero p{

font-size:20px;

line-height:1.6;

}





.profile img{

width:320px;

height:320px;

border-radius:50%;

object-fit:cover;

border:5px solid #38bdf8;

}





.btn{

display:inline-block;

margin-top:30px;

padding:15px 30px;

background:#38bdf8;

color:black;

border-radius:30px;

text-decoration:none;

font-weight:bold;

}





section{

padding:80px 10%;

}



.heading{

text-align:center;

font-size:40px;

margin-bottom:40px;

}




.text{

font-size:20px;

line-height:1.8;

text-align:center;

}





.cards{
display:flex;

justify-content:center;

gap:30px;

flex-wrap:wrap;

}



.card{

background:#1e293b;

padding:30px;

width:300px;

border-radius:20px;

transition:.3s;

}



.card:hover{

transform:translateY(-10px);

background:#334155;

}



.large{

width:60%;

margin:auto;

}





.skills{

display:flex;

justify-content:center;

flex-wrap:wrap;

gap:20px;

}



.skills span{

background:#38bdf8;

color:black;

padding:15px 25px;

border-radius:30px;

font-weight:bold;

}





#contact{

text-align:center;

}



#contact a{

color:#38bdf8;

}





footer{

text-align:center;

padding:20px;

background:#000;

}




@media(max-width:800px){


.hero{

flex-direction:column;

text-align:center;

}


nav ul{

display:none;

}


.hero h1{

font-size:40px;

}


}

.certificate-card a{

text-decoration:none;

color:#38bdf8;

}


.certificate-card a:hover{

color:white;

}


/* Internship */


.internship-card a{

text-decoration:none;

color:#38bdf8;

}


.internship-card a:hover{

color:white;

}


.internship-card{

width:400px;

}
```

## OUTPUT

![alt text](<image/Screenshot 2026-07-25 114756.png>)
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
