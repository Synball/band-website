<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8" />
	<link rel="Stylesheet" href="tfk.css">
	<title></title>
</head>
<script>

function Login(form) { username = new Array("Synball","Bren","Mono","Kenny")
password = new Array("Synball","Bren","Mono","Kenny"); page="index.html"; 

if (form.username.value == username[0] && form.password.value == password[0] || form.username.value == username[1] && form.password.value == password[1] ||
form.username.value == username[2] && form.password.value == password[2] || form.username.value == username[3] && form.password.value == password[3] ||
form.username.value == username[4] && form.password.value == password[4] || form.username.value == username[5] && form.password.value == password[5] ||

form.username.value == username[6] && form.password.value == password[6] || form.username.value == username[7] && form.password.value == password[7] ||

form.username.value == username[8] && form.password.value == password[8] || form.username.value == username[9] && form.password.value == password[9]) 
{ self.location.href = page; } 
else { alert("You got the password wrong you muppet.\nGive it another go there."); form.username.focus(); } return true; }

</script> 

</head> 

<body bgcolor="#eeeeee"> 

<header id="header-background"> 
	<h1 style="font-size:8vw;">The Family Knife</h1>
	
	<nav id="horizontal">
	<a href="https://www.apple.com" target="_blank">iTunes</a>
	<a href="https://www.spotify.com" target="_blank">Spotify</a>
	<a href="https://soundcloud.com/thefamilyknife" target="_blank">Soundcloud</a>
	</nav>
</header>

<form> 
<br> 
<main>
	<h5>Username: 
	<input type="text" name="username" 
	style="background:#bfbfbf;color:#212121;border-color:#212121;" onFocus="this.style.background = '#ffffff';"

	onBlur="this.style.background = '#bfbfbf';"> 
	<br> Password: 
	<input type="password" name="password" style="background:#bfbfbf;color:#212121;border-color:#212121;" onFocus="this.style.background = '#ffffff';"	onBlur="this.style.background = '#bfbfbf';"> 
	<br> 
	<input type="button" value="Login" onClick="Login(this.form);" style="background:#bfbfbf;color:#000000;border-color:#212121;" onMouseOver="this.style.color =	'#404040';" onMouseOut="this.style.color = '#000000';" onFocusr="this.style.color = '#404040';" onBlur="this.style.color = '#000000';">
	</h5> 
</main> 
</form> 

</body> 
</html>
