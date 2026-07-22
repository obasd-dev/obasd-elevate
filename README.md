
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ObasD Elevate | Luxury Hotel</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f8f8f8;
color:#333;
}

header{
position:fixed;
top:0; /* Added this to fix the header to the top */
left:0; /* Added this to ensure it aligns perfectly with the left edge */
width:100%;
background:rgba(0,0,0,.7);
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
z-index:999;
backdrop-filter:blur(8px);
}

.logo{
font-size:30px;
font-weight:bold;
color:#D4AF37;
}

nav a{
text-decoration:none;
margin-left:25px;
color:#fff;
font-weight:500;
transition:.3s;
}

nav a:hover{
color:#D4AF37;
}

.hero{
height:100vh;
background:url('https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=1800&q=80') center/cover;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
position:relative;
}

.hero::before{
content:"";
position:absolute;
left:0;
top:0;
width:100%;
height:100%;
background:rgba(0,0,0,.55);
}

.hero-content{
position:relative;
z-index:1;
max-width:700px;
}

.hero h1{
font-size:65px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
line-height:1.7;
margin-bottom:35px;
}

.btn{
display:inline-block;
padding:15px 40px;
background:#D4AF37;
color:white;
text-decoration:none;
font-weight:bold;
border-radius:50px;
transition:.3s;
}

.btn:hover{
background:#b68e18;
transform:translateY(-4px);
}

section{
padding:90px 10%;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:60px;
color:#222;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;
}

.about img{
width:100%;
border-radius:15px;
}

.about p{
font-size:18px;
line-height:1.8;
}

.rooms{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.room{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 10px 30px rgba(0,0,0,.08);
transition:.4s;
}

.room:hover{
transform:translateY(-10px);
}

.room img{
width:100%;
height:250px;
object-fit:cover;
}

.room-content{
padding:25px;
}

.room h3{
margin-bottom:15px;
}

.price{
color:#D4AF37;
font-size:24px;
font-weight:bold;
margin-top:15px;
}

.features{
background:#111;
color:white;
}

.feature-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
text-align:center;
}

.feature{
padding:30px;
background:#222;
border-radius:15px;
}

.feature h3{
margin:20px 0;
color:#D4AF37;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:15px;
transition:.4s;
}

.gallery img:hover{
transform:scale(1.05);
}

.testimonials{
background:#fafafa;
}

.testimonial-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.card{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.contact{
background:#111;
color:white;
text-align:center;
}

.contact p{
margin:15px 0;
font-size:18px;
}

footer{
background:#000;
color:white;
text-align:center;
padding:25px;
}

@media(max-width:900px){

header{
padding:20px;
flex-direction:column;
}

nav{
margin-top:15px;
}

.about{
grid-template-columns:1fr;
}

.hero h1{
font-size:45px;
}

}

</style>

</head>

<body>

<header>

<div class="logo">ObasD Elevate</div>

<nav>

<a href="#">Home</a>

<a href="#about">About</a>

<a href="#rooms">Rooms</a>

<a href="#gallery">Gallery</a>

<a href="#contact">Contact</a>

</nav>

</header>

<section class="hero">

<div class="hero-content">

<h1>Luxury Beyond Comfort</h1>

<p>
Experience elegance, premium hospitality, breathtaking suites,
fine dining, and unforgettable moments at ObasD Elevate Hotel.
</p>

<a href="#" class="btn">Book Your Stay</a>

</div>

</section>

<section id="about">

<h2 class="title">Welcome to ObasD Elevate</h2>

<div class="about">

<img src="https://images.unsplash.com/photo-1551882547-ff40c63fe5fa?auto=format&fit=crop&w=1200&q=80">

<div>

<p>

ObasD Elevate is designed for travelers seeking luxury,
comfort, and exceptional hospitality.

From elegant suites and rooftop dining to a relaxing spa
and infinity pool, every stay is carefully crafted to
deliver unforgettable memories.

Whether you're visiting for business or leisure,
our dedicated team ensures every guest enjoys
world-class service.

</p>

</div>

</div>

</section>

<section id="rooms">

<h2 class="title">Luxury Rooms</h2>

<div class="rooms">

<div class="room">

<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=900&q=80">

<div class="room-content">

<h3>Deluxe Room</h3>

<p>Elegant comfort with premium furnishings and city views.</p>

<div class="price">$150 / Night</div>

</div>

</div>

<div class="room">

<img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267?auto=format&fit=crop&w=900&q=80">

<div class="room-content">

<h3>Executive Suite</h3>

<p>Luxury suite with lounge, workspace and king-size bed.</p>

<div class="price">$260 / Night</div>

</div>

</div>

<div class="room">

<img src="https://images.unsplash.com/photo-1566665797739-1674de7a421a?auto=format&fit=crop&w=900&q=80">

<div class="room-content">

<h3>Presidential Suite</h3>

<p>Ultimate elegance featuring panoramic views and premium amenities.</p>

<div class="price">$450 / Night</div>

</div>

</div>

</div>

</section>

<section class="features">

<h2 class="title" style="color:white;">Hotel Amenities</h2>

<div class="feature-grid">

<div class="feature">

<h3>🏊 Infinity Pool</h3>

<p>Relax with stunning skyline views.</p>

</div>

<div class="feature">

<h3>🍽 Fine Dining</h3>

<p>International cuisine prepared by expert chefs.</p>

</div>

<div class="feature">

<h3>💆 Luxury Spa</h3>

<p>Rejuvenate your body and mind.</p>

</div>

<div class="feature">

<h3>🏋 Fitness Center</h3>

<p>Modern gym open 24 hours.</p>

</div>

</div>

</section>

<section id="gallery">

<h2 class="title">Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1542314831-068cd1dbfeeb?auto=format&fit=crop&w=900&q=80">

<img src="https://images.unsplash.com/photo-1445019980597-93fa8acb246c?auto=format&fit=crop&w=900&q=80">

<img src="https://images.unsplash.com/photo-1512918728675-ed5a9ecdebfd?auto=format&fit=crop&w=900&q=80">

<img src="https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=900&q=80">

</div>

</section>

<section class="testimonials">

<h2 class="title">Guest Reviews</h2>

<div class="testimonial-grid">

<div class="card">

★★★★★

<p style="margin-top:15px;">

One of the finest hotels I've ever stayed in.
Excellent hospitality and luxurious rooms.

</p>

<strong>- Sarah M.</strong>

</div>

<div class="card">

★★★★★

<p style="margin-top:15px;">

Amazing experience. Beautiful views,
friendly staff and exceptional service.

</p>

<strong>- David A.</strong>

</div>

<div class="card">

★★★★★

<p style="margin-top:15px;">

Highly recommended for vacations and
business trips alike.

</p>

<strong>- Michael T.</strong>

</div>

</div>

</section>

<section id="contact" class="contact">

<h2 class="title" style="color:white;">Contact Us</h2>

<p>📍 Luxury Avenue - Omisanjana, Ado - Ekiti, Nigeria</p>

<p>📞 +234 916 319 0591</p>

<p>✉ reservations@obasdelevate.com</p>

<br>

<a href="#" class="btn">Reserve Your Room</a>

</section>

<footer>

© 2026 ObasD Elevate Hotel. All Rights Reserved.

</footer>

</body>
</html>
