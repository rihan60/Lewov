update_textdoc = {
  "id": "683896f520348191ab313f2730e2ddfc",
  "update_regex": ".*",
  "new_text": """<!DOCTYPE html>
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
      background: #d2b48c;
      color: #333;
    }
    header {
      background: #4b2e05;
      padding: 20px 40px;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      animation: slideDown 1s ease;
      box-shadow: 0 2px 10px rgba(0,0,0,0.3);
    }
    @keyframes slideDown {
      from { transform: translateY(-100%); }
      to { transform: translateY(0); }
    }
    header h1 {
      font-size: 2.5rem;
      font-weight: 700;
      font-style: italic;
      letter-spacing: 3px;
      font-family: 'Poppins', sans-serif;
      cursor: default;
      text-shadow: 2px 2px 5px #000;
      user-select: none;
    }
    nav a {
      color: white;
      margin-left: 25px;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1rem;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #f3c677;
      text-shadow: 0 0 5px #f3c677;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1521334884684-d80222895322?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      height: 75vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.85);
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
      font-weight: 700;
      margin-bottom: 10px;
      font-family: 'Poppins', sans-serif;
      letter-spacing: 2px;
      animation: glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow {
      from {
        text-shadow: 0 0 5px #f3c677, 0 0 10px #f3c677;
      }
      to {
        text-shadow: 0 0 20px #f3c677, 0 0 30px #f3c677;
      }
    }
    .hero p {
      font-size: 1.3rem;
      max-width: 600px;
      margin: 0 auto;
      font-weight: 400;
      font-style: italic;
      letter-spacing: 1px;
      animation: fadeInText 4s ease forwards;
      opacity: 0;
    }
    @keyframes fadeInText {
      to { opacity: 1; }
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      padding: 50px 40px;
      background: #f7e9d2;
    }
    .product {
      background: #fff8f0;
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 6px 15px rgba(0,0,0,0.15);
      text-align: center;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      position: relative;
    }
    .product:hover {
      transform: scale(1.07);
      box-shadow: 0 10px 30px rgba(0,0,0,0.25);
      z-index: 10;
    }
    .product img {
      width: 100%;
      height: 320px;
      object-fit: cover;
      border-bottom: 1px solid #d9cbb6;
      animation: float 4s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    .product h3 {
      margin: 15px 10px 10px;
      font-size: 1.5rem;
      font-weight: 600;
      color: #4b2e05;
    }
    .product select {
      margin: 15px auto 20px;
      padding: 8px 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 1rem;
      cursor: pointer;
      background: #f7e9d2;
      transition: border-color 0.3s ease;
    }
    .product select:hover, .product select:focus {
      border-color: #4b2e05;
      outline: none;
    }
    .product button {
      background: #4b2e05;
      color: white;
      border: none;
      padding: 12px 30px;
      margin-bottom: 25px;
      cursor: pointer;
      border-radius: 8px;
      font-weight: 600;
      font-size: 1.1rem;
      transition: background-color 0.3s ease;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    .product button:hover {
      background-color: #6e4b12;
      box-shadow: 0 6px 12px rgba(0,0,0,0.35);
    }
    .contact {
      padding: 60px 40px;
      background: #fff8f0;
      box-shadow: inset 0 0 15px #d9cbb6;
    }
    .contact h2 {
      text-align: center;
      font-size: 2.5rem;
      color: #4b2e05;
      margin-bottom: 25px;
      font-weight: 700;
      font-family: 'Poppins', sans-serif;
      text-shadow: 1px 1px 2px #d9cbb6;
    }
    .contact form {
      max-width: 650px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
    .contact input, .contact textarea {
      padding: 15px 12px;
      margin: 10px 0;
      border: 1px solid #d9cbb6;
      border-radius: 8px;
      font-size: 1.1rem;
      font-family: 'Poppins', sans-serif;
      transition: border-color 0.3s ease;
    }
    .contact input:focus, .contact textarea:focus {
      outline: none;
      border-color: #4b2e05;
      box-shadow: 0 0 8px #4b2e05;
    }
    .contact button {
      width: 180px;
      align-self: center;
      background: #4b2e05;
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 700;
      font-size: 1.2rem;
      margin-top: 15px;
      box-shadow: 0 5px 10px rgba(0,0,0,0.3);
      transition: background-color 0.3s ease;
    }
    .contact button:hover {
      background-color: #6e4b12;
      box-shadow: 0 7px 15px rgba(0,0,0,0.45);
    }
    footer {
      background: #4b2e05;
      color: white;
      text-align: center;
      padding: 22px 15px;
      font-weight: 600;
      font-size: 1rem;
      box-shadow: 0 -2px 8px rgba(0,0,0,0.3);
      user-select: none;
    }
    .slider {
      background: #3b2303;
      color: #f3c677;
      overflow: hidden;
      white-space: nowrap;
      box-shadow: 0 4px 10px rgba(0,0,0,0.25);
      font-weight: 600;
      font-size: 1.1rem;
      padding: 12px 0;
      letter-spacing
