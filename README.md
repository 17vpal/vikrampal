# vikrampal
<html>
<head>
<title>
Midterm Home Page
</title>
<link href="midterm.css" rel="stylesheet" type="text/css"/>
 <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
  <div id="sidenavbar" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">Close</a>
  <a href="midterm.html">Home</a>
  <a href="resume.html">Resume</a>
</div>


<span onclick="openNav()"><div class="navthing">Open Index</div></span>
<div class="coolname">Vikram Pal</div>
<div class="welcome"><h3><u>Welcome!</u></h3></div>
<div class="bro">Welcome to my website! My name is Vikram Pal and I'm pleased to introduce you to some of my finest work. On here, you can see a few cool pictures I have taken above in the slideshow. Below you can see
a little bit about who I am and what I like to do. I also have a few projects below that you should feel free to check out and browse at your leisure. Thanks for visiting and I hope you enjoy!</div>
</br>
</br>
</br>


<div class="grey"><img src="midtermp.jpg" style="width:300px;height:455px;" align="right"><u><h3>About Me</u></h3>
<p>I am currenty a freshman at IU. I'm enrolled in 5 classes in my first semester which include:
<ul>
<li>M119 (Calc 1)</li>
<li>Info101 (Intro to Informatics)</li>
<li>BUS-C 104 (Business Presentations)</li>
<li>A101 (Accounting)</li>
<li>ECON 201 (Microeconomics)</li>
</ul>
I am currently double majoring with finance and informatics. I like to play football, basketball, and most of all golf in my free time. I also like to code websites in my free time.
</p>
</div>
</br>
</br>
<h3><div class="welcome"><u>My Projects</u></h3></div>
<div class="project">
<ol>
<li><a href="http://pages.iu.edu/~vpal/i101/index.html">i101 Index Page</a></li>
<ul>
<li>This link leads you to my Index Page for my i101 class, which will have links to all of the projects I have completed in i101. Most of the projects are about features we have learned in class from multiple
programs spanning from HTML to CSS to Python to Javascript.</li>
</ul>
<li><a href="http://pages.iu.edu/~vpal/i101/home.html">Fantasy Football Page</a></li>
<ul>
<li>This website leads you to a personal project. I made a website dedicated to a fantasy football league where I update things such as power rankings and predictions based off statistics that I gather as well as my
own personal analysis. This leads me to conclusions about who I believe is progressing and regressing.</li>
</ul>
<li><a href="https://docs.google.com/document/d/1vZ7Yr_fZMg9WUHXUW_oAjBCGJVntzLGBe2_8XkLhvfs/edit?usp=sharing">Paper on Technoethics</a></li>
<ul>
<li>This final link leads to a project completed in my lecture hall for i101. This is a google drive document that I wrote to express my viewpoint of how technology is seen in my personal interests and in 
the media. For my personal interest, I talk about how golf has advanced a lot over the last 20 years due to tecnhology. Furthermore, I talk about how technology and abstract ideas are expressed in
television and media all the time.</li>
</ul>
</ol>
</div>
</br>
</br>
<div class="footer">
  <p>I certify that the content included in this portfolio/website is my own original work (or is cited accurately) and accurate to my knowledge. Work included which was conducted as part of a team or other group is indicated and attributed as such the other team members are named and a true description of my role in the project is included - Vikram Pal</p>
</div>

<script>
function openNav() {
    document.getElementById("sidenavbar").style.width = "150px";
    document.getElementById("main").style.marginLeft = "150px";
    document.body.style.backgroundColor = "rgba(0,0,0,0.4)";
	var x = document.getElementById("sidenavbar");
	x.style.fontSize = "32px";
	x.style.color = "white";
}

function closeNav() {
    document.getElementById("sidenavbar").style.width = "0";
    document.getElementById("main").style.marginLeft = "0";
    document.body.style.backgroundColor = "white";
}
</script>

</body>
</html>
