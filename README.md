<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Endorsement</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="hero">
        <h1>Paper bag Product</h1>
        <p>The best product to improve your life!</p>
        <p>Product that can reduce plastic waste!</p>
        <a href="#buy-now" class="btn">Buy Now</a>
    </header>

    <section class="product-details">
        <img src="Screenshot_2025-03-14-17-16-01-06_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Product Image" height="100" width="100">
        <div class="info">
            <h2>Why Choose This Product?</h2>
            <p>High-quality, reliable, and affordable.</p>
            <p>very easy to carry necessary things.</p>
            <p>foldable bag.</p>
            <p> can lift 10kg inside.</p>
            <p>can dispose and re-use.</p>
            <p>very useful to bring food and any belongings.</p>
            <p class="price">₱29.99</p>
            <a href="#buy-now" class="btn">Order Now</a>
        </div>
    </section>

    <section class="reviews">
        <h2>Customer Reviews</h2>
        <p>⭐⭐⭐⭐⭐ "This product changed my life!" - Happy Customer
        </p>
        <p> 
        ⭐⭐⭐⭐ "very easy to carry! - Customer
        </p>
        
       <p>
         ⭐⭐⭐⭐ Can bring wherever i go - Customer</p>
    </section>

    <section class="faq">
        <h2>FAQs</h2>
        <p><strong>Q:</strong> Is this product useful?</p>
        <p><strong>A:</strong> Absolutely! Very effiecient to use.</p>
    </section>

    <section class="contact">
        <h2>Contact Us</h2>
        <p>Email: Jandeansereno2@gmail.com</p>
        <p> phone number: 09817353117
        </p>
        <p> location at: Nabitasan, Iloilo City</p>
    </section>

    <footer>
        <p>© 2025 Amazing Product. All rights reserved.</p>
    </footer>
</body>
</html>
body {
  margin: 0;
}

.game-canvas {
  width: 100%;
  height: 100vw;
  max-width: 500px;
  max-height:500px;
  margin-left: auto;
  margin-right: auto;
}

.keys {
  font-family: 'Lato', sans-serif;
  text-align: center;
  width: 10%;
  padding: 10px;
  box-sizing: border-box;
  height: 10px;
  margin: auto;
}

.up {
  position: relative;
  top: -4px;
}

.chevron::before {
  border-style: solid;
  border-width: 8px 8px 0 0;
  content: '';
  display: inline-block;
  height: 20px;
  width: 20px;
  top: -10px;
  position: relative;
  transform: rotate(-45deg);
}

.chevron.down::before {
  transform: rotate(135deg);
  top: -22px;
}

.chevron.right::before {
  transform: rotate(45deg);
  top: -18px;
  left: -5px;
}

.chevron.left::before {
  transform: rotate(225deg);
  top: -18px;
  left: 5px;
}

.arr {
  cursor: pointer;
  width: 70px;
  height: 70px;
  text-align: center;
  line-height: 100px;
  background: gray;
  color: white;
  font-size: 50px;
  border-right: 10px solid #ccc;
  border-bottom: 10px solid #ccc;
  border-left: 10px solid #ddd;
  border-top: 10px solid #eee;
  display: inline-block;
  margin: 5px;
  transition: all .05s linear;
  user-select: none;
}

.arr:active {
  background: #555;
}

#game-container {
  display: flex;
  flex-direction: column;
  background-color: rgba(220, 220, 220, 0.6);
}
console.log('hello world!');
