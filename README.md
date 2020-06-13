<!doctpe html>
<html lang ="en">
<head>
	 <meta charset="utf-8">
	 <title>module2</title>
<style>
	h2{
		text-align: center;
		box-sizing: border-box;
		border: 20px;
	}

.container{
	width: 95%
	overflow: hidden;
	background: skyblue;
	margin: 20px auto;
	padding: 20px 0px;
}

.container ul{
	padding: 0px;
	margin: 0px;
}
.container ul li{
	list-style: none;
	float: left;
	width: 20%;
	height: 300px;
	background: red;
	margin: 40px 30px 0px 50px;
	box-sizing: border-box;
	border: 2px solid white;
}
.container ul li:hover{
	opacity: 0.9/
}
.container ul li: title hover{
	background: blue;
	color:black;
}


.container ul li  .title{
	width: 100%;
	height: 50px;
	line-height: 50px;
	background: blue;
	text-align: right;
}


@media screen and (max-width: 1250px){
	.container ul li{
		width: 40%;
		margin-left: 50px;
	}
}

 @media screen and (max-width: 750px){
 	.container{
 		width: 100%
 		padding: 0px;
 	}


 	.container ul li{
 		float: none;
 		width: 90%;
 		margin: 40px auto;
 	}
 }
</style>
</head>
<body>
	<h2>BOX MODEL</h2>
	<div class="container">
		<ul>
			<li> <div class="title">header</div><p>i am here for such kind of information</p></li>
			<li> <div class="title">header</div><p>i am here for such kind of information</p> </li>
			<li> <div class="title">header</div><p>i am here for such kind of information</p> </li>
		</ul>
	</div>
</body>
</html>
