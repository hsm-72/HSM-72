<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Merch Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffffff;
      color: #222;
      margin: 0;
      padding: 0;
    }

    header {
      padding: 2rem;
      text-align: center;
      background-color: #f4f4f4;
      border-bottom: 1px solid #ddd;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.1rem;
      color: #666;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    .product {
      border: 1px solid #eee;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.02);
    }

    .product img {
      width: 100%;
      height: auto;
      max-height: 250px;
      object-fit: cover;
      border-radius: 4px;
      margin-bottom: 1rem;
    }

    .product h3 {
      margin: 0.5rem 0;
      font-size: 1.3rem;
    }

    .product p {
      color: #666;
      font-size: 0.95rem;
    }

    .product .price {
      font-weight: bold;
      margin: 0.5rem 0;
    }

    .product .buy-btn {
      display: inline-block;
      padding: 0.5rem 1rem;
      background-color: #222;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-size: 0.9rem;
      margin-top: 0.5rem;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #aaa;
      background: #f9f9f9;
      border-top: 1px solid #eee;
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Merch Store</h1>
    <p>Clean. Minimal. Authentic. Grab your gear below.</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/400x300" alt="T-Shirt">
      <h3>Placeholder T-Shirt</h3>
      <p>Premium cotton tee with a placeholder design.</p>
      <div class="price">$25.00</div>
      <a href="#" class="buy-btn">Buy with Venmo</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/400x300" alt="Mug">
      <h3>Placeholder Mug</h3>
      <p>Ceramic mug with placeholder artwork. Coffee not included.</p>
      <div class="price">$15.00</div>
      <a href="#" class="buy-btn">Buy with Venmo</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/400x300" alt="Sticker Pack">
      <h3>Sticker Pack</h3>
      <p>Set of 5 vinyl stickers with placeholder designs.</p>
      <div class="price">$8.00</div>
      <a href="#" class="buy-btn">Buy with Venmo</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/400x300" alt="Hoodie">
      <h3>Placeholder Hoodie</h3>
      <p>Comfy hoodie to keep you warm and mysterious.</p>
      <div class="price">$45.00</div>
      <a href="#" class="buy-btn">Buy with Venmo</a>
    </div>
  </section>

  <footer>
    © 2025 Your Merch Store. All rights reserved.
  </footer>

</body>
</html>
