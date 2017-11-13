# Web-Design
For Web Design

<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>Float Website</title>

<style>
	body{
		
		background-color: #00C4C4
	}
	h1 {
		background-color: aqua;
		text-align: center;
		border-style:ridge;
		border-width: thick;
		margin-left:  70px;
		margin-right:  70px;
		padding-top: 10px;
		padding-bottom: 10px;
	}
	
	.mainBox {
		/*background-color: yellow;
		width: 1000px;
		float: left;
		padding-bottom: 1000px;
		margin:20px*/
	}
	
	.box1 {
		background-color: yellow;
		width: 400px;

		padding-bottom: 200px;
		border-style: inset;
		border-width:thick;
		margin-top:30px;
		
		
	}
	.color {
		color: #00C4C4;
		
	}
	.divider {
		
		float:left;
		width: 900px;
		
		padding-bottom: 50px;
		border-style: inset;
		border-width:thick;
		
		
	}
	.box2 {
		background-color: blue;
		width: 50%;
		padding-bottom: 200px;
		border-style: inset;
		border-width:thick;
		margin-top:30px;
		margin-left: 450px;
		
	}
	.box3 {
		background-color: red;
		width: 400px;
		float: left;
		padding-bottom: 200px;
		border-style: inset;
		border-width:thick;
		margin-top:30px;
		/*margin-bottom:30px;*/
	}
	.img1 {
		float: right;
		background-color: yellow;
		width: 400px;

		
		border-style: inset;
		border-width:thick;
		
		
		
	}
	
	</style>

</head>



<body>
<div class="mainBox">
  <h1>Main Characters from Oturan</h1>
  <div class="box1">
    <h3 classs="color">Oturan</h3>
  </div>
<img class="img1"src="Final Images/Screen Shot 2017-11-08 at 8.29.25 AM.png" width="400" height="600" alt="Oturan">


<div class="box2">  
<h3 class="color">Allen</h3>
</div>

<div class="box3">  
<h3 class="color">Wilson</h3>
</div>

	</div>

	



</body>
</html>





//second peace of code

<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>float site</title>

<style>
	.headerBox {
		
		text-align: center;
		color: #343434;
		border: solid;
		border-color: #343434;
		font-size: 70px;
		background-color: #BFBFBF;
		width: 100%;
		margin-top: 20px;
		margin margin-bottom: 60px;
		
	}
	.mainContainer {
		width: 1000px;
		margin-right: auto;
		margin-left: auto;
		
	}
	
	body {
		background-color: #1A2855;
		
	}
	.box1 {
		background-color: #bfbfbf;
		border: solid;
		border-color: #343434;
		border-width:thick;
		width: 350px;
		height: 400px;
		margin-top: 30px;
		float: left;
	}       
	
	.box2 {
		background-color: #bfbfbf;
		border: solid;
		border-color: #343434;
		border-width:thick;
		width: 350px;
		height: 400px;
		margin-top: 30px;
		text-align: center;
		float: right;
		
	}
	
	.box3 {
		
		background-color: #bfbfbf;
		border: solid;
		border-color: #343434;
		border-width:thick;
	    width: 350px;
		height: 400px;
		margin-top: 30px;
		float: left;
	}
 
	.red {
		color: #A81010;
		text-align: center;
		font-size: 40px;
		
	}
	.picright {
		height: 400px;
		width: 600px;
		border: solid;
		border-color: #343434;
		border-width:thick;
		float: right;
		margin-top: 30px;
		
	}
	
	.picleft {
		height: 400px;
		width: 600px;
		border: solid;
		border-color: #343434;
		border-width:thick;
		float: left;
		margin-top: 30px;
		
	}
	
	
	</style>
</head>

<body>
<div class="mainContainer">

<div class="headerBox">
<p>Movies of the 21st Century</p>
	</div>
	
<div class="box1">
	<p class="red">Avengers</p>
	
</div>
<img class="picright" src="avengers-spider-man1.jpg">

<div class="box2">
	<p class="red">Star Wars</p>
</div>
<img class="picleft" src="seven_starwars3d_06.jpg">

<div class="box3">
	<p class="red">Jurrasic park</p>
</div>
<img class="picright" src="../../Documents/Unnamed Site 2/dinosaur.png">
	</div>
</body>
</html>

