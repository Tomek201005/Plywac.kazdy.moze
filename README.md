<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Pływać każdy może</title>
<style>
  /* Reset i podstawowe style */
  * {
    box-sizing: border-box;
  }
  body {
    margin:0; padding:0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(to bottom, #70c8f3, #1e90ff);
    color: #003344;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  header {
    background-color: rgba(0, 65, 130, 0.8);
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 2em;
    font-weight: bold;
    box-shadow: 0 2px 5px rgba(0,0,0,0.3);
  }
  nav {
    background-color: rgba(0, 90, 180, 0.9);
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
  }
  nav a {
    color: white;
    padding: 15px 30px;
    text-decoration: none;
    font-weight: 600;
    transition: background-color 0.3s ease;
    cursor: pointer;
  }
  nav a:hover, nav a.active {
    background-color: rgba(0, 50, 100, 0.9);
  }
  main {
    flex-grow: 1;
    max-width: 900px;
    margin: 40px auto 80px;
    background: rgba(255 255 255 / 0.9);
    border-radius: 12px;
    padding: 30px 40px;
    box-shadow: 0 0 20px rgba(0,0,0,0.1);
  }
  section {
    display: none;
  }
  section.active {
    display: block;
  }
  h2 {
    color: #004466;
    margin-bottom: 15px;
  }
  h3 {
    margin-top: 25px;
  }
  ul {
    margin-left: 20px;
  }
  blockquote {
    font-style: italic;
    font-size: 1.3em;
    color: #006699;
    margin: 20px 0 30px;
    text-align: center;
  }
  /* Fale na dole */
  .waves {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 200%;
    height: 12vh;
    background:
      radial-gradient(circle at 10% 50%, #0077be 30%, transparent 80%),
      radial-gradient(circle at 30% 50%, #0099de 30%, transparent 80%),
      radial-gradient(circle at 50% 50%, #005f8e 30%, transparent 80%);
    background-repeat: repeat-x;
    background-size: 200px 100%;
    animation: wave-move 8s linear infinite;
    opacity: 0.6;
    z-index: 0;
  }
  @keyframes wave-move {
    0% { background-position: 0 0, 0 0, 0 0; }
    100% { background-position: -400px 0, -200px 0, -100px 0; }
  }
  /* Responsywność */
  @media (max-width: 600px) {
    nav a {
      padding: 10px 15px;
      font-size: 0.9em;
    }
    main {
      margin: 20px 10px 60px;
      padding: 20px;
    }
  }
</style>
</head>
<body>

<header>Pływać każdy może</header>

<nav>
  <a href="#" class="active" data-section="home">Strona główna</a>
  <a href="#" data-section="styles">Style pływackie</a>
  <a href="#" data-section="swimmers">Najlepsi pływacy</a>
  <a href="#" data-section="kozienice">Kozienice pływają</a>
  <a href="#" data-section="contact">Kontakt</a>
</nav>

<main>
  <section id="home" class="active">
    <blockquote>
      „Pływanie to sztuka, którą każdy może opanować.<br />
      Zacznij już dziś i odkryj radość z ruchu w wodzie.”
    </blockquote>
    <p>Pływanie to jedna z najzdrowszych i najprzyjemniejszych form aktywności fizycznej 🏊‍♂️🌊, która angażuje niemal wszystkie partie mięśniowe 💪 i poprawia kondycję całego ciała. Niezależnie od wieku i umiejętności, każdy może zacząć pływać i czerpać z tego korzyści 😊.</p>
    <p>Regularne pływanie pomaga w:</p>
    <ul>
      <li><strong>Wzmacnianiu mięśni:</strong> podczas pływania pracują nasze ramiona, nogi, plecy i tułów - wzmacniamy w ten sposób mięśnie i zwiększa ich wytrzymałość.</li>
      <li><strong>Poprawie wydolności sercowo-naczyniowej:</strong> pływanie zwiększa pojemność płuc i poprawia krążenie krwi, co przyczynia się do lepszej wydolności serca.</li>
      <li><strong>Spalaniu kalorii:</strong> podczas intensywnego pływania można spalić nawet do 500-700 kalorii na godzinę! To świetny trening cardio 🔥.</li>
      <li><strong>Zwiększeniu elastyczności:</strong> pływanie poprawia zakres ruchu stawów, co jest korzystne dla osób cierpiących na sztywność stawów czy problemy z mobilnością. Jednocześnie nie obciążamy stawów, dlatego pływanie często jest także jedną z form rehabilitacji po kontuzjach oraz urazach kręgosłupa.</li>
      <li><strong>Poprawa skupienia:</strong> pływając skupiamy się na swoim ciele i ruchu, odrywamy się od wszelkich rozpraszaczy takich jak telefon czy telewizor.</li>
    </ul>
    <p>Pływanie ma również pozytywny wpływ na zdrowie psychiczne:</p>
    <ul>
      <li><strong>Redukcja stresu:</strong> kontakt z wodą działa uspokajająco i relaksująco, pomagając w redukcji poziomu stresu i poprawie nastroju. Rytmiczne, powtarzalne ruchy w wodzie są formą terapii ruchowej i działają niczym medytacja.</li>
      <li><strong>Poprawa samopoczucia:</strong> Aktywność fizyczna zwiększa produkcję endorfin, co przyczynia się do poprawy samopoczucia i ogólnego zadowolenia z życia.</li>
      <li><strong>Leczenie depresji i lęku:</strong> regularne pływanie może być formą terapii wspomagającej leczenie depresji i zaburzeń lękowych.</li>
    </ul>
  </section>

  <section id="styles">
    <h2>Style pływackie</h2>

    <h3>Styl klasyczny (żabka)</h3>
    <p>Styl klasyczny, zwany potocznie żabką, charakteryzuje się symetrycznym ruchem rąk i nóg, przypominającym kopnięcia żaby. Jest to jeden z najstarszych i najłatwiejszych do nauki stylów pływackich. Ruchy są stosunkowo powolne i pozwalają na swobodne oddychanie co cykl, co czyni go popularnym wśród początkujących i osób pływających rekreacyjnie.</p>

    <h3>Styl dowolny (kraul)</h3>
    <p>Styl dowolny, znany również jako kraul, to najszybszy ze wszystkich stylów pływackich i najczęściej używany w zawodach. Polega na naprzemiennych ruchach ramion oraz intensywnych kopnięciach nóg. Oddychanie odbywa się bokiem podczas przerwy w ruchu ramienia. Wymaga dobrej kondycji oraz koordynacji.</p>

    <h3>Styl grzbietowy</h3>
    <p>Styl grzbietowy to pływanie na plecach z ruchem ramion podobnym do kraula. Jest to jedyny styl wykonywany na plecach, co pozwala na swobodne oddychanie przez cały czas. Technika wymaga koordynacji ruchów oraz utrzymania odpowiedniej pozycji ciała, aby minimalizować opór wody.</p>

    <h3>Styl motylkowy (delfin)</h3>
    <p>Styl motylkowy to technicznie najbardziej wymagający styl pływacki, charakteryzujący się jednoczesnym ruchem obu rąk nad wodą i falującym ruchem ciała przypominającym ruch delfina. Wymaga dużej siły, koordynacji oraz wytrzymałości. Oddychanie odbywa się podczas fazy unoszenia ciała nad wodę.</p>
  </section>

  <section id="swimmers">
    <h2>Najlepsi pływacy</h2>

    <h3>Michael Phelps <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Flag_of_the_United_States.svg/30px-Flag_of_the_United_States.svg.png" alt="USA" /></h3>
    <p>Michael Phelps jest najbardziej utytułowanym pływakiem w historii, zdobywając 23 złote medale olimpijskie i ustanawiając liczne rekordy świata na dystansach od 100 m do 400 m w różnych stylach.</p>

    <h3>Caeleb Dressel <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Flag_of_the_United_States.svg/30px-Flag_of_the_United_States.svg.png" alt="USA" /></h3>
    <p>Caeleb Dressel to jeden z najszybszych współczesnych pływaków, specjalizujący się w sprintach. Zdobył wiele medali na Mistrzostwach Świata i Igrzyskach Olimpijskich, w tym złoto na 100 m stylem dowolnym i 100 m stylem motylkowym.</p>

    <h3>Otylia Jędrzejczak <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Flag_of_Poland.svg/30px-Flag_of_Poland.svg.png" alt="Polska" /></h3>
    <p>Otylia Jędrzejczak jest jedną z najlepszych polskich pływaczek, zdobywczynią złotego medalu olimpijskiego na 200 m stylem motylkowym oraz wielokrotną mistrzynią świata i Europy.</p>

    <h3>Radosław Kawęcki <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Flag_of_Poland.svg/30px-Flag_of_Poland.svg.png" alt="Polska" /></h3>
    <p>Radosław Kawęcki to specjalista od stylu grzbietowego, wielokrotny medalista mistrzostw świata i Europy, a także rekordzista Polski na dystansach 100 m i 200 m grzbietem.</p>
  </section>

  <section id="kozienice">
    <h2>Kozienice pływają</h2>
    <p>W Kozienicach działa kilka aktywnych klubów pływackich, które oferują profesjonalne szkolenia dla dzieci, młodzieży i dorosłych. Kluby te wspierają rozwój sportowy lokalnej społeczności, promując zdrowy tryb życia oraz rywalizację sportową na różnych poziomach.</p>

    <h3>Basen w Kozienicach</h3>
    <p>Basen miejski w Kozienicach to nowoczesny obiekt z komfortowymi warunkami do nauki i rekreacji pływackiej. Znajduje się przy ulicy Sportowej 5 i jest czynny codziennie od 6:00 do 22:00.</p>

    <h3>Kluby pływackie w Kozienicach</h3>

    <h4>1. Sportowy Klub Pływacki „Delfin”</h4>
    <p><strong>Prezes:</strong> Janusz Abramczyk</p>
    <p><strong>Adres:</strong> ul. Głowaczowska 41, 26-900 Kozienice</p>
    <p><strong>Telefon:</strong> 603 976 441, 504 061 381</p>
    <p><strong>E-mail:</strong> <a href="mailto:abram.j.@wp.pl">abram.j.@wp.pl</a></p>
    <p><strong>Strona internetowa:</strong> <a href="http://skp-delfin.pl" target="_blank" rel="noopener noreferrer">skp-delfin.pl</a></p>
    <p>SKP Delfin to renomowany klub z wieloletnią tradycją, oferujący zajęcia pływackie na różnych poziomach zaawansowania. Klub organizuje szkolenia, zawody oraz obozy sportowe, wspierając wszechstronny rozwój swoich zawodników.</p>

    <h4>2. UKS Aquator Kozienice</h4>
    <p><strong>Prezes:</strong> Radosław Gola</p>
    <p><strong>Adres:</strong> ul. Legionów 4, 26-900 Kozienice</p>
    <p><strong>Telefon:</strong> 609 293 949</p>
    <p><strong>Facebook:</strong> <a href="https://www.facebook.com/UKSAquatorKozienice" target="_blank" rel="noopener noreferrer">UKS Aquator Kozienice</a></p>
    <p>UKS Aquator to dynamicznie rozwijający się klub, który prowadzi treningi pływackie dla dzieci i młodzieży. Klub promuje zdrowy tryb życia oraz aktywność fizyczną, angażując się także w organizację lokalnych wydarzeń sportowych.</p>
  </section>

  <section id="contact">
    <h2>Kontakt</h2>
    <p>Osoba do kontaktu: <strong>Tomasz Prus</strong></p>
    <p>Email: <a href="mailto:tomasz.prus@example.com">tomasz.prus@example.com</a></p>
    <p>Telefon: 123-456-789</p>
  </section>
</main>

<div class="waves"></div>

<script>
  const navLinks = document.querySelectorAll('nav a');
  const sections = document.querySelectorAll('main section');

  navLinks.forEach(link => {
    link.addEventListener('click', e => {
      e.preventDefault();
      // Usuwamy aktywność z linków
      navLinks.forEach(l => l.classList.remove('active'));
      // Ukrywamy sekcje
      sections.forEach(s => s.classList.remove('active'));

      // Aktywujemy klikniętą zakładkę i powiązaną sekcję
      link.classList.add('active');
      const section = document.getElementById(link.dataset.section);
      if (section) section.classList.add('active');
    });
  });
</script>

</body>
</html>
