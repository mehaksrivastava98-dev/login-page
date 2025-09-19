<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<title></title>
	<style>
		
		h2{
			color: white;
		}
		body{
			
			height: 600px;
			
			background: url(file:///C:/Users/DELL-PC/Desktop/desktopimage.jpg);
			background-position: center;
			background-repeat: no-repeat;

					}
		form{
			border-radius:100px;
			
			text-align:center;
			color: white;
			font-size:25px;
			
		}
		#btn{
			border-radius: 40px;
			font-size:30px;
			text-transform: uppercase;
			
			border-style: dotted;
			margin: 10px 0;
			cursor: pointer;
			border-color: black;
			color: darkorange;
		}
		.container{
			width: 400px;
			height: 400px;
			background: rgba(0, 30, 40, 1.5);
			border-radius: 40px;
			
			align-items: center;
			justify-content: center;
			border:10px solid red;
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%,-50%);
		}

	</style>
</head>
<body>
	<div class="container">
	<h2 align="center"><u>login page</u></h2>
	<form>
		User-name:<input type="text" name="r" placeholder="User-name"><br><br>
		Password:<input type="password" name="l" placeholder="Password"><br><br>
		<p><input type="checkbox">Remember me
			<a href="file:///C:/Users/DELL-PC/Desktop/w3css/reconformation.html?s=rw3t44&b=rw3t44">forget password</a></p>
				<input id="btn" type="submit" value="login">
				<p>don't have an  account?
					<a  href="#">register</a></p>


	</form>
</div>
</body>
</html>
