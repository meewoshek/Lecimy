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
    /* Klasa do sekcji 'Kim jestem?' */
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
    /* Nowe style dla oddzielonych sekcji */
    .start-plan-section {
      background-color: #f1f1f1; /* Inne tło dla tej sekcji */
      margin-top: 2rem; /* Przestrzeń nad sekcją */
      padding: 2rem;
    }
    .offer {
      background: #fff;
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
    /* Sekcja z ofertami (Standard, Premium) */
    .pricing-section {
      background-color: #ffffff;
      padding: 2rem;
      margin-top: 2rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .offer h3 {
      margin-top: 0;
    }
    /* Sekcja wyzwań */
    .challenge-section {
      background-color: #ffe6e6; /* Jasno-czerwony, wyróżniający się kolor */
      padding: 2rem;
      text-align: center;
      margin-top: 2rem;
    }
    .centered {
      width: 800px;
      height: auto;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Trener online ale efekty już stacjonarne</h1>
    <p>Pamiętaj, że Twoje wyniki są takie, jak ciężko na nie zapracowałeś/aś!</p>
  </header>

  <section>
    <h2>Kim jestem?</h2>
    <div class="about">
      <img src="IMG_4905.jpg" alt="Miłosz Bembenek – trener">
      <div class="about-text">
        <p>Cześć!</p>
        <p>Mam na imię Miłosz i jestem certyfikowanym trenerem personalnym, piłkarzem oraz zawodnikiem sportów walki, który niestety ale zarazi Cię pozytywnym nastawieniem i chęcią do następnego, kolejnego i jeszcze jednego treningu. Pomogę Ci ogarnąć swoje ciało i zdrowie w prosty sposób i <strong>bez magicznych diet. </strong>Proste, że jasne. <strong>Sprawdź sam/a</strong> i przekonaj się na własnym ciele.</p>
      </div>
    </div>
  </section>

  <!-- Sekcja Darmowy Plan Startowy -->
  <section class="start-plan-section">
    <h2>Darmowy plan startowy</h2>
    <div class="offer centered">
      <p>Dla osób, które <strong>dopiero zaczynają.</strong> Otrzymasz:</p>
      <ul>
        <li>Mini-poradnik żywieniowy</li>
        <li>Plan FBW 2x w tygodniu</li>
        <li>Plan FBW 3x w tygodniu</li>
      </ul>
      <p><strong>0 zł</strong> – kliknij poniżej i odbierz plan!</p>
    </div>
    <div class="cta centered">
      <a href="https://linktr.ee/meewoshek" target="_blank">Kliknij tutaj</a>
      <p><strong>Potrzebujesz bardziej dopasowanej pomocy? Sprawdź poniżej! 💪</strong></p>
    </div>
  </section>

  <!-- Sekcja Prowadzenie online -->
  <section class="pricing-section">
    <h2>Prowadzenie online - wybierz coś dla siebie!</h2>
    <div class="offer centered">
      <h3>Starter – 129 zł</h3>
      <p>Indywidualny plan treningowy + wsparcie online. Idealne na początek.</p>
    </div>
    <div class="offer centered">
      <h3>Standard – 299 zł / miesiąc</h3>
      <p>Indywidualny plan treningowy, analiza Twojej diety i progresji treningowej, stały kontakt.</p>
    </div>
    <div class="offer centered">
      <h3>Premium – 449 zł / miesiąc</h3>
      <p>Pełne wsparcie 1:1, regularne rozmowy i kontrola techniki, diety, analiza stylu życia, codzienny kontakt oraz indywidualna opieka.</p>
    </div>
    <div class="cta centered">
      <p>Masz pytania? Napisz do mnie na IG: <strong>@milosz.trenuje</strong></p>
      <a href="https://www.instagram.com/milosz.trenuje" target="_blank">Pogadajmy!</a>
    </div>
  </section>

  <!-- Sekcja Miesięczne wyzwania -->
  <section class="challenge-section">
    <h2>🔥 Miesięczne wyzwania 🔥</h2>
    <p><strong>Chcesz dodatkową motywację w postaci wyzwań? Już ja coś dla Ciebie znajdę!  
    Obiecuję, że efekty Cię zaskoczą!</strong></p>
  </section>

  <footer>
    <p>&copy; 2025 Miłosz Bembenek | Jeśli dotrwałeś/aś do tego momentu to napisz do mnie na instagramie i pochwal się swoim maxem na klatę 😁 </p>
  </footer>
  <script>
  document.addEventListener("DOMContentLoaded", function () {
    const selectors = ['p', 'li', '.about-text', '.cta'];
    selectors.forEach(selector => {
      document.querySelectorAll(selector).forEach(el => {
        el.innerHTML = el.innerHTML
          // spacja + pojedyncza litera + spacja
          .replace(/ (\w{1}) /g, ' $1&nbsp;')
          // spacja + pojedyncza litera + przecinek/kropka
          .replace(/ (\w{1})([,.])/g, ' $1$2')
          // spacja + pojedyncza litera na końcu
          .replace(/ (\w{1})<\/(p|li)>/g, ' $1</$2>');
      });
    });
  });
</script>
</body>
</html>
