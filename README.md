<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>White Chocolate | Chocotastic</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#f8f1ea;
}

/* Header */

header{
background:#5a3825;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
box-shadow:0 5px 15px rgba(0,0,0,.15);
position:sticky;
top:0;
z-index:100;
}

.left{
display:flex;
align-items:center;
gap:20px;
}

.cart-btn{
background:#fff;
color:#5a3825;
padding:10px 18px;
border-radius:8px;
text-decoration:none;
font-weight:bold;
transition:.3s;
}

.cart-btn:hover{
background:#f4d7b5;
}

.logo{
height:55px;
width:170px;
background:#ffffff20;
border:2px dashed white;
display:flex;
align-items:center;
justify-content:center;
color:white;
font-size:14px;
}

/* Title */

.title{
text-align:center;
padding:40px 20px 20px;
}

.title h1{
font-size:38px;
color:#5a3825;
}

.title p{
margin-top:10px;
color:#7b5b45;
}

/* Products */

.container{
width:92%;
max-width:1300px;
margin:auto;
padding-bottom:60px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:18px;
overflow:hidden;
box-shadow:0 8px 20px rgba(0,0,0,.12);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.info{
padding:18px;
}

.info h3{
color:#5a3825;
margin-bottom:8px;
}

.price{
font-size:22px;
font-weight:bold;
color:#b06d2b;
margin-bottom:18px;
}

.buttons{
display:flex;
gap:10px;
}

.details,
.addcart{
flex:1;
padding:12px;
border:none;
border-radius:8px;
cursor:pointer;
font-weight:bold;
transition:.3s;
}

.details{
background:#5a3825;
color:white;
}

.details:hover{
background:#432515;
}

.addcart{
background:#e9c8a2;
color:#5a3825;
}

.addcart:hover{
background:#d9ae7c;
}

footer{
margin-top:40px;
padding:25px;
background:#5a3825;
text-align:center;
color:white;
}

</style>

</head>

<body>

<header>

<div class="left">

<a href="cart.html" class="cart-btn">
🛒 Cart
</a>

</div>

<div class="logo">

Your Logo Here

</div>

</header>

<div class="title">

<h1>White Chocolate Collection</h1>

<p>Premium White Chocolates for Every Sweet Moment</p>

</div>

<div class="container">

<div class="products">

<div class="card">
<img src="Classic.jpg">
<div class="info">
<h3>Classic White Chocolate</h3>
<div class="price">৳320</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

<div class="card">
<img src="almond.jpg">
<div class="info">
<h3>Almond White Chocolate</h3>
<div class="price">৳380</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

<div class="card">
<img src="hazelnut.jpg">
<div class="info">
<h3>Hazelnut White Chocolate</h3>
<div class="price">৳400</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

<div class="card">
<img src="vanilla.jpeg">
<div class="info">
<h3>Vanilla White Chocolate</h3>
<div class="price">৳350</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

<div class="card">
<img src="Strawberry.jpeg">
<div class="info">
<h3>Strawberry White Chocolate</h3>
<div class="price">৳420</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

<div class="card">
<img src="cookies.jpeg">
<div class="info">
<h3>Cookies White Chocolate</h3>
<div class="price">৳390</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

<div class="card">
<img src="icaramel.jpeg">
<div class="info">
<h3>Caramel White Chocolate</h3>
<div class="price">৳430</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

<div class="card">
<img src="truffle.jpeg">
<div class="info">
<h3>Premium White Truffle</h3>
<div class="price">৳480</div>
<div class="buttons">
<button class="details">View Details</button>
<button class="addcart">🛒</button>
</div>
</div>
</div>

</div>

</div>

<footer>

© 2026 Chocotastic | Crafted with Love 🍫

</footer>

</body>
</html>
