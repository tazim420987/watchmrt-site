<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Essential meta tags -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WatchMRT.com - Home</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/k7ujTnH1z7MZHchGGH0gLQGURa3lT+ioUi6N7/9Q3fNwqmD1+sfkz8Gr+cD3aQgi4u+6Jepqf1Tlw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    /* ====== Base Styles ====== */
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #121212;
      color: #eee;
      line-height: 1.6;
    }
    a {
      color: inherit;
      text-decoration: none;
    }
    img {
      display: block;
      max-width: 100%;
    }

    /* ====== Header ====== */
    header {
      position: sticky;
      top: 0;
      z-index: 10;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: rgba(30,30,30,0.9);
      backdrop-filter: blur(10px);
    }
    header h1 {
      font-size: 2rem;
      letter-spacing: 1px;
      display: flex;
      align-items: center;
    }
    header h1:before {
      content: '\f03d'; /* fa-video icon code */
      font-family: 'Font Awesome 5 Free';
      font-weight: 900;
      margin-right: 8px;
      color: #ff004f;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0%,100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    nav a {
      margin: 0 20px;
      font-weight: 500;
      position: relative;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ff004f;
    }
    nav a:after {
      content: '';
      position: absolute;
      left: 0; bottom: -4px;
      width: 0;
      height: 2px;
      background: #ff004f;
      transition: width 0.3s;
    }
    nav a:hover:after {
      width: 100%;
    }

    /* ====== Hero Section ====== */
    .hero {
      position: relative;
      background: url('https://via.placeholder.com/1200x600') center/cover no-repeat;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #fff;
    }
    .hero:before {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(180deg, rgba(0,0,0,0.4), rgba(0,0,0,0.7));
    }
    .hero h2 {
      position: relative;
      font-size: 4rem;
      margin: 0;
      animation: fadeIn 1s ease-out forwards;
    }
    .hero p {
      position: relative;
      font-size: 1.5rem;
      margin: 20px 0;
      animation: fadeIn 1.5s ease-out forwards;
    }
    .buttons {
      position: relative;
      display: flex;
      gap: 20px;
      animation: fadeIn 2s ease-out forwards;
    }
    .hero button {
      padding: 15px 30px;
      border: 2px solid #ff004f;
      background: transparent;
      color: #ff004f;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 50px;
      transition: all 0.3s;
    }
    .hero button:hover {
      background: #ff004f;
      color: #fff;
      transform: translateY(-3px);
      box-shadow: 0 8px 15px rgba(255,0,79,0.4);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* ====== Featured Videos ====== */
    .section { padding: 80px 40px; }
    .video-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }
    .video-item {
      position: relative;
      overflow: hidden;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
      transition: transform 0.3s;
    }
    .video-item:hover {
      transform: scale(1.03);
    }
    .video-item img {
      display: block;
      width: 100%;
      height: auto;
    }
    .video-item h3 {
      position: absolute;
      bottom: 0;
      width: 100%;
      margin: 0;
      padding: 15px;
      font-size: 1.2rem;
      background: rgba(0,0,0,0.6);
      color: #fff;
    }
    .video-item:before {
      content: '\f144'; /* fa-play icon */
      font-family: 'Font Awesome 5 Free';
      font-weight: 900;
      position: absolute;
      font-size: 3rem;
      color: rgba(255,0,79,0.8);
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      opacity: 0;
      transition: opacity 0.3s;
    }
    .video-item:hover:before {
      opacity: 1;
    }

    /* ====== Newsletter Section ====== */
    .newsletter {
      background: #1e1e1e;
      padding: 60px 40px;
      text-align: center;
      border-radius: 12px;
      margin: 40px auto;
      max-width: 800px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
    }
    .newsletter h2 { margin-bottom: 10px; }
    .newsletter input[type="email"] {
      padding: 12px;
      width: 60%;
      border: none;
      border-radius: 50px;
      margin-right: 10px;
    }
    .newsletter button {
      padding: 12px 25px;
      border: none;
      background: #ff004f;
      color: #fff;
      font-size: 1rem;
      border-radius: 50px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .newsletter button:hover {
      background: #e60045;
    }

    /* ====== Footer ====== */
    footer {
      background: #141414;
      padding: 30px 40px;
      text-align: center;
      color: #888;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>WatchMRT</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Videos</a>
      <a href="#">Categories</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <!-- Hero Banner -->
  <section class="hero">
    <h2>Lights. Camera. MRT.</h2>
    <p>Original stories. Professional production. Watch now.</p>
    <div class="buttons">
      <button>Watch Videos</button>
      <button>Explore Categories</button>
    </div>
  </section>

  <!-- Featured Videos Grid -->
  <section class="section">
    <h2>Featured Videos</h2>
    <div class="video-grid">
      <div class="video-item">
        <img src="https://via.placeholder.com/400x225" alt="The Last Light">
        <h3>Short Film: The Last Light</h3>
      </div>
      <div class="video-item">
        <img src="https://via.placeholder.com/400x225" alt="Studio Days">
        <h3>Behind the Scenes: Studio Days</h3>
      </div>
      <div class="video-item">
        <img src="https://via.placeholder.com/400x225" alt="Echoes">
        <h3>Music Video: Echoes</h3>
      </div>
    </div>
  </section>

  <!-- Newsletter Signup -->
  <section class="newsletter">
    <h2>Stay in the Loop</h2>
    <p>Subscribe for exclusive behind-the-scenes content &amp; updates.</p>
    <form>
      <input type="email" placeholder="Enter your email" required>
      <button type="submit">Subscribe</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 MRT PRODUCTION. All Rights Reserved.
  </footer>
</body>
</html>
