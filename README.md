<!DOCTYPE html>
<html>
  <head>
    <title>Code Lodge Delaware</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
   <link href="https://fonts.googleapis.com/css?family=Pacifico" rel="stylesheet">
   <meta name="viewport" content="width=device-width">
    <!-- Internal style -->
   <!-- <style>
    p{
     font-size : 20px;
     font-weight: bold;
   }
   h1{
    font-size: 90px;
   }
  header{
    background-color: orange;}
    </style> -->
  </head>
  <body>
  <!-- Inline style -->
  <!-- <body style="background-color: orange">  -->
    <header id="#top" class="main-header">
      <span class="title">Journey through the Mountains of code</span>
     <!--   <span class="title">Second Journey through the Mountains of code</span> -->
     <!--<button id="button">The bUtton</button>-->
      <!--<h1 style="color:white;">Lake Tahoe, California</h1>-->
      <h1>Code Lodge, DE</h1>
    </header>
    <div class="primary-content t-border">
    <p>
     Code Lodge is one of the most breathtaking attractions located in the USA. It's home to a number coders, hobbyst, and tourist . Coding and hacking are a significant part of the area's reputation.
    </p>
    <a class="callout" href="#">Find out more</a>
    <div class="wildlife">
    <h2>Check out all the Wildlife</h2>
        <p>
          As spawning season approaches the coders acquire six packs of beer and a whole lot of coffee. Upon arrival they usually fire up their laptops instead of observing the <a href="#">mink</a>, <a href="#">bears</a>, and <a href="#">Bald eagles</a>.
        </p>
    </div>
      <a class="callout" href="#">See the Wildlife</a>
      </div>
      
      <div class="secondary-content t-border group">
      <div class="resorts">
          <img src="https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/mtn-landscape.jpg" alt="resort">
      <!--<img src="img/resort.jpg" alt="Resort">-->
      <h3>From Tents to Resorts</h3>
      <p>
        Coders Lodge is full of wonderful places to stay. You have the ability to sleep in the outdoors in a tent, or relax like a king at a five star codingresort. Our top four resorts:
      </p>
      <ul>
          <li><a href="#hotels">Code Resort Hotel</a></li>
          <li><a href="#resorts">South Code Resorts</a></li>
          <li><a href="#lodging">CodersSki Resort Lodging</a></li>
           <li><a href="#lake">South Lake Tahoe Resorts</a></li>
      </ul> 
      </div>
      <div class="tips"> 
      <img src="https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/resort.jpg">
      <!--<img src="http://c2.staticflickr.com/8/7218/7209301894_c99d3a33c2_h.jpg "  width="372px" height="214.5px;">-->
      <!--<img src="img/mtn-landscape.jpg" alt="Mountain Landscape"> -->
      <h3>Pack Accordingly</h3>
      <p>
        One of most important things when it comes to traveling through the great outdoors is packing accordingly. Here are a few tips:
      </p>
        <ol class="orderedList">
            <li>Bring extra battery packs</li>
            <li>Pack sunscreen</li>
            <li>Bring lots of coffee just in case</li>
            <li>Pack light</li>
        </ol>
      </div>
    </div>

    <footer id="main-footer" class="t-border">
      <p>All rights reserved to <a href="http://www.zipcodewilmington.com">Zip Code Wilmington</a>.</p>
      <a href="#top">Back to top &raquo;</a>
    </footer>
    <!--<script type="text/javascript" src="script.js"></script>-->
  </body>
</html>

<!--https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/bear.jpg-->
<!--https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/mountains.jpg-->
<!--https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/mtn-landscape.jpg-->
<!--https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/resort.jpg-->



**{
	margin: 0;
	padding : 0;
	color: red;
}*/

/**{
	border: solid 2px;
}*/
*{
	box-sizing: border-box;
}

body{
	/*text-align: center;*/
	color: #878787;
	margin: 0;
	font-size: 1em;
	font-family: Helvetica, Arial, sans-serif;

}

.main-header{
	background-color: #ffa949;
	height: 850px;
	padding-top: 170px;
	background-image: url('https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/mountains.jpg');
	/*width: 960px;*/
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center;
}

ol li{
	/*background-color: tomato;*/
	color: #878787;
	margin-bottom: 5px;
}

h1{
	/*font-size: 72px;
	color: white;*/
	/*font-size: 90px;*/
	font-size: 5.625rem;
	color: white;
	text-transform: uppercase;
	font-weight: normal;
	font-family: 'Pacifico', cursive;
	text-shadow: 5px 8px 0 #222; /* horizontal, vertical, blur, color */
	/*transition-property: color, background-color, border;*/


/* NOT NEEDED	-webkit-transition-duration: 2s;
    -moz-transition-duration: 2s;
    -o-transition-duration: 2s;* NOT NEEDED/
    
 /*   transition-duration: 2s;*/
	/*transition-delay: .2s;*/
	/*transition-timing-function: ease-out;*/

}


/*h1:hover{*/
/*	color: orange;*/
/*	background-color: lightblue;*/
/*	border: solid 3px orange;*/

/*}*/


h2{
	font-size: 3.3125em; /* 53px/16 */
	text-decoration: none;
	font-weight: normal;
	margin-bottom: .5em;
}

h3{
	font-size: 1.25em; /* 20px/16 */;
	/*color: #48525c;*/
	color: rgb(255,169,73);
	margin-bottom: 1.7em;
}

