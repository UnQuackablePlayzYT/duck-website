# duck-website <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>All About Ducks</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f8ff;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background: #4db8ff;
      color: white;
      text-align: center;
      padding: 1.5rem 0;
    }
    nav {
      background: #007acc;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .gallery img {
      width: 200px;
      margin: 1rem;
      border-radius: 8px;
      box-shadow: 2px 2px 8px rgba(0,0,0,0.2);
    }
    footer {
      background: #4db8ff;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Duck World</h1>
    <p>All about ducks — fun, facts, and fluff!</p>
  </header>

  <nav>
    <a href="#facts">Duck Facts</a>
    <a href="#gallery">Gallery</a>
    <a href="#game">Duck Game</a>
  </nav>

  <section id="facts">
    <h2>🐤 Fun Duck Facts</h2>
    <ul>
      <li>Ducks have waterproof feathers!</li>
      <li>They can sleep with one eye open.</li>
      <li>Some ducks migrate thousands of miles.</li>
      <li>They communicate using over 15 different sounds.</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>🖼️ Duck Gallery</h2>
    <div class="gallery">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Mallard2.jpg/320px-Mallard2.jpg" alt="Mallard Duck">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Ducklings_in_grass.jpg/320px-Ducklings_in_grass.jpg" alt="Ducklings">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bf/White_domestic_duck.jpg/320px-White_domestic_duck.jpg" alt="White Duck">
    </div>
  </section>

  <section id="game">
    <h2>🎮 Duck Game (Coming Soon!)</h2>
    <p>We're working on a fun duck-themed mini game. Stay tuned!</p>
  </section>

  <footer>
    <p>© 2025 Duck World. All quacks reserved.</p>
  </footer>
</body>
</html>
