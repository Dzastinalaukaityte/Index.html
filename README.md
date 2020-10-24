# Index.html
Work in progress website.

(THE HTML CODE FOR THE WEBSITE)


<!DOCTYPE html>
<html lang=”en”>
<meta charset = "UTF-8" />
<head>
<title>My Very Basic Homepage</title>
<link rel="stylesheet" type="text/css" href="website/css/style.css">
<body>
<header class="page-header">
	<h1>Curriculum Vitae</h1>
	<a href="images/harry-styles-watermelon-sugar.jpg" width="250" height="300">
		<img src="images/harry-styles-watermelon-sugar.jpg">
	<nav>
		<ul>
			<li><a href="#">About Me</a></li>
			<li><a href="#">Education</a></li>
			<li><a href="#">Hobbies</a></li>
			<li><a href="#">Favourite Meal</a></li>
		</ul>
	</nav>
</header>

<main>
	<article>
		<h2>WELCOME</h2>
		<P>Welcome to my very first basic website. It is still a work in progress but soon it will look really good.</P>
	</article>
<h2>About Me</h2>
<p>My name is Dzastina. I am 18 years old. I have brown hair and blue eyes. My favourite colour is red and green. I have two pets, a dog and a hamster. My dogs name is Lola. She has brown eyes and black fur. She likes to sleep a lot but can be very energetic at the same time. My hamsters name is Squishy. He has light brown fur and a white stripe that goes down his back. He is very playful and energetic.</p>
<h2>Education</h2>
<p>I went to a secondary school called St.Dominics College. It was a big secondary school with nearly 1000 people attending it every day. It was all girls school. It was originally a convent set up by 6 nuns who came from Australia. It has been modernised and now is run as a secondary school. My three favourite subjects were:<ul><li>Geography</li><li>Maths</li><li>Home Economics</li></ul></p>
<h2>Hobbies</h2>
<p>I play a lot of games such as Amoung Us, Call Of Duty, GTA5 and many more with my friends. I also listen to music 24/7 and I love to cycle my bike.</p>
	<li><a href="https://store.steampowered.com/app/945360/Among_Us/">A site to play games.</a></li>
	<a href="images/amoungus.jpg" width="250" height="120">
		<img src="images/amoungus.jpg">
	</a>	
	<li><a href="https://www.spotify.com/ie/">A site to listen to music.</a></li>
	<a href="images/spotify.jpg" width="250" height="120">
		<img src="images/spotify.jpg">
	</a>	

	<h2>Favourite Meal</h2>
<p>My favourite meal is ramen noodles.</p>
<ul>
	<li><a href="https://student.computing.dcu.ie/~laukaid2/FavouriteMeal.html">A ramen noodle recipe.</a></li>
</ul>
</main>

<footer>
	<p>You can contact me by email: dzastina.laukaityte@mail.dcu.ie</p>
</footer>
</body>
</html>



(THE STYLE.CSS FOR THE WEBSITE)


html, body {
  margin: 0;
  padding: 0;
}

html {
  font-size: 15px;
  background-color: lightgrey;
}

body {
  width: 100%;
  min-width: 800px;
}

h1, h2 {
  font-family: 'Roboto', sans-serif;
  color: black;
  text-align: center;
}

p, input, il {
  font-family: 'Roboto', sans-serif;
  color: black;
}

h1 {
  font-size: 3rem;
  text-align: center;
  padding-top: 65px;
  padding-left: 175px;
}

h2 {
  font-size: 2rem;
  text-align: left;
}

p, il {
  font-size: 1.6 rem;
  line-height: 1.5;
}

header {
  margin-bottom: 10px;
  display: flex;
  flex-flow: row wrap;
}

body > * {
  padding: 1%
}

main, header, nav, article, footer, section {
  background-color: #03f98d;
} 

h1 {
  flex: 5;
  text-transform: uppercase;
  height: 100px;
}

header img {
  display: block;
  height: 250px;
  width: 200px;
  padding-top: 15px;
  padding-right: 15px;
}

nav {
  height: 50px;
  flex: 100%;
  display: flex;
  background-color: #03f98d;
}

nav ul {
  padding: 0;
  list-style-type: none;
  flex: 2;
  display: flex;
  background-color: #03f98d;
}

nav li {
  display: inline;
  text-align: center;
  flex: 1;
  background-color: #03f98d;
}

nav a, nav span {
  display: inline-block;
  font-size: 2rem;
  height: 1rem;
  line-height: 0.7;
  text-transform: uppercase;
  text-decoration: none;
  color: black;
  background-color: #03f98d;
}


article, section {
  flex: 4;
  background-color: #03f98d;
}

footer {
  margin-top: 10px;
  background-color: #03f98d;
}
