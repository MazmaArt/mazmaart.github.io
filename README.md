<!DOCTYPE html>
<header style="display: flex; align-items: center; justify-content: space-between; padding: 1rem 2rem; background-color: #fff; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
  <!-- Logo -->
  <div>
    <a href="/">
      <img src="logo-da-usare-nel-sito-principale-mazma-art.webp" alt="Logo Mazma Art" style="height: 120px;">
    </a>
  </div>

  <!-- Navigazione -->
  <nav>
    <ul style="list-style: none; display: flex; gap: 1.5rem; margin: 0; padding: 0;">
      <li><a href="#home" style="text-decoration: none; color: #333;">Home</a></li>
      <li><a href="#opere" style="text-decoration: none; color: #333;">Opere</a></li>
      <li><a href="#ispirazione" style="text-decoration: none; color: #333;">Ispirazione</a></li>
      <li><a href="#contatti" style="text-decoration: none; color: #333;">Contatti</a></li>
    </ul>
  </nav>
</header>


  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #fff;
      color: #111;
      line-height: 1.6;
    }
    header {
      height: 100vh;
      background: url('images/hero.jpg') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }
    header h1 {
      font-size: 3.5rem;
      background: rgba(0, 0, 0, 0.6);
      padding: 1rem 2rem;
      border-radius: 8px;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      z-index: 1000;
    }
    nav .logo {
      font-weight: bold;
      font-size: 1.2rem;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }
    nav ul li a {
      text-decoration: none;
      color: #111;
      font-weight: 500;
    }
    section {
      padding: 6rem 2rem 4rem;
      max-width: 900px;
      margin: 0 auto;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    footer {
      background: #f9f9f9;
      padding: 2rem;
      text-align: center;
      font-size: 0.9rem;
      color: #555;
    }
    a {
      color: #007acc;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <nav>
    <div class="logo">MazmaArt</div>
    <ul>
      <li><a href="#about">Chi sono</a></li>
      <li><a href="#works">Opere</a></li>
      <li><a href="#contact">Contatti</a></li>
    </ul>
  </nav>

  <header>
    <h1>Arte che parla all'anima</h1>
  </header>

  <section id="about">
    <h2>Chi sono</h2>
    <p>Ciao! Sono MazmaArt, artista specializzata in cloisonné e tecniche decorative ispirate al simbolismo e alla materia. Creo opere che fondono luce, metallo e colore per evocare emozioni profonde.</p>
  </section>

  <section id="works">
    <h2>Opere</h2>
    <div class="gallery">
      <img src="images/opera1.jpg" alt="Opera 1">
      <img src="images/opera2.jpg" alt="Opera 2">
      <img src="images/opera3.jpg" alt="Opera 3">
    </div>
  </section>
  <header>
  <div style="display: flex; align-items: center; justify-content: center; gap: 1rem; flex-wrap: wrap;">
    <img src="logo-da-usare-nel-sito-principale-mazma-art.webp" alt="Logo MazmaArt" style="height: 120px;" />
    <h1>MazmaArt</h1>
  </div>
  <p>"L'arte non riproduce ciò che è visibile, ma rende visibile ciò che non sempre lo è."</p>
</header>

  <section id="contact">
    <h2>Contatti</h2>
    <p>Email: <a href="mailto:mazmaart@gmail.com">mazmaart@gmail.com</a></p>
    <p>Instagram: <a href="https://www.instagram.com/mazmaart" target="_blank">@mazmaart.grazi</a></p>
  </section>

  <footer>
    <p>&copy; 2025 MazmaArt. Tutti i diritti riservati.</p>
  </footer>
</body>
</html>
 

  
