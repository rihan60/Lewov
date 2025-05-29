<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lewov - Own the Look</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #111;
    }
    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-style: italic;
      color: #ccc;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 30px;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .product h3 {
      margin: 10px 0;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>LEWOV</h1>
    <p>Own the Look. Rule the Street.</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Black+Signature+Hoodie" alt="Black Signature Hoodie">
      <h3>Black Signature Hoodie</h3>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Summer+Vibe+T-shirt" alt="Summer Vibe T-shirt">
      <h3>Summer Vibe T-shirt</h3>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Classic+Full+Sleeve" alt="Lewov Classic Full Sleeve">
      <h3>Lewov Classic Full Sleeve</h3>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Oversized+Tee" alt="Streetwear Oversized Tee">
      <h3>Streetwear Oversized Tee</h3>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Lewov. All rights reserved.</p>
  </footer>
</body>
</html>
