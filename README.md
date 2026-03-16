# think
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coffee Haven Cafe</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: Arial, sans-serif;
}

body{
background:#f8f5f2;
color:#333;
}

/* Navbar */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 60px;
background:#3e2723;
color:white;
}

nav h1{
font-size:26px;
}

nav ul{
display:flex;
list-style:none;
gap:25px;
}

nav a{
text-decoration:none;
color:white;
font-weight:bold;
}

/* Hero Section */

.hero{
height:90vh;
background:url("https://images.unsplash.com/photo-1509042239860-f550ce710b93") center/cover no-repeat;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
}

.hero-content{
background:rgba(0,0,0,0.5);
padding:40px;
border-radius:10px;
}

.hero h2{
font-size:48px;
margin-bottom:10px;
}

.hero p{
margin-bottom:20px;
}

.btn{
background:#d2691e;
color:white;
padding:12px 25px;
border:none;
border-radius:5px;
text-decoration:none;
font-weight:bold;
}

/* About */

.about{
padding:60px 10%;
text-align:center;
}

.about h2{
margin-bottom:20px;
font-size:32px;
}

/* Menu */

.menu{
padding:60px 10%;
background:white;
}

.menu h2{
text-align:center;
margin-bottom:40px;
}

.menu-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:30px;
}

.menu-item{
background:#f4f4f4;
padding:20px;
border-radius:10px;
text-align:center;
}

.menu-item img{
width:100%;
border-radius:10px;
margin-bottom:10px;
}

/* Contact */

.contact{
padding:60px 10%;
text-align:center;
}

footer{
background:#3e2723;
color:white;
text-align:center;
padding:20px;
}

/* Mobile */

@media(max-width:768px){

nav{
flex-direction:column;
gap:10px;
}

.hero h2{
font-size:32px;
}

}
</style>
</head>

<body>

<nav>
<h1>Coffee Haven</h1>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#menu">Menu</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">
<div class="hero-content">
<h2>Fresh Coffee Everyday</h2>
<p>Experience the best coffee and desserts in town</p>
<a href="#menu" class="btn">View Menu</a>
</div>
</section>

<section class="about" id="about">
<h2>About Our Cafe</h2>
<p>
Welcome to Coffee Haven — a cozy place where coffee lovers gather.
We serve freshly brewed coffee, delicious desserts, and a relaxing
environment to enjoy with friends.
</p>
</section>

<section class="menu" id="menu">
<h2>Popular Menu</h2>

<div class="menu-grid">

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1511920170033-f8396924c348">
<h3>Espresso</h3>
<p>₹120</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93">
<h3>Cappuccino</h3>
<p>₹180</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085">
<h3>Latte</h3>
<p>₹200</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1563805042-7684c019e1cb">
<h3>Chocolate Cake</h3>
<p>₹150</p>
</div>

</div>
</section>

<section class="contact" id="contact">
<h2>Visit Us</h2>
<p>📍 Main Street, Your City</p>
<p>📞 +91 98765 43210</p>
<p>🕒 Open Daily: 8 AM – 10 PM</p>
</section>

<footer>
<p>© 2026 Coffee Haven Cafe | All Rights Reserved</p>
</footer>

</body>
</html>
