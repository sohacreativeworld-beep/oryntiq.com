# oryntiq.co
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Legid — Digital Design Studio</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    /* === BASE === */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Orbitron', sans-serif;
      background: #000;
      color: #dcdcdc;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    /* === HEADER === */
    header {
      padding: 1.5rem 5%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }

    .logo {
      font-size: 1.8rem;
      font-weight: 700;
      background: linear-gradient(90deg, #c0c0c0, #d4af37);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      letter-spacing: 2px;
    }

    nav a {
      color: #dcdcdc;
      text-decoration: none;
      margin-left: 2rem;
      transition: 0.3s;
      font-weight: 600;
    }
    nav a:hover {
      color: #d4af37;
    }

    /* === HERO SECTION === */
    .hero {
      text-align: center;
      padding: 5rem 10%;
    }

    .hero h1 {
      font-size: 3rem;
      background: linear-gradient(90deg, #d4af37, #c0c0c0);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 1.5rem;
    }

    .hero p {
      font-size: 1.1rem;
      color: #bfbfbf;
      max-width: 700px;
      margin: 0 auto 2rem;
    }

    .cta {
      display: inline-block;
      padding: 0.9rem 2rem;
      border: 2px solid #d4af37;
      color: #d4af37;
      border-radius: 8px;
      transition: 0.3s ease;
      font-weight: 600;
    }

    .cta:hover {
      background: linear-gradient(90deg, #d4af37, #c0c0c0);
      color: #000;
      transform: scale(1.05);
      box-shadow: 0 0 20px rgba(212,175,55,0.4);
    }

    /* === FOOTER === */
    footer {
      text-align: center;
      padding: 1.5rem;
      border-top: 1px solid rgba(255,255,255,0.1);
      font-size: 0.9rem;
      color: #9c9c9c;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">LEGID</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Projects</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1>Where Vision Meets Precision</h1>
      <p>LEGID crafts digital experiences blending luxury, technology, and bold design for the future-forward brands.</p>
      <a href="#" class="cta">Explore Work</a>
    </section>
  </main>

  <footer>
    © 2025 LEGID | All Rights Reserved
  </footer>
</body>
</html>
