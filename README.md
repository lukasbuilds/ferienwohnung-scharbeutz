<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ferienwohnungen Scharbeutz – Modern Coastal Comfort</title>

  <style>
    /* ===== Grundfarben & Typografie ===== */
    :root {
      --sand: #f5f3ef;
      --blue: #2f5d73;
      --dark: #1f2a30;
      --light: #ffffff;
      --accent: #c7a46a;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background-color: var(--sand);
      color: var(--dark);
      line-height: 1.6;
    }

    a {
      color: var(--blue);
      text-decoration: none;
    }

    header {
      background: url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e") center/cover no-repeat;
      min-height: 90vh;
      display: flex;
      align-items: center;
      padding: 4rem;
      color: white;
    }

    .hero {
      max-width: 700px;
      background: rgba(0,0,0,0.35);
      padding: 3rem;
      border-radius: 12px;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .cta {
      margin-top: 2rem;
    }

    .btn {
      display: inline-block;
      padding: 0.9rem 1.8rem;
      margin-right: 1rem;
      border-radius: 30px;
      background: var(--accent);
      color: white;
      font-weight: 600;
    }

    section {
      padding: 5rem 8%;
      background: var(--sand);
    }

    section.white {
      background: var(--light);
    }

    h2 {
      font-size: 2.2rem;
      margin-bottom: 1.5rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 2rem;
    }

    .apartment {
      background: white;
      border-radius: 16px;
      padding: 1.5rem;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    }

    .apartment img {
      width: 100%;
      border-radius: 12px;
      margin-bottom: 1rem;
    }

    .apartment h3 {
      margin-bottom: 0.5rem;
    }

    footer {
      background: var(--dark);
      color: white;
      padding: 3rem 8%;
      text-align: center;
    }

    .lang-switch {
      position: fixed;
      top: 20px;
      right: 20px;
      background: white;
      border-radius: 20px;
      padding: 0.4rem 0.8rem;
      font-size: 0.9rem;
      cursor: pointer;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }

    @media (max-width: 768px) {
      h1 { font-size: 2.2rem; }
      header { padding: 2rem; }
    }
  </style>
</head>

<body>

<div class="lang-switch" onclick="toggleLanguage()">DE / EN</div>

<header>
  <div class="hero">
    <h1 data-de="Exklusive Ferienwohnungen in Scharbeutz"
        data-en="Exclusive Holiday Apartments in Scharbeutz">
        Exklusive Ferienwohnungen in Scharbeutz
    </h1>

    <p data-de="Modern. Ruhig. Hochwertig. Erleben Sie die Ostsee von ihrer schönsten Seite."
       data-en="Modern. Quiet. High-quality. Experience the Baltic Sea at its finest.">
       Modern. Ruhig. Hochwertig. Erleben Sie die Ostsee von ihrer schönsten Seite.
    </p>

    <div class="cta">
      <a href="#kontakt" class="btn"
         data-de="Jetzt anfragen"
         data-en="Send inquiry">
         Jetzt anfragen
      </a>
    </div>
  </div>
</header>

<section class="white">
  <h2 data-de="Unsere Ferienwohnungen"
      data-en="Our Apartments">
      Unsere Ferienwohnungen
  </h2>

  <p data-de="26 stilvoll eingerichtete Ferienwohnungen für anspruchsvolle Gäste, die Wert auf Komfort, Ruhe und Qualität legen."
     data-en="26 tastefully designed apartments for guests who value comfort, tranquility and quality.">
     26 stilvoll eingerichtete Ferienwohnungen für anspruchsvolle Gäste, die Wert auf Komfort, Ruhe und Qualität legen.
  </p>
</section>

<section>
  <div class="grid">
    <!-- Beispiel Wohnung – du kannst das 26x duplizieren -->
    <div class="apartment">
      <img src="https://images.unsplash.com/photo-1505691938895-1758d7feb511" alt="">
      <h3>Apartment 01</h3>
      <p>1–2 Gäste · Balkon · Strandnah</p>
      <p>
        <a href="#">Airbnb</a> |
        <a href="#">Booking</a>
      </p>
    </div>

    <div class="apartment">
      <img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267" alt="">
      <h3>Apartment 02</h3>
      <p>2–4 Gäste · Terrasse · Ruhige Lage</p>
      <p>
        <a href="#">Airbnb</a> |
        <a href="#">Booking</a>
      </p>
    </div>
  </div>
</section>

<section class="white" id="kontakt">
  <h2 data-de="Kontakt & Anfrage"
      data-en="Contact & Inquiry">
      Kontakt & Anfrage
  </h2>

  <p data-de="Sie haben Fragen oder wünschen ein individuelles Angebot?"
     data-en="Do you have questions or would like a personalized offer?">
     Sie haben Fragen oder wünschen ein individuelles Angebot?
  </p>

  <form>
    <input type="text" placeholder="Name" style="width:100%;padding:10px;margin:10px 0;">
    <input type="email" placeholder="E-Mail" style="width:100%;padding:10px;margin:10px 0;">
    <textarea placeholder="Nachricht" style="width:100%;padding:10px;margin:10px 0;"></textarea>
    <button class="btn" type="submit"
      data-de="Nachricht senden"
      data-en="Send message">
      Nachricht senden
    </button>
  </form>
</section>

<footer>
  <p>© Ferienwohnungen Scharbeutz</p>
</footer>

<script>
  let currentLang = "de";

  function toggleLanguage() {
    currentLang = currentLang === "de" ? "en" : "de";
    document.querySelectorAll("[data-de]").forEach(el => {
      el.innerText = el.dataset[currentLang];
    });
  }
</script>

</body>
</html>
