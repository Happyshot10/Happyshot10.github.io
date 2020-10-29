 	<!DOCTYPE html>
	<html>
	<head>
		<title>Login</title>
		<link rel="icon" href="Hi.png">
	</head>
	<body>
		
		<center class="hello mepopo">
	<form name="form1">
		<p>Username</p>
		<input type="text" name="Username">


		<p>Password</p>
		<input type="text" name="Pword">

		<br><br>
		<button type="button" onclick="logincheck()">Submit</button>

	</form>
	</center>

	<h1 id="Loggedin"></h1>


	<script type="text/javascript">
		
		var http = 


		function funoneo() {
			window.location.replace("hello site.html")
		} 

		function logincheck() {
			
			if(document.forms["form1"]["Username"].value == "Kovfam" && document.forms["form1"]["Pword"].value == "Kovam"){
				

				window.open('mailto:happyshot1010@gmail.com?subject=We are on our way&body=The Kovacs are on there way')
				window.location.replace("Kov.html");
				return
				}else{
					document.getElementById("Loggedin").innerHTML = "ACCESS DENIED";
				}

			if(document.forms["form1"]["Username"].value == "Brook" && document.forms["form1"]["Pword"].value == "Bfam"){
				window.open('mailto:happyshot1010@gmail.com?subject=We are on our way&body=The Brookmans are on there way')
				window.location.replace("Brookmans.html");
				return

			}
			else {
				document.getElementById("Loggedin").innerHTML = "ACCESS DENIED";
			}
				if(document.forms["form1"]["Username"].value == "Ms.Burke" && document.forms["form1"]["Pword"].value == "gym"){
				window.open('mailto:happyshot1010@gmail.com?subject=I am on our way&body=Ms.Burke is on her way')
				window.location.replace("gym.html");
				return

				}else {
					document.getElementById("Loggedin").innerHTML = "ACCESS DENIED";
				}
		}


	</script>
	</body>
	</html>


     

 
