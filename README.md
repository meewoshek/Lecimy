<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Trening Online z Ludzkim Podejściem</title>
  <style>
   .about-section {
  display: flex; /* Flexbox do układania tekstu i obrazu obok siebie */
  align-items: center; /* Wyrównanie elementów w pionie */
  justify-content: flex-start; /* Ustawienie elementów w poziomie od lewej */
  gap: 20px; /* Odstęp między tekstem a obrazem */
  padding: 20px;
}

.about-text {
  max-width: 60%; /* Ograniczamy szerokość tekstu, żeby się nie rozciągał na całą szerokość */
  text-align: left; /* Ustawienie tekstu do lewej */
}

.about-image img {
  width: 40%; /* Obrazek będzie miał 40% szerokości */
  border-radius: 8px; /* Zaokrąglone rogi obrazka */
  object-fit: cover; /* Dopasowanie obrazka */
}

/* Styl dla innych sekcji */
.start-plan-section, .pricing-section {
  text-align: left; /* Wyrównanie tekstu do lewej */
  padding: 1rem;
}

.cta a {
  display: inline-block;
  text-align: left;
  margin-top: 10px;
}

/* Wyrównanie tytułów do lewej */
.start-plan-section h2, .pricing-section h2 {
  text-align: left;
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
         <p>Dalej liczysz, że forma zrobi się sama? Sorry, ale grubo się mylisz.</p>
      <p>Jestem Miłosz – gość, który pomoże Ci w końcu ogarnąć Twoją formę i pewność siebie, bez zbędnego pieprzenia.</p>
      <p>Współpracuję z facetami w wieku 20–40 lat, którzy mimo ciężkich treningów nadal mają problem ze zrobieniem formy.</p>
      <p>Co zyskujesz? Konkretny plan, proste i smaczne jedzenie i co najważniejsze - EFEKTY.</p>
      <p>I mam dla Ciebie gwarancję: Daj mi 30 dni i działaj zgodnie z moimi wytycznymi, a daję słowo, że będziesz zadowolony swoimi efektami. Jeśli tak się nie stanie - zwracam Ci 100% ceny. Chyba uczciwy deal. To co, działamy?</p>
    </div>
    <div class="about-image">
      <img src="your-image.jpg" alt="Miłosz" />
    </div>
  </div>
</section>

<section class="start-plan-section">
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
</section>

<section class="pricing-section">
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
