
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chocolate Details | Chocotastic</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f7efe7;
}

/* Header */

header{
    background:#4e2d1c;
    color:white;
    padding:18px;
    text-align:center;
    font-size:30px;
    font-weight:bold;
    box-shadow:0 5px 15px rgba(0,0,0,.2);
}

/* Main */

.container{
    width:90%;
    max-width:1200px;
    margin:50px auto;
}

.product{
    display:flex;
    gap:40px;
    flex-wrap:wrap;
    background:white;
    padding:30px;
    border-radius:18px;
    box-shadow:0 15px 30px rgba(0,0,0,.12);
}

.product-image{
    flex:1;
}

.product-image img{
    width:100%;
    border-radius:15px;
}

.product-details{
    flex:1;
}

.product-details h1{
    color:#4e2d1c;
    margin-bottom:15px;
}

.price{
    font-size:32px;
    color:#7b3f00;
    font-weight:bold;
    margin-bottom:15px;
}

.rating{
    color:gold;
    font-size:20px;
    margin-bottom:20px;
}

.description{
    color:#555;
    line-height:1.8;
    margin-bottom:30px;
}

.buttons{
    display:flex;
    gap:15px;
}

.buy-btn,
.cart-btn{

    padding:15px 35px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    font-size:17px;
    transition:.3s;

}

.buy-btn{

    background:#6b3e26;
    color:white;

}

.buy-btn:hover{

    background:#4e2d1c;

}

.cart-btn{

    background:#d4a373;
    color:white;

}

.cart-btn:hover{

    background:#b87c4c;

}

/* Similar */

.similar{

    margin-top:60px;

}

.similar h2{

    color:#4e2d1c;
    margin-bottom:25px;

}

.cards{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;

}

.card{

background:white;
padding:15px;
border-radius:15px;
text-align:center;
box-shadow:0 10px 20px rgba(0,0,0,.1);
transition:.3s;

}

.card:hover{

transform:translateY(-8px);

}

.card img{

width:100%;
height:180px;
object-fit:cover;
border-radius:12px;

}

.card a{

text-decoration:none;
color:#4e2d1c;
font-size:18px;
font-weight:bold;
display:block;
margin-top:12px;

}

footer{

margin-top:70px;
background:#4e2d1c;
color:white;
padding:20px;
text-align:center;

}

@media(max-width:768px){

.product{

flex-direction:column;

}

.buttons{

flex-direction:column;

}

}

</style>

</head>

<body>

<header>

🍫 Chocotastic

</header>

<div class="container">

<div class="product">

<div class="product-image">

<img src="https://images.unsplash.com/photo-1549007994-cb92caebd54b?w=900" alt="Chocolate">

</div>

<div class="product-details">

<h1>Belgian Dark Chocolate</h1>

<div class="price">$8.99</div>

<div class="rating">

★★★★★

</div>

<p class="description">

Experience the rich taste of premium Belgian Dark Chocolate made from the finest cocoa beans. Smooth texture, intense chocolate flavor, and a delightful sweetness make every bite unforgettable.

Perfect for gifts, special occasions, or simply satisfying your chocolate cravings.

</p>

<div class="buttons">

<button class="buy-btn">

Buy Now

</button>

<button class="cart-btn">

Add to Cart

</button>

</div>

</div>

</div>

<div class="similar">

<h2>🍫 Similar Chocolates</h2>

<div class="cards">

<div class="card">

<img src="https://images.unsplash.com/photo-1511381939415-e44015466834?w=500">

<a href="milk-chocolate.html">

Milk Chocolate

</a>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1606313564200-e75d5e30476c?w=500">

<a href="white-chocolate.html">

White Chocolate

</a>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1571506165871-ee72a35bc9d4?w=500">

<a href="hazelnut.html">

Hazelnut Chocolate

</a>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1621939514649-280e2ee25f60?w=500">

<a href="caramel.html">

Caramel Chocolate

</a>

</div>

</div>

</div>

</div>

<footer>

© 2026 Chocotastic | Sweetness in Every Bite 🍫

</footer>

</body>
</html>
