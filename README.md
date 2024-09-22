 <!DOCTYPE html>
<html lang="en">
<head>

<title> JAHED NST</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #edbcbc;
  padding: 20px;
  text-align: center;
  font-size: 5px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
    text-align: center;
  }
}
</style>
</head>
<body>


<!--Header part start-->
  <header>
    <div class="logo">
      Social Media Analyst  
</div>
    <div class="navber">
        <ul>

            <li><a href="#"> Home</a> </li>
            <li><a href="#">Blog</a></li>
            <li> <a href="#">Services</a>
            <ul>
                <li>marketing</li>
                <li>ads manager</li>
            </ul></li>         
                <li><a href="#">About Us</a></li>
             </ul>
    </div>
</header>
<!--Header part ebd-->
<STYle>
   /*header estet*/ 
   header{
      width:100%;
       
      color: white;
      display: flex;
  }
  .logo {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 25px;
      font-weight:bold;
      margin-left: 10px;
      margin-top: 10px;
      padding: 10px;
      color: #dc1515;
  }
  .navber {
      display: flex;
      justify-content: center;
      align-items: center;
      padding-left: 400px;
  }
  .navber ul{
  list-style: none;
  }
  .navber ul li{
      background-color: #dc1515;
      width: 180px;
      height: 30px;
      line-height: 30px;
      text-align: center;
      float: left;
      color: white;
      font-size: 10px;
      font-weight: bold;
      text-transform: uppercase;
      position: relative;
  }
  .navber ul li a{
       text-decoration: none;
       color: white;
       text-align: center;
       justify-items: center;
       align-items: center;
  }
  .navber ul li :hover{
      background-color: rgb(24, 20, 21);
      transition: all ease-in 0.5s;
  }
  .navber ul ul{
      display: none;
  }
  .navber ul li:hover>ul{
      display: block;
  }
</STYle>
 <main>
  <div class="box 1"></div>
  <div class="box2"></div>
  <div class="box3"></div>

 </main>
  <style>
    main{
      margin: 20;
      padding: 30;
      box-sizing: border-box;
      text-align: center;
background-color: #dc1515;
    
      width: 75%;
      margin: 10px auto;
    }
      /*header end*/ 

  </style>
 


 

<!--img&video -->

 
<img src="digital.png" alt="Trulli" width="400" height="233">
<video width="400" height="233" controls>
  <source src="youtube.mp4" type="video/mp4">
  <source src= "im hgh.jpg" type="video/ogg">
  Your browser does not support the video tag.
</video>
<video width="400" height="233" controls>
  <source src="Blue White Modern Bold Digital Marketing Expert Video.mp4" type="video/mp4">
  <source src= "Blue White Modern Bold Digital Marketing Expert Video.mp4" type="video/ogg">
  Your browser does not support the video tag.
</video>

<!--img&video end -->

<article>
  <h1>About</h1>
 <p>with the insights and capabilities necessary to succeed in the digital landscape. With its cutting-edge features, intuitive interface, and advanced scheduling capabilities, the Social Media Analyst is the ultimate solution for optimizing your online presence. Developed by the esteemed team at Freelancer.com, this innovative tool is the key to unlocking your social media potential and driving impactful results.</p>
</article>
<p style="background-color:hsl(0, 100%, 50%);" class="p2"> with the insights and capabilities necessary to succeed in the digital landscape. With its cutting-edge features, intuitive interface, and advanced scheduling capabilities, the Social Media Analyst is the ultimate solution for optimizing your online presence. Developed by the esteemed team at Freelancer.com, this innovative tool is the key to unlocking your social media potential and driving impactful results.</p>
<style>
  .p2{
    width: 300px;
    height: 400;
  }
</style>
 

 














<!--futer  st -->
  <footer>
    <div class="name">
        <h2>Social Media Analyst at Freelancer.com</h2>
    </div>
    <div class="tax">
        <p>Introducing a comprehensive social media marketing solution that is designed to elevate your business to
            new heights of success. Our dedicated professional is committed to understanding your unique needs and
            providing the most effective assistance to your business. Our services include online marketing
            management, graphic design, and social media management across a range of platforms, including Facebook,
            Instagram, YouTube, and Google My Business, Threads. With a focus on delivering outstanding work and
            quality that exceeds your expectations, we are confident in our ability to help your busin.</p>
    </div>
    <div class="icon">
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa- Youtube"></i>
        <i class="fa-brands fa- instagram"></i>
        <i class="fa-brands fa- linkeding"></i>
    </div>
    <div class="coppy">
        JAHEDNST@GMAIL.COM
    </div>
</footer>
<!--futer end-->
<style>/*futer start */
  footer{
      position: absolute;
      bottom: 0;
      text-align: center;
      background-color: #545151;
      width: 99%;
      color: rgb(14, 14, 14);
  } 
  .name{
      font-family: Arial, Helvetica, sans-serif;
      font-weight: bold;
      font-size: 10px;
  }
  .tax p {
      width: 1200px;
      text-align: center;
      margin: 0 auto;
      position:  relative;
      top: -10px;
      color: #171414;
  }
  .icon i { 
      font-size: 10px;
      position:  relative;
      top: -10px;
      padding: 10px;
  }
  .coppy{
      height: 20px;
      width: 100%;
      background-color: rgb(200, 48, 48);
  }</style>
<main>
<div class="box 1 "></div>



</main>






  </body>
 </html>
