<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ChessMastery Store</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #e0f7fa, #fce4ec);
    }
    header, footer {
      background: linear-gradient(90deg, #1a1a40, #3498db);
      color: #fff;
      text-align: center;
      padding: 30px 20px;
    }
    nav {
      background: #d63031;
      padding: 12px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      font-size: 18px;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ffeaa7;
    }
    .container {
      max-width: 1100px;
      margin: 30px auto;
      padding: 25px;
      background: #ffffff;
      border-radius: 16px;
      box-shadow: 0 6px 16px rgba(0, 0, 0, 0.15);
    }
    h1, h2 {
      color: #2d3436;
    }
    h2 {
      border-bottom: 3px solid #0984e3;
      padding-bottom: 5px;
    }
    .product {
      display: flex;
      margin-bottom: 25px;
      border: 2px solid #dfe6e9;
      border-radius: 14px;
      overflow: hidden;
      background: linear-gradient(to right, #f5f7fa, #dfe6e9);
      transition: transform 0.3s ease;
    }
    .product:hover {
      transform: scale(1.02);
    }
    .product img {
      width: 200px;
      height: auto;
      border-right: 2px solid #dfe6e9;
    }
    .product-details {
      padding: 20px;
    }
    .product-details h3 {
      margin-top: 0;
      color: #6c5ce7;
    }
    .btn {
      display: inline-block;
      padding: 12px 24px;
      background: #00b894;
      color: #fff;
      border: none;
      text-decoration: none;
      border-radius: 8px;
      font-size: 16px;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #019875;
    }
  </style>
</head>
<body>
  <header>
    <h1>ChessMastery Store</h1>
    <p>Unlock your chess potential with premium eBooks and video courses</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#ebooks">eBooks</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="ebooks">
      <h2>eBooks</h2>
      <div class="product">
        <img src="https://via.placeholder.com/200?text=Chess+Openings" alt="Chess eBook 1">
        <div class="product-details">
          <h3>Mastering Chess Openings</h3>
          <p>A comprehensive guide to the most powerful opening strategies in chess.</p>
          <a class="btn" href="#">Buy for $9.99</a>
        </div>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200?text=Chess+Tactics" alt="Chess eBook 2">
        <div class="product-details">
          <h3>Chess Tactics for Beginners</h3>
          <p>Learn essential tactics to dominate your games with ease and precision.</p>
          <a class="btn" href="#">Buy for $7.99</a>
        </div>
      </div>
    </section>

    <section id="courses">
      <h2>Courses</h2>
      <div class="product">
        <img src="https://via.placeholder.com/200?text=Fundamentals" alt="Chess Course 1">
        <div class="product-details">
          <h3>Complete Chess Fundamentals</h3>
          <p>A step-by-step video course for beginners to intermediate players to build strong foundations.</p>
          <a class="btn" href="#">Enroll for $19.99</a>
        </div>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200?text=Strategy+Planning" alt="Chess Course 2">
        <div class="product-details">
          <h3>Advanced Strategy & Planning</h3>
          <p>Master the art of planning ahead and long-term positional play like a pro.</p>
          <a class="btn" href="#">Enroll for $24.99</a>
        </div>
      </div>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 ChessMastery. All rights reserved.</p>
  </footer>
</body>
</html>
