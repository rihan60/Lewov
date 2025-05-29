<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lewov - Premium Streetwear</title>
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
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #111;
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
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1612423284934-7016d437c4b3') center/cover no-repeat;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.7);
      text-align: center;
      padding: 0 20px;
      animation: fadeIn 2s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .hero h2 {
      font-size: 3rem;
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
      transition: transform 0.3s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      height: 300px;
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
      background: #111;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-bottom: 20px;
      cursor: pointer;
      border-radius: 5px;
    }
    .contact {
      padding: 40px;
      background: #fff;
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
      background: #111;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
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
  </style>
</head>
<body>
  <header>
    <h1>LEWOV</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="slider">
    <div class="slider-text">
      New Drop Available Now — Black Signature Hoodie | White Oversized Tee | Classic Full Sleeve — Shop Fast Before Sold Out!
    </div>
  </div>

  <section class="hero">
    <h2>Own the Look. Rule the Street.</h2>
  </section>

  <section class="products" id="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x300.png?text=Black+Signature+Hoodie" alt="Black Signature Hoodie">
      <h3>Black Signature Hoodie</h3>
      <select>
        <option>Size: S</option>
        <option>Size: M</option>
        <option>Size: L</option>
        <option>Size: XL</option>
      </select>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x300.png?text=White+Oversized+Tee" alt="White Oversized Tee">
      <h3>White Oversized Tee</h3>
      <select>
        <option>Size: S</option>
        <option>Size: M</option>
        <option>Size: L</option>
        <option>Size: XL</option>
      </select>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x300.png?text=Full+Sleeve+Classic" alt="Classic Full Sleeve">
      <h3>Classic Full Sleeve</h3>
      <select>
        <option>Size: S</option>
        <option>Size: M</option>
        <option>Size: L</option>
        <option>Size: XL</option>
      </select>
      <button>Add to Cart</button>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2 style="text-align:center; margin-bottom:20px">Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Lewov. All Rights Reserved.</p>
  </footer>
</body>
</html>
