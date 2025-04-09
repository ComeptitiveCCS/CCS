<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Competitive CoD Series</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background-color: #0a0f2c;
      color: #ffffff;
      background-image: url('https://i.imgur.com/wso34RQ.png');
      background-size: 400px;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      opacity: 0.95;
    }
    nav {
      background: rgba(18, 28, 74, 0.95);
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav .logo {
      font-size: 1.5rem;
      color: #ffffff;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 2rem;
    }
    nav ul li a {
      color: #ffffff;
      text-decoration: none;
      transition: color 0.3s;
    }
    nav ul li a:hover {
      color: #5da9ff;
    }
    .hero {
      padding: 6rem 2rem;
      text-align: center;
      background: rgba(26, 36, 92, 0.85);
      backdrop-filter: blur(4px);
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .cta-buttons a {
      text-decoration: none;
      margin: 0 1rem;
      background: #5da9ff;
      color: #0a0f2c;
      padding: 0.75rem 1.5rem;
      border-radius: 8px;
      transition: background 0.3s;
    }
    .cta-buttons a:hover {
      background: #3d8fe6;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: rgba(18, 28, 74, 0.95);
      font-size: 0.9rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <nav>
    <div class="logo">Competitive CoD Series</div>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Teams</a></li>
      <li><a href="#">Standings</a></li>
      <li><a href="#">Media</a></li>
    </ul>
  </nav>

  <section class="hero">
    <h1>Welcome to the Competitive CoD Series</h1>
    <p>Where the best teams battle for glory. Qualifiers, tournaments, highlights — all in one place.</p>
    <div class="cta-buttons">
      <a href="https://discord.gg/FSaMrtqm" target="_blank">Join Discord</a>
      <a href="https://www.twitch.tv/" target="_blank">Watch Live</a>
    </div>
  </section>

  <footer>
    &copy; 2025 Competitive CoD Series | All Rights Reserved
  </footer>
</body>
</html>
