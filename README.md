<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Trening Online z Ludzkim Podejściem</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #1e1e2f;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    section {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      color: #1e1e2f;
    }
    .offer {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      margin: 1rem 0;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .cta {
      background: #1e1e2f;
      color: white;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
      margin-top: 2rem;
    }
    .cta a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      background: #ff6b6b;
      padding: 0.5rem 1rem;
      border-radius: 6px;
      display: inline-block;
      margin-top: 1rem;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #777;
    }
    .about {
      display: flex;
      gap: 2rem;
      align-items: flex-start;
      flex-wrap: wrap;
      margin-top: 1rem;
    }
    .about img {
      width: 200px;
      height: auto;
      border-radius: 12px;
      flex-shrink: 0;
    }
    .about-text {
      flex: 1;
      min-width: 250px;
      text-align: justify;
    }

    /* Tylko dla sekcji "Darmowy plan startowy" i poniżej */
    .centered-content {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      padding: 2rem;
      text-align: center;
      margin-top: 2rem;
    }

    .start-plan-section {
      width: 100%;
      max-width: 100vw;
      background-color: #f1f1f1;
      padding: 2rem;
      box-sizing: border-box;
      margin: 0;
    }

    .pricing-section {
      background-color: #ffffff;
      padding: 2rem;
      margin-top: 2rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .challenge-section {
      background-color: #ffe6e6;
      padding: 2rem;
      text-align: center;
      margin-top: 2rem;
    }

    @media (max-width: 768px) {
      .about {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }
      .about-text {
        text-align: justify;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Trener online ale efekty już stacjonarne</h1>
    <p>Pamiętaj, że Twoje wyniki są takie, jak ciężko na nie zapracowałeś/aś!</p>
  </header>

  <section>
    <h2>Ej, Ty!</h2>
    <div class="about">
      <img src="IMG_4905.jpg" alt="Miłosz Bembenek – trener">
      <div class="about-text">
        <p>Dalej liczysz, że <strong>forma zrobi się sama?</strong> Sorry, ale grubo się mylisz. 
        <p>Jestem Miłosz – gość, który pomoże Ci w końcu ogarnąć Twoją formę i pewność siebie, <strong>bez zbędnego pieprzenia.</strong><p>
        <p>Współpracuję z facetami w wieku <strong>20–40 lat</strong>, którzy mimo ciężkich treningów nadal mają <strong>problem ze zrobieniem formy.</strong><p>
        <p>Co zyskujesz? Konkretny plan, proste i smaczne jedzenie i co najważniejsze - <strong>EFEKTY.</strong> <p>
        I mam dla Ciebie <strong>gwarancję:</strong>
        Daj mi <strong>30 dni</strong> i działaj zgodnie z moimi wytycznymi, a <strong>daję słowo,</strong> że będziesz zadowolony swoimi efektami.
        Jeśli tak się nie stanie - <strong>zwracam Ci 100% ceny.</strong> Chyba uczciwy deal. <strong>To co, działamy?</strong></p>
      </div>
    </div>
  </section>

  <!-- Sekcja Darmowy plan startowy -->
  <section class="centered-content">
    <div class="start-plan-section">
      <h2>Darmowy plan startowy</h2>
      <div class="offer">
        <p>Dla osób, które <strong>dopiero zaczynają.</strong> Otrzymasz:</p>
        <ul>
          <li>Mini-poradnik żywieniowy</li>
          <li>Plan FBW 2x w tygodniu</li>
          <li>Plan FBW 3x w tygodniu</li>
        </ul>
        <p><strong>0 zł</strong> – kliknij poniżej i odbierz plan!</p>
      </div>
      <div class="cta">
        <a href="https://linktr.ee/meewoshek" target="_blank">Kliknij tutaj</a>
        <p><strong>Potrzebujesz bardziej dopasowanej pomocy? Sprawdź poniżej! 💪</strong></p>
      </div>
    </div>
  </section>

  <!-- Sekcja Prowadzenie online -->
  <section class="centered-content">
    <div class="pricing-section">
      <h2>Wybierz pakiet dla siebie!</h2>
      <div class="offer">
        <h3>Pakiet Rozgrzewka – 129 zł</h3>
        <p>Indywidualny plan treningowy + wsparcie online. Idealne na początek.</p>
      </div>
      <div class="offer">
        <h3>Pakiet Przemiana – 299 zł / miesiąc</h3>
        <p>Indywidualny plan treningowy, analiza Twojej diety i kontrola postępów w treningach, stały kontakt.</p>
      </div>
      <div class="offer">
        <h3>Pakiet Bestia – 449 zł / miesiąc</h3>
        <p>Pełne wsparcie 1:1, kontrola techniki, progresji, diety, analiza stylu życia, codzienny kontakt oraz indywidualna opieka.</p>
      </div>
      <div class="cta">
        <p>Masz pytania? Napisz do mnie na IG: <strong>@milosz.trenuje</strong></p>
        <a href="https://www.instagram.com/milosz.trenuje" target="_blank">Pogadajmy!</a>
      </div>
    </div>
  </section>

  <!-- Sekcja Miesięczne wyzwania -->
  <section class="centered-content">
    <div class="challenge-section">
      <h2>🔥 Miesięczne wyzwania 🔥</h2>
      <p><strong>Chcesz dodatkową motywację w postaci wyzwań? Już ja coś dla Ciebie znajdę!  
      Obiecuję, że efekty Cię zaskoczą!</strong></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Miłosz Bembenek | Jeśli dotrwałeś/aś do tego momentu to napisz do mnie na instagramie i pochwal się swoim maxem na klatę 😁 </p>
  </footer>
</body>
</html>
