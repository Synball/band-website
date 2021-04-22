<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8" />
	<link rel="Stylesheet" href="tfk.css">
	<title>Demos</title>
		<script src="http://code.jquery.com/jquery-2.1.4.min.js"></script>
<script>
    $(function(){
        $('a').each(function(){
            if ($(this).prop('href') == window.location.href) {
                $(this).addClass('active'); $(this).parents('li').addClass('active');
            }
        });
    });
</script>
</head>
<body>

<header id="header-background"> 
	<h1 style="font-size:8vw;">Demos</h1>
	
	<nav id="horizontal">
	<a href="https://www.apple.com" target="_blank">iTunes</a>
	<a href="https://www.spotify.com" target="_blank">Spotify</a>
	<a href="https://soundcloud.com/thefamilyknife" target="_blank">Soundcloud</a>
	</nav>
</header>

<main>

<nav class="sidenav">
	<a href="index.md">Home</a>
	<a href="reviews.html">Reviews</a>
	<a href="demos.html">Demos</a>
	<a href="albums.html">Albums</a>
</nav>

<br><br>

<table style="width:80%" class="center">
		<tr>
			<th id="th01" colspan="3"></th>
		</tr>
		<tr>
			<th>Title</th>
			<th>Writer</th>
			<th>Play</th>
		</tr>
		<tr>
			<td id="td01">Hackeysack</td>
			<td id="td01">Steve Synnott</td>
			<td> <audio controls>
  				<source src="hackeysack.wav" type="audio/wav">
				Your browser does not support the audio element.
				</audio></td>
		</tr>
				<tr>
			<td id="td01">2-4-1 at Linekars</td>
			<td id="td01">Bren McGinley</td>
			<td> <audio controls>
  				<source src="2-4-1 at Linekars.wav" type="audio/wav">
				Your browser does not support the audio element.
				</audio></td>
		</tr>
	</table>

</body>
</html>