.title{
	color: white;
	/*font-size: 26px;*/
	font-size: 1.625rem;
	
}
.primary-content, 
.secondary-content{
	/*width: 80%;*/
	width: 75%;
	margin: auto;
	padding-left: 50px;
	padding-right: 50px;
	max-width: 900px;
}

.primary-content, 
.main-header{
	/*border: 3px solid red;*/
	text-align: center;
}
.secondary-content{
	/*border: 3px solid red;*/
/*	border-top:2px solid gray;*/
padding-top: 80px;
padding-bottom: 70px;

}
.t-border{
		border-top:2px solid lightgrey;
}
.wildlife{
	color: white;
	background-color: #434a52;
	padding: 100px 120px 100px 120px;
	/*border: 10px solid #ffa949;*/
	border-top: 10px solid #ffa949;
	margin: 105px 0 60px 0;
	background-image: url(https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/bear.jpg);
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
	box-shadow: 15px 15px 10px #222;
	border-radius: 50px;
	
	/*transition-property: background-image,transform;*/
	/*transition-duration: 2s;*/
	/*transition-delay: .5s;*/
	/*transition-timing-function: ease-in;*/
	
	overflow: hidden;

}

.wildlife:hover{
	background-image: url('https://raw.githubusercontent.com/MikailaAkeredolu/finalcodelecture/master/img/mountains.jpg');
	/*transform: scale(1.1);*/
	/*transform: scale(1.1, 2.2);*/
	/*transform: translateY(100px);*/
	/*transform: translate(100px, 50px);*/
}

img{
	max-width: 100%;
	margin-bottom: 20px;
	/*transform: rotate(25deg);*/ /*EXPERIMENT*/
	/*transition-property:transform;*/
	/*transition-property: transform, border;*/
	/*transition-duration: .3s;*/
	/*transition-delay: .2s;*/

}

img:hover{
	/*transform: rotate(1turn);*/
/*	border: 5px solid black;*/
}

a:link{
	color: lightblue;
	text-decoration: none;
}

a:visited{
	color:orange;
}

a:hover{
	color: rgba(255,169,73, .4);
}
a:active{
	color: yellow;
}

/*a:focus{
	color: white;
	background-color: orange;
}*/
.callout{
	font-size: 1.25em;
	border-bottom: 3px solid orange;
	padding: 0 9px 3px 9px;
	margin-top: 20px;
	display: inline-block;
}

.resorts, 
.tips{
	width: 46.5%;
}

.resorts{
	float: left;
}

.tips{
	float: right;
}


.group:after{
content: "";
display: table;
clear: both;
}

#main-footer{
	padding-top: 60px;
	padding-bottom: 60px;
	border-bottom: solid 10px #ffa949;
	text-align: center;
	background-color: lightblue;

}

ul{
	list-style-type: square;
	padding-left: 0;
	margin-left: 0;
}

ol{
	list-style-type: decimal-leading-zero;
	padding-left: 0;
	margin-left: 0;
}


footer p{
	font-style:italic; 
	/*font-size: 20px;*/
	/*color: white;
	background-color: blue;*/
}




/*Media Queries*/

@media(max-width: 960px){
	body{
		background-color: royalblue;
	}
	p{
		color: white;
	}
}

/* 480 px*/
@media(max-width:480px ){
	body{
		background-color: darkred;
	}
}

/*when between 481 and 700 px display these styles*/

@media(min-width: 481px) and (max-width: 700px){
	body{
		background-color: seagreen;
	}
	.wildlife{
		padding: 100px 80px 100px 80px;
		box-shadow: none;
		margin: 55px 0 30px 0;
	}

	/*	.resorts, .tips{
		float: none;
		width: 100%;
	}*/
}

@media(max-width: 1024px){
	.primary-content, .secondary-content{
		width: 90%;
	}
}

@media(max-width: 768px){
	.primary-content, .secondary-content{
		width: 100%;
		padding: 20px;
		border: none;
	}
	.main-header{
		max-height: 380px;
		padding-top: 10px;
		padding-left: 25px;
		padding-right: 25px;
		padding-bottom: 0px;

	}
	.title{
		display: none;
	}

	h1{
		font-size: 3rem;
		text-shadow: 3px 4px 0 #222;
	}

	h2{

	font-size: 1.5em; /* 53px/16 */
	text-decoration: none;
	font-weight: normal;
	margin-bottom: .5em;

	}

	p{
		font-size: .9em;
	}

	/*ul{	*/
	/*font-size: .9em;*/
	/*list-style-type: none;*/
	/*padding-left: 0;*/
	/*margin-left: 0;*/
	/*}*/

	/*ol{*/
	/*	font-size: .9em;*/
	/*	list-style-type: none;*/
	/*	padding-left: 0;*/
	/*    margin-left: 0;*/
	/*}*/

	/*.secondary-content a{*/
	/*	color: white;*/
	/*}*/

	/*.secondary-content ol li {*/
	/*	color: white;*/
	/*}*/

	/*.wildlife{*/
	/*	padding: 50px 60px 50px 60px;*/
	/*	box-shadow: none;*/
	/*	margin: 55px 0 30px 0;*/
	/*}*/

	/*	.resorts, .tips{*/
	/*	float: none;*/
	/*	width: 100%;*/
	/*}*/

	/*#main-footer{*/
	/*	padding: 20px 0;*/
	/*}*/

}

/*#toggleList{*/
/*	padding: 10px;*/
/*	margin: 10px;*/
/*	color: white;*/
/*	font-weight: bold;*/
/*	background-color: yellow;*/
/*}*/







