# teachingfrontend
Starter folder to teach html css and javascript

Images to use

<img src="http://c1.staticflickr.com/9/8450/8026519634_f33f3724ea_b.jpg ">

<img src="http://c2.staticflickr.com/8/7218/7209301894_c99d3a33c2_h.jpg ">

<img src="http://c2.staticflickr.com/8/7231/6947093326_df216540ff_b.jpg"> 

<img src="http://c1.staticflickr.com/9/8788/17367410309_78abb9e5b6_b.jpg">

<img src="http://c2.staticflickr.com/6/5814/20700286354_762c19bd3b_b.jpg ">

<img src="http://c2.staticflickr.com/6/5647/21137202535_404bf25729_b.jpg ">

<img src="http://c2.staticflickr.com/6/5588/14991687545_5c8e1a2e86_b.jpg"> 

<img src="http://c2.staticflickr.com/4/3888/14878097108_5997041006_b.jpg"> 

<img src="http://c2.staticflickr.com/8/7579/15482110477_0b0e9e5421_b.jpg">



<!DOCTYPE html>
<html>
  <head>
  	<link rel="stylesheet" href="css/style.css" type="text/css" />
    <title>Lake Tahoe</title>
  </head>
<body> 
    <header id="top" class="main-header">
      <span>Journey through the Sierra Nevada Mountains</span>
      <h1>Lake Tahoe, California</h1>
    </header>
    
<div class="primary-content t-border">
    <p>
      Lake Tahoe is one of the most breathtaking attractions located in California. It's home to a number of ski resorts, summer outdoor recreation, and tourist attractions. Snow and skiing are a significant part of the area's reputation.
    </p>
    <a href="#">Find out more</a>
    
    <h2>Check out all the Wildlife</h2>
    
	<p>As spawning season approaches the fish acquire a humpback and protuberant jaw. After spawning they die and their carcasses provide a feast for gatherings of <a href="#">mink</a>, <a href="#">bears</a>, and <a href="#">Bald eagles</a>.</p>
	<a href="#">See the Wildlife</a>
</div> 

<div class="secondary-content t-border">
<h3>From Tents to Resorts</h3>
 <p>Lake Tahoe is full of wonderful places to stay. You have the ability to sleep in the outdoors in a tent, or relax like a king at a five star resort. Here are our top three </p>
<ul>
	<li><a href="#">Lake Tahoe Resort Hotel</a></li>
	<li><a href="#">South Lake Tahoe Resorts</a></li>
	<li><a href="#">Tahoe Ski Resort Lodging</a></li>
</ul> 
<div>
<footer id="main-footer" class="t-border">
	<p>All rights reserved to the state of <a href="#">California</a>.</p>
	<a href="#top">Back to top &raquo;</a>
</footer>
<!--<img src="http://c1.staticflickr.com/9/8450/8026519634_f33f3724ea_b.jpg " width="400px" height="215px">-->
<!--<img src="http://c1.staticflickr.com/9/8450/8026519634_f33f3724ea_b.jpg " width="400px" height="215px">-->
</body>
</html>











body{
   color: #878787; 
   margin: 0;  
}

header{
    background-color: orange;
}

h1{ 
    font-size: 5.625em; 
    color: white;
    text-transform: uppercase;
}

h2{
    font-size: 53px;
}

h3{
    font-size: 20px;  
    color: rgb(255,169,73);
}

#main-footer{
    padding-top: 60px;
    padding-bottom: 60px;
    border-bottom: solid 10px #ffa949;
    background-color: lightblue;
    text-align: center;
}

.primary-content{
    text-align: center
}

.secondary-content{
  
}

.main-header {
    color: #ffa949;
}

.t-border{
     border-top: 2px solid gray;
}

.title{ 
    color: white;
  font-size: 1.625em;
}

ol li{
    /*background-color: tomato;*/
    color: #878787;
    margin-bottom: 5px;
}

a:visited {
color :orange;
}

a:hover{
    color : forestgreen;
    
}

.primary-content, .secondary-content{
    width: 60%;
} 

.primary-content, .main-header{
    text-align: center;
}
