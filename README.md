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
      animation: fadeIn 2s ease-in-out;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-style: italic;
      color: #ccc;
    }
    .hero {
      background: linear-gradient(135deg, #111, #333);
      color: white;
      text-align: center;
      padding: 60px 20px;
      animation: slideUp 1.5s ease-out;
    }
    .hero h2 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 30px;
      animation: fadeIn 2s ease-in-out;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s ease;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .product h3 {
      margin: 10px 0 5px 0;
    }
    .options {
      margin-bottom: 10px;
    }
    .options select {
      margin: 5px;
      padding: 5px;
    }
    .add-to-cart {
      background-color: #111;
      color: white;
      padding: 10px;
      border: none;
      cursor: pointer;
      margin-bottom: 15px;
      border-radius: 5px;
    }
    .add-to-cart:hover {
      background-color: #444;
    }
    .contact-form {
      padding: 30px;
      background-color: #fff;
      margin: 30px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      animation: fadeIn 2s ease-in-out;
    }
    .contact-form h2 {
      text-align: center;
    }
    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact-form button {
      padding: 10px 20px;
      background-color: #111;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .contact-form button:hover {
      background-color: #333;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideUp {
      from { transform: translateY(40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
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

  <section class="hero">
    <h2>New Collection 2025</h2>
    <p>Trendy. Bold. You.</p>
  </section>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Black+Signature+Hoodie" alt="Black Signature Hoodie">
      <h3>Black Signature Hoodie</h3>
      <div class="options">
        <select>
          <option>Select Size</option>
          <option>Small</option>
          <option>Medium</option>
          <option>Large</option>
        </select>
        <select>
          <option>Select Color</option>
          <option>Black</option>
          <option>Gray</option>
        </select>
      </div>
      <button class="add-to-cart">Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Summer+Vibe+T-shirt" alt="Summer Vibe T-shirt">
      <h3>Summer Vibe T-shirt</h3>
      <div class="options">
        <select>
          <option>Select Size</option>
          <option>Small</option>
          <option>Medium</option>
          <option>Large</option>
        </select>
        <select>
          <option>Select Color</option>
          <option>White</option>
          <option>Yellow</option>
        </select>
      </div>
      <button class="add-to-cart">Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Classic+Full+Sleeve" alt="Lewov Classic Full Sleeve">
      <h3>Lewov Classic Full Sleeve</h3>
      <div class="options">
        <select>
          <option>Select Size</option>
          <option>Small</option>
          <option>Medium</option>
          <option>Large</option>
        </select>
        <select>
          <option>Select Color</option>
          <option>Blue</option>
          <option>Black</option>
        </select>
      </div>
      <button class="add-to-cart">Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x250.png?text=Oversized+Tee" alt="Streetwear Oversized Tee">
      <h3>Streetwear Oversized Tee</h3>
      <div class="options">
        <select>
          <option>Select Size</option>
          <option>Small</option>
          <option>Medium</option>
          <option>Large</option>
        </select>
        <select>
          <option>Select Color</option>
          <option>Beige</option>
          <option>Green</option>
        </select>
      </div>
      <button class="add-to-cart">Add to Cart</button>
    </div>
  </section>

  <section class="contact-form">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Lewov. All rights reserved.</p>
  </footer>
</body>
</html>
