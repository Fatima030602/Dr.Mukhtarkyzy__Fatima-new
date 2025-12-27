<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dr. Fatima Mukhtarkyzy — Прайс-лист</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #f7f7f7;
      color: #333;
    }
    header {
      background: #007b7a;
      color: #fff;
      padding: 30px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-family: 'Playfair Display', serif;
      font-size: 2.2rem;
    }
    header p {
      margin-top: 10px;
      font-size: 1.1rem;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #fff;
      box-shadow: 0 1px 5px rgba(0,0,0,0.1);
      flex-wrap: wrap;
    }
    nav a {
      padding: 12px 18px;
      color: #007b7a;
      text-decoration: none;
      font-weight: 500;
    }
    nav a:hover {
      background: #f0f0f0;
      border-radius: 4px;
    }
    section {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      font-family: 'Playfair Display', serif;
      color: #c9a36a;
      font-size: 2rem;
      margin-bottom: 25px;
      text-align: center;
    }
    .section-card {
      background: #fff;
      padding: 25px;
      border-radius: 20px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.05);
      margin-bottom: 30px;
      transition: 0.3s ease;
    }
    .section-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 25px 50px rgba(0,0,0,0.1);
    }

    /* О враче */
    .doctor {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
      align-items: center;
    }
    .doctor img {
      width: 220px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .doctor-info {
      flex: 1;
      min-width: 250px;
    }
    ul.services {
      list-style: none;
      padding: 0;
      margin-top: 15px;
    }
    ul.services li {
      background: #f0f7f7;
      margin: 6px 0;
      padding: 8px 12px;
      border-radius: 5px;
    }

    /* Прайс-лист */
    .price-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }
    .category-card {
      padding: 20px;
      border-radius: 20px;
      color: #fff;
      position: relative;
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .category-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 40px rgba(0,0,0,0.2);
    }
    .category-title {
      font-family: 'Playfair Display', serif;
      font-size: 1.8rem;
      margin-bottom: 15px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .category-title i {
      font-size: 1.5rem;
    }
    ul.price-list {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    ul.price-list li {
      display: flex;
      justify-content: space-between;
      padding: 8px 0;
      border-bottom: 1px solid rgba(255,255,255,0.3);
      position: relative;
    }
    .promo {
      background: rgba(255,255,255,0.3);
      color: #fff;
      font-weight: bold;
      padding: 10px 15px;
      border-radius: 6px;
      margin: 15px 0;
      text-align: center;
    }

    /* Цветные карточки */
    .gynecology { background: #c92121; }
    .cosmetology { background: #c9a36a; }
    .ivtherapy { background: #007b7a; }

    /* Кнопка WhatsApp */
    .cta {
      display: inline-block;
      padding: 12px 25px;
      background: #25D366;
      color: #fff;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 15px;
      transition: background 0.3s ease;
    }
    .cta:hover { background: #128C7E; }

    /* Контакты */
    .contact-link {
      color: #007b7a;
      text-decoration: none;
    }
    .contact-link:hover { text-decoration: underline; }

    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: #fff;
    }

    @media(max-width:900px) {
      .category-title { font-size: 1.6rem; }
      .doctor { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>

<header>
  <h1>Dr. Fatima Mukhtarkyzy</h1>
  <p>Врач-гинеколог, маммолог, УЗИ-специалист и гинеколог-эстет</p>
</header>

<nav>
  <a href="#about">О враче</a>
  <a href="#gynecology">Гинекология</a>
  <a href="#cosmetology">Косметология</a>
  <a href="#ivtherapy">IV-терапия</a>
  <a href="#contacts">Контакты</a>
</nav>

<!-- О враче -->
<section id="about">
  <div class="section-card">
    <h2>О враче</h2>
    <div class="doctor">
      <img src="WhatsApp Image 2025-04-22 at 17.45.05.jpeg" alt="Dr. Fatima Mukhtarkyzy">
      <div class="doctor-info">
        <p>Dr. Фатима Мұхтарқызы — опытный гинеколог с более чем 22-летним стажем, посвятившая свою профессию заботе о женском здоровье и качестве жизни. За годы практики она помогла тысячам женщин, сочетая надежную классическую медицину с современными эстетическими методиками.</p>
        <p>Специализация: комплексное ведение женского здоровья — диагностика и лечение всех гинекологических заболеваний, помощь при недержании мочи, восстановление интимного здоровья и улучшение качества сексуальной жизни. Каждая пациентка получает индивидуальный подход для максимального комфорта.</p>
        <h3>Услуги:</h3>
        <ul class="services">
          <li>Лазерное сужение влагалища</li>
          <li>PRP-плазмотерапия</li>
          <li>Контурная пластика филлерами</li>
          <li>SMAS-лифтинг интимной зоны</li>
          <li>Подтяжка мышц аппаратом «Трон Кегеля»</li>
        </ul>
        <a class="cta" href="https://wa.me/77782251338?text=Здравствуйте,%20хочу%20записаться%20на%20прием%20к%20Dr.%20Fatima" target="_blank">Записаться через WhatsApp</a>
      </div>
    </div>
  </div>
</section>

<!-- Гинекология -->
<section id="gynecology">
  <div class="section-card">
    <h2>Гинекология</h2>
    <div class="price-grid">
      <div class="category-card gynecology">
        <div class="category-title"><i>🩺</i> Гинекология</div>
        <div class="promo">АКЦИЯ! CO2 лазер + Плазмолифтинг + Плазма Гель + Филлеры — Скидка 50 000 тг</div>
        <ul class="price-list">
          <li>Плазмолифтинг + Плазма Гель (4 пробирки)<span>25 000 тг</span></li>
          <li>Estefill 2 мл + Плазмолифтинг + Плазма Гель<span>105 000 тг</span></li>
          <li>Estefill 4 мл + Плазмолифтинг + Плазма Гель<span>105 000 тг</span></li>
          <li>Chaeum 2 мл + Плазмолифтинг + Плазма Гель<span>70 000 тг</span></li>
          <li>Chaeum 4 мл + Плазмолифтинг + Плазма Гель<span>70 000 тг</span></li>
          <li>Трон Кегеля: 1 сеанс <span>5 000 тг</span>, 5 сеансов <span>22 500 тг</span>, 10 процедур <span>40 000 тг</span></li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- Косметология -->
<section id="cosmetology">
  <div class="section-card">
    <h2>Косметология</h2>
    <div class="price-grid">
      <div class="category-card cosmetology">
        <div class="category-title"><i>💆‍♀️</i> Косметология</div>
        <ul class="price-list">
          <!-- Биоревитализация -->
          <li><strong>Биоревитализация (увлажнение кожи)</strong></li>
          <li>Aqua Exosome — 12 000 тг</li>
          <li>Hyaron — 10 000 тг</li>
          <li>Kiara Reju — 20 000 тг</li>
          <li>Aquashine — 45 000 тг</li>
          <li>Rejuran — 65 000 тг</li>
          <li>Rejuran Healer — 90 000 тг</li>
          <li>Jalupro (синий) — 48 000 тг</li>
          <li>Curenex — 18 000 тг</li>
          <li>PN Pro — 35 000 тг</li>
          <li>NAD + PDRN — 25 000 тг</li>
          <li>Cindella Healer — 55 000 тг</li>

          <!-- Вокруг глаз -->
          <li><strong>Биоревитализация вокруг глаз</strong></li>
          <li>Ami Eyes — 23 000 тг</li>
          <li>Illuma Eyes — 23 000 тг</li>

          <!-- Осветление кожи -->
          <li><strong>Осветление кожи</strong></li>
          <li>Ultra White Active — 25 000 тг</li>
          <li>Glutanhyall W-Action — 25 000 тг</li>

          <!-- Акне-терапия -->
          <li><strong>Акне-терапия</strong></li>
          <li>Acne Retinol — 25 000 тг</li>
          <li>Мэлсмон — 14 000 тг</li>

          <!-- Мезотерапия -->
          <li><strong>Мезотерапия</strong></li>
          <li>Dermaheal — 15 000 тг</li>
          <li>Мезотерапия + биоревитализация — 22 000 тг</li>
          <li>Плазма + биоревитализация — 22 000 тг</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- IV-терапия -->
<section id="ivtherapy">
  <div class="section-card">
    <h2>IV-терапия</h2>
    <div class="price-grid">
      <div class="category-card ivtherapy">
        <div class="category-title"><i>💉</i> IV-терапия</div>
        <ul class="price-list">
          <!-- Капельницы -->
          <li><strong>Капельницы</strong></li>
          <li>Золушка — 12 000 тг</li>
          <li>Мужская капельница — 12 000 тг</li>
          <li>Похудейка — 12 000 тг</li>
          <li>Мультивита — 10 000 тг</li>
          <li>Чесночная — 10 000 тг</li>
          <li>Коктейль Майерса — 15 000 тг</li>
          <li>Гингко Билоба — 12 000 тг</li>
          <li>Железо — 15 000 тг</li>
          <li>Витамин D — 14 000 тг</li>
          <li>Detox — 10 000 тг</li>
          <li>Лаеннек — 15 000 тг</li>
          <li>Витамин C — 10 000 тг</li>
          <li>Максиблю — 10 000 тг</li>

          <!-- Липолитики -->
          <li><strong>Липолитики</strong></li>
          <li>Lipo Lab (лицо) — 15 000 тг</li>
          <li>Lipo Lab (тело) — 12 000 тг</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- Контакты -->
<section id="contacts">
  <div class="section-card">
    <h2>Контакты</h2>
    <p>📞 <a class="contact-link" href="tel:+77782251338">+7 778 225 13 38</a></p>
    <p>📷 Instagram: <a class="contact-link" href="https://instagram.com/dr.fatima_mukhtarkyzy" target="_blank">@dr.fatima_mukhtarkyzy</a></p>
    <a class="cta" href="https://wa.me/77782251338?text=Здравствуйте,%20хочу%20записаться%20на%20прием%20к%20Dr.%20Fatima" target="_blank">Записаться через WhatsApp</a>
  </div>
</section>

<footer>
  &copy; 2025 Dr. Fatima Mukhtarkyzy. Все права защищены.
</footer>

</body>
</html>
