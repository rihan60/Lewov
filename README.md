<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LEWOV - Premium Streetwear</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: #f5e9dc;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      background: #2c1b0e;
      padding: 20px 40px;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      animation: slideDown 1s ease;
    }
    @keyframes slideDown {
      from { transform: translateY(-100%); }
      to { transform: translateY(0); }
    }
    header h1 {
      font-size: 2rem;
      letter-spacing: 2px;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1552374196-c4e7ffc6e126') center/cover no-repeat;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.8);
      text-align: center;
      padding: 0 20px;
      animation: fadeIn 2s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .hero h2 {
      font-size: 3.5rem;
      background: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 10px;
    }
    .slider {
      background: #000;
      color: #fff;
      overflow: hidden;
      white-space: nowrap;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    .slider-text {
      display: inline-block;
      padding: 15px 0;
      font-weight: 600;
      font-size: 1rem;
      animation: marquee 20s linear infinite;
    }
    @keyframes marquee {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      padding: 40px;
    }
    .product {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .product:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
    .product img {
      width: 100%;
      height: 320px;
      object-fit: cover;
    }
    .product h3 {
      margin: 10px;
    }
    .product select {
      margin: 10px auto;
      padding: 5px;
    }
    .product button {
      background: #2c1b0e;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-bottom: 20px;
      cursor: pointer;
      border-radius: 5px;
    }
    .categories, .about, .contact {
      padding: 60px 40px;
      background: #fff;
    }
    .categories h2, .about h2, .contact h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .categories-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .category {
      background: #f5e9dc;
      border: 1px solid #d6c5b2;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      min-width: 180px;
    }
    .about p {
      max-width: 800px;
      margin: auto;
      text-align: center;
      line-height: 1.6;
    }
    .contact form {
      max-width: 600px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
    .contact input, .contact textarea {
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact button {
      width: 150px;
      align-self: center;
      background: #2c1b0e;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #2c1b0e;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>LEWOV</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#categories">Categories</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="slider">
    <div class="slider-text">
      New Drop Available Now — Black Signature Hoodie | White Oversized Tee | Classic Full Sleeve — Shop Fast Before Sold Out!
    </div>
  </div>

  <section class="hero" id="home">
    <h2>Own the Look. Rule the Street.</h2>
  </section>

  <section class="products" id="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x300.png?text=Street+Hoodie" alt="Product 1">
      <h3>Street Hoodie</h3>
      <select>
        <option>Size: S</option>
        <option>Size: M</option>
        <option>Size: L</option>
      </select>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x300.png?text=Urban+Tee" alt="Product 2">
      <h3>Urban Tee</h3>
      <select>
        <option>Size: M</option>
        <option>Size: L</option>
        <option>Size: XL</option>
      </select>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x300.png?text=Denim+Jacket" alt="Product 3">
      <h3>Denim Jacket</h3>
      <select>
        <option>Size: L</option>
        <option>Size: XL</option>
      </select>
      <button>Add to Cart</button>
    </div>
  </section>

  <section class="categories" id="categories">
    <h2>Shop by Category</h2>
    <div class="categories-grid">
      <div class="category">Hoodies</div>
      <div class="category">T-Shirts</div>
      <div class="category">Jackets</div>
      <div class="category">Accessories</div>
      <div class="category">Limited Edition</div>
    </div>
  </section>

  <section class="about" id="about">
    <h2>About Lewov</h2>
    <p>Lewov is your destination for premium urban streetwear. Our collection is designed to empower confidence and individuality through fashion. We believe every outfit should tell a story — make yours bold.</p>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 LEWOV. All rights reserved.</p>
  </footer>
</body>
</html>
