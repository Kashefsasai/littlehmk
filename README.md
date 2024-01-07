<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LITTLE HMK - Your Private Brand</title>
<style>
body {
font-family: 'Helvetica Neue', Arial, sans-serif;
margin: 0;
padding: 0;
background-color: #f8f8f8;
color: #333;
line-height: 1.6;
}

header {
background-color: #333;
color: #fff;
padding: 1em;
text-align: center;
box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

nav {
display: flex;
justify-content: center;
margin-top: 10px;
}

nav a {
text-decoration: none;
color: #fff;
padding: 10px 15px;
margin: 0 10px;
border-radius: 4px;
transition: background-color 0.3s ease;
}

nav a:hover {
background-color: #555;
}

section {
max-width: 800px;
margin: 20px auto;
padding: 20px;
background-color: #fff;
border-radius: 8px;
box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
color: #333;
margin-bottom: 20px;
}

.product-category {
margin-bottom: 30px;
}

ul {
list-style: none;
padding: 0;
}

ul li {
margin-bottom: 10px;
}

form {
display: grid;
grid-template-columns: 1fr 1fr;
gap: 20px;
margin-top: 20px;
}

label {
display: block;
margin-bottom: 5px;
color: #555;
}

input, select {
width: 100%;
padding: 10px;
border: 1px solid #ccc;
border-radius: 4px;
font-size: 14px;
}

button {
background-color: #333;
color: #fff;
padding: 15px;
border: none;
border-radius: 4px;
cursor: pointer;
font-size: 16px;
transition: background-color 0.3s ease;
}

button:hover {
background-color: #555;
}

footer {
text-align: center;
padding: 1em;
background-color: #333;
color: #fff;
position: fixed;
bottom: 0;
width: 100%;
box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1);
}
</style>
</head>
<body>
<header>
<h1>LITTLE HMK - Your Private Brand</h1>
<nav>
<a href="#products">Products</a>
<a href="#payment">Payment Options</a>
<!-- Add more navigation links as needed -->
</nav>
</header>

<section id="products">
<h2>Product Categories</h2>
<div class="product-category">
<h3>Home Accessories</h3>
<ul>
<li>Throw Pillows</li>
<li>Decorative Vases</li>
<!-- Add more specific home accessories here -->
</ul>
</div>
<div class="product-category">
<h3>Electronics</h3>
<ul>
<li>Smartphones</li>
<li>Laptops</li>
<!-- Add more specific products here -->
</ul>
</div>
<!-- Add more product categories as needed -->
</section>

<section id="payment">
<h2>Payment Options</h2>
<ul>
<li> Credit Card</li>
<li> PayPal</li>
<!-- Add more payment options as needed -->
</ul>
</section>

<section id="order-form">
<h2>Place an Order</h2>
<form action="/submit-order" method="post">
<label for="product">Product:</label>
<select id="product" name="product">
<option value="pillows">Throw Pillows</option>
<option value="vases">Decorative Vases</option>
<!-- Add more home accessory options as needed -->
</select>

<label for="quantity">Quantity:</label>
<input type="number" id="quantity" name="quantity" min="1" required>

<label for="payment-method">Payment Method:</label>
<select id="payment-method" name="payment-method">
<option value="credit-card">Credit Card</option>
<option value="paypal">PayPal</option>
<!-- Add more payment options as needed -->
</select>

<button type="submit">Place Order</button>
</form>
</section>

<footer>
<p>&copy; 2024 LITTLE HMK. All rights reserved.</p>
</footer>
</body>
</html>
