<!------Here html page starts  ------->
<!DOCTYPE html>
<html lang="en">


<!-------------------------Header starts here -------------------------------->
<head>
<title>About me</title>
<subtitle>Arun Kumar Pandey</subtitle>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
  
<style>

* {box-sizing: border-box}

.container {
  width: 100%;
  background-color: #ddd;
}

.skills {
  text-align: right;
  padding-top: 10px;
  padding-bottom: 10px;
  color: white;
}

.python {width: 70%; background-color: #1e60a6;}
.machine {width: 35%; background-color: #904231;}
.gnuplot  {width: 50%; background-color: #7A9EA5;}
.html {width: 45%; background-color: #808080;}
.fortran {width: 55%; background-color:  #86C729;}
.swift {width: 30%; background-color: #F2BA7B;}

  
/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}


/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #30460c;
  color: white;
}


/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: rgb(21, 10, 22);
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned links */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<!---------------------- Header eds here --------------------------------------->


<!------Here main body starts  ------->
<body>
<div class="header">
    <h1>This is header</h1>
    <img src="yourimage.png" alt="Trulli" width="200" height="150"> 
      <!---src - Specifies the path to the image
      alt - Specifies an alternate text for the image-->
    <p>This is header subtitle.</p>
  </div>

  <div class= “header-image”>
  </div>

  <div class="navbar">
    <a href="https://github.com/arunsinp">GitHub</a>
    <a href="#">Your codes</a>
    <a href="#">Photos</a>
    <a href="#" class="right">Link for something</a>
  </div>
  
 <div class="row">
    <div class="side">

<h2>About Me</h2>
This html file is a format file for the website designing.

<!-------     
![image](https://user-images.githubusercontent.com/15100077/212930031-efc55dd5-9151-4f4a-8322-53a45c7d58ee.png)
----->

<img src="https://user-images.githubusercontent.com/15100077/212930031-efc55dd5-9151-4f4a-8322-53a45c7d58ee.png" alt="Arun"> 

<p><img src="somephotos.jpg" alt="Trulli" width="300" height="200"></p>
Hi there! My name is Arun Kumar Pandey and I am a postdoctoral fellow at University of Delhi. 
I have always been passionate about math and physics and have been 
working in this field for almost 6 years. In my free time, I enjoy 
hiking, reading classic books and watching movies. I am excited to meet new people and learn from their
experiences and perspectives. I believe that we can all learn and grow from each 
other, and I am always open to hearing new ideas and approaches. I am a hard-working
and reliable individual, and I am committed to delivering high-quality work in 
everything I do. Thank you for taking the time to get to know me a little bit better.
<!-------Add your photos here, if you wish -->
</div>
<div class="main">
     <p>
     <h1>Technical Skills<h1/>

<h3>Programming Skills</h3>

<p>Python</p>
<div class="container">
  <div class="skills python"></div>
</div>

<p>Machine-learning</p>
<div class="container">
  <div class="skills machine"></div>
</div>

<p>Gnuplot</p>
<div class="container">
  <div class="skills gnuplot"></div>
</div>

<p>Fortran</p>
<div class="container">
  <div class="skills fortran"></div>
</div>

<p>HTML</p>
<div class="container">
  <div class="skills html"></div>
</div>

<p>SWIFT</p>
<div class="container">
  <div class="skills swift"></div>
</div>

 <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}

.container {
  width: 100%;
  background-color: #ddd;
}

.skills {
  text-align: right;
  padding-top: 10px;
  padding-bottom: 10px;
  color: white;
}

.GIT {width: 65%; background-color: #0909F8;}
.mathematica  {width: 80%; background-color: #7707f7;}
.excel {width: 70%; background-color: #5C1E69;}
.SQL {width: 70%; background-color: #2196F3;}
.Powerbi {width: 60%; background-color: #f44336;}
.tableau  {width: 50%; background-color:#66E6FF;}
.latex  {width: 90%; background-color: #332390;}
</style>
</head>
<body>

<h3>Tools and Softwares </h3>

<p>GIT</p>
<div class="container">
  <div class="skills GIT"></div>
</div>

<p>Mathematica</p>
<div class="container">
  <div class="skills Mathematica"></div>
</div>

<p>Latex</p>
<div class="container">
  <div class="skills latex"></div>
</div>

<p>MS Excel</p>
<div class="container">
  <div class="skills excel"></div>
</div>

<p>SQL</p>
<div class="container">
  <div class="skills SQL"></div>
</div>

<p>Power BI</p>
<div class="container">
  <div class="skills Powerbi"></div>
</div>

<p>Tableau</p>
<div class="container">
  <div class="skills tableau"></div>
</div>

  
  <div class="footer">
    <h4>This website is managed by yourname or email id</h4>
  </div>
<!------Here main body ends  ------->
</body>
<!---------------------------Here html page ends ---------------------------------->
