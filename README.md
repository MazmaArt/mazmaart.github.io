<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Il Tuo Sito - Arte Cloisonné</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; color: #333; }
    header { display: flex; align-items: center; justify-content: space-between; padding: 1rem 2rem; background: #fff; box-shadow: 0 2px 6px rgba(0,0,0,0.1); position: sticky; top: 0; z-index: 10; }
    header img { height: 60px; }
    nav ul { list-style: none; display: flex; gap: 1.5rem; margin: 0; padding: 0; }
    nav a { text-decoration: none; color: #333; font-weight: bold; }
    section { padding: 4rem 2rem; text-align: center; }
    .hero { background: #f5f5f5; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit,minmax(280px,1fr)); gap: 1.5rem; }
    .grid-item { position: relative; overflow: hidden; }
    .grid-item img { width: 100%; height: auto; display: block; transition: transform .3s ease; }
    .grid-item:hover img { transform: scale(1.05); }
    footer { padding: 2rem; background: #fafafa; text-align: center; font-size: 0.9rem; color: #666; }
    @media (max-width: 600px) {
      nav ul { flex-direction: column; gap: 1rem; }
    }
  </style>
</head>
<body>

<header>
  <a href="/">
    <img src="logo-da-usare-nel-sito-principale-mazma-art.webp" alt="Il tuo logo">
  </a>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#macro">Macro</a></li>
      <li><a href="#landscape">Paesaggi</a></li>
      <li><a href="#still">Still Life</a></li>
      <li><a href="#collage">Collage Art</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contatti</a></li>
    </ul>
  </nav>
</header>

<section id="home" class="hero">
  <h1>Benvenuti nella mia arte cloisonné</h1>
  <p>Un viaggio visivo attraverso dettagli, natura, composizioni e collage.</p>
</section>

<section id="macro">
  <h2>Macro</h2>
  <div class="grid">
    <!-- 4 immagini esempio -->
    <div class="grid-item"><img src="macro1.jpg" alt="Macro 1"></div>
    <div class="grid-item"><img src="macro2.jpg" alt="Macro 2"></div>
    <div class="grid-item"><img src="macro3.jpg" alt="Macro 3"></div>
    <div class="grid-item"><img src="macro4.jpg" alt="Macro 4"></div>
  </div>
  <p>Scopri dettagli invisibili a occhio nudo, trasformati in pura arte.</p>
</section>

<section id="landscape">
  <h2>Paesaggi</h2>
  <div class="grid">
    <div class="grid-item"><img src="land1.jpg" alt="Paesaggio 1"></div>
    <div class="grid-item"><img src="land2.jpg" alt="Paesaggio 2"></div>
    <div class="grid-item"><img src="land3.jpg" alt="Paesaggio 3"></div>
    <div class="grid-item"><img src="land4.jpg" alt="Paesaggio 4"></div>
  </div>
  <p>Poesia visiva tra natura, montagna, acqua e luce.</p>
</section>

<section id="still">
  <h2>Still Life</h2>
  <div class="grid">
    <div class="grid-item"><img src="still1.jpg" alt="Still Life 1"></div>
    <div class="grid-item"><img src="still2.jpg" alt="Still Life 2"></div>
    <div class="grid-item"><img src="still3.jpg" alt="Still Life 3"></div>
    <div class="grid-item"><img src="still4.jpg" alt="Still Life 4"></div>
  </div>
  <p>Oggetti quotidiani trasformati in eleganti opere d'arte.</p>
</section>

<section id="collage">
  <h2>Collage Art</h2>
  <div class="grid">
    <div class="grid-item"><img src="coll1.jpg" alt="Collage 1"></div>
    <div class="grid-item"><img src="coll2.jpg" alt="Collage 2"></div>
    <div class="grid-item"><img src="coll3.jpg" alt="Collage 3"></div>
    <div class="grid-item"><img src="coll4.jpg" alt="Collage 4"></div>
  </div>
  <p>Composizioni originali che narrano storie visive.</p>
</section>

<section id="about">
  <h2>About</h2>
  <p>Mi chiamo [Tuo Nome], lavoro con la tecnica cloisonné per creare opere che raccontano emozioni attraverso colore, forma e luce.</p>
</section>

<section id="contact">
  <h2>Contatti</h2>
  <p>Scrivimi: <a href="mailto:tuo@email.com">tuo@email.com</a></p>
  <p>Seguimi sui social: Instagram / Facebook / TikTok</p>
</section>

<footer>
  <p>© 2025 [Tuo Nome]. Tutti i diritti riservati.</p>
</footer>

</body>
</html>
 

  
