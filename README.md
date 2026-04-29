<!DOCTYPE html>
<html>
<head>
  <title>Almo Overseas</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

  <style>
    body {font-family: 'Poppins', sans-serif; margin:0; color:#333;}
    
    header {
      background:white;
      padding:15px;
      border-bottom:1px solid #eee;
    }

    nav {
      display:flex;
      justify-content:space-between;
      align-items:center;
      max-width:1100px;
      margin:auto;
    }

    nav img {height:50px;}

    nav a {
      text-decoration:none;
      margin-left:20px;
      color:#0a2540;
      font-weight:500;
    }

    .hero {
      background:url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1');
      background-size:cover;
      background-position:center;
      color:white;
      text-align:center;
      padding:120px 20px;
    }

    .hero h1 {font-size:40px; margin-bottom:10px;}
    .hero p {font-size:18px;}

    .btn {
      display:inline-block;
      margin-top:20px;
      padding:12px 25px;
      background:#0a2540;
      color:white;
      text-decoration:none;
      border-radius:5px;
    }

    .section {
      max-width:1100px;
      margin:60px auto;
      padding:20px;
      text-align:center;
    }

    .cards {
      display:flex;
      gap:20px;
      flex-wrap:wrap;
      margin-top:30px;
    }

    .card {
      flex:1;
      min-width:250px;
      padding:25px;
      border:1px solid #eee;
      border-radius:8px;
    }

    footer {
      background:#0a2540;
      color:white;
      text-align:center;
      padding:25px;
      margin-top:50px;
    }
  </style>
</head>

<body>

<header>
  <nav>
    <img src="logo.png" alt="Almo Overseas Logo">
    <div>
      <a href="#">Home</a>
      <a href="#">Destinations</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </div>
  </nav>
</header>

<div class="hero">
  <h1>Study Abroad with Confidence</h1>
  <p>Guiding students to opportunities in the UK, Turkey, and beyond</p>
  <a href="#contact" class="btn">Get Started</a>
</div>

<div class="section">
  <h2>Popular Destinations</h2>
  <div class="cards">
    <div class="card">🇬🇧 United Kingdom</div>
    <div class="card">🇹🇷 Turkey</div>
    <div class="card">🇦🇪 Dubai</div>
  </div>
</div>

<div class="section">
  <h2>Why Choose Almo Overseas</h2>
  <p>We provide reliable guidance to help students explore international education opportunities and make informed decisions.</p>
</div>

<div class="section" id="contact">
  <h2>Contact Us</h2>
  <p>Email: support.almo@gmail.com</p>
</div>

<footer>
  <p>© 2026 Almo Overseas</p>
</footer>

</body>
</html>
