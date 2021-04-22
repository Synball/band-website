<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8" />
	<link rel="Stylesheet" href="tfk.css">
	<title>TFK - Albums</title>
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
	<h1 style="font-size:8vw;">Albums</h1>
	
	<nav id="horizontal">
	<a href="https://www.apple.com" target="_blank">iTunes</a>
	<a href="https://www.spotify.com" target="_blank">Spotify</a>
	<a href="https://soundcloud.com/thefamilyknife" target="_blank">Soundcloud</a>
	</nav>
</header>

<main>

<nav class="sidenav">
	<a href="index.md">Home</a>
	<a href="reviews.md">Reviews</a>
	<a href="demos.md">Demos</a>
	<a href="albums.md">Albums</a>
</nav>

<section>
<br>
<h2>The Family Knife (2019)</h2>
	<ol>
	<li>The Sea
	<li>Trojan Horse
	<li>Leave Me Sleeping
	<li>Yeah, Maybe
	<li>Golden Soundz
	<li>Lightheaded
	<li>Making It Rain
	<li>Under The Blue Atlas Cedar
	<li>You've Changed
	<li>Lotus
	<li>Don't Want To Give Up</li>
	</ol>
</section>

<hr>

<section>
<br>
<h2>Singles</h2>
	<ul class="player">
	<li> <a href="2 for 1 at Linekars Mastered.wav" target="_blank">2 for 1 at Linekars</a></li> 
	</ul>
</section>

</main>

</body>
</html>
