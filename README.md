<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dr. Fatima Mukhtarkyzy — Прайс-лист</title>
  <style>
    body{margin:0;font-family:'Segoe UI',sans-serif;background:#f7f7f7;color:#333}
    header{background:#007b7a;color:#fff;padding:30px;text-align:center}
    header h1{margin:0;font-size:2.2em}
    header p{margin-top:10px;font-size:1.1em}
    nav{display:flex;justify-content:center;background:#fff;box-shadow:0 1px 5px rgba(0,0,0,0.1);flex-wrap:wrap}
    nav a{padding:12px 18px;color:#007b7a;text-decoration:none;font-weight:500}
    nav a:hover{background:#f0f0f0;border-radius:4px}

    section{max-width:1100px;margin:40px auto;padding:20px;}
    .section-card{background:#fff;padding:25px;border-radius:25px;box-shadow:0 15px 30px rgba(0,0,0,0.05);margin-bottom:30px;transition:0.3s ease}
    .section-card:hover{transform:translateY(-5px);box-shadow:0 25px 50px rgba(0,0,0,0.1)}
    h2{font-family:'Playfair Display', serif;color:#c9a36a;font-size:2rem;margin-bottom:25px}
    h3{font-family:'Playfair Display', serif;color:#c9a36a;margin-bottom:20px}

    /* Врач */
    .doctor{display:flex;flex-wrap:wrap;gap:25px;align-items:center}
    .doctor img{width:220px;border-radius:10px;box-shadow:0 2px 8px rgba(0,0,0,0.1)}
    .doctor-info{flex:1;min-width:250px}
    ul.services{list-style:none;padding:0;margin-top:15px}
    ul.services li{background:#f0f7f7;margin:6px 0;padding:8px 12px;border-radius:5px}

    /* Сетка для прайса */
    .price-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:30px}
    .category-title{font-family:'Playfair Display', serif;font-size:1.8rem;color:#c9a36a;margin-bottom:15px;display:flex;align-items:center;gap:10px}
    .price-list{list-style:none;padding:0;margin:0;font-family:'Inter',sans-serif}
    .price-list li{display:flex;justify-content:space-between;padding:8px 0;border-bottom:1px solid #eee;position:relative}
    .tag{background:#c92121;color:#fff;font-size:0.85rem;padding:2px 8px;border-radius:12px;position:absolute;right:0;top:0}
    .promo{background:#ffe6e6;color:#c92121;font-weight:bold;padding:10px 15px;border-radius:6px;margin:15px 0;text-align:center}

    /* WhatsApp кнопка */
    .cta{display:inline-block;padding:12px 25px;background:#25D366;color:#fff;border-radius:5px;text-decoration:none;font-weight:bold;margin-top:15px}
    .cta:hover{background:#128C7E}
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
      <img src="doctor_photo.jpg" alt="Dr. Fatima Mukhtarkyzy">
      <div class="doctor-info">
        <p>Стаж работы — более 20 лет</p>
        <p>🎓 Окончила Южно-Казахстанский государственный институт в 2001 году по специальности «Лечебное дело»</p>
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
      <div class="section-card">
        <div class="category-title">🩺 Гинекология</div>
        <div class="promo">АКЦИЯ! CO2 лазер + Плазмолифтинг + Плазма Гель + Филлеры — Скидка 50 000 тг</div>
        <ul class="price-list">
          <li>Плазмолифтинг + Плазма Гель (4 пробирки)<span>25 000 тг</span></li>
          <li>Estefill 2 мл + Плазмолифтинг + Плазма Гель<span>105 000 тг</span></li>
          <li>Estefill 4 мл + Плазмолифтинг + Плазма Гель<span>105 000 тг</span></li>
          <li>Chaeum 2 мл + Плазмолифтинг + Плазма Гель<span>70 000 тг</span></li>
          <li>Chaeum 4 мл + Плазмолифтинг + Плазма Гель<span>70 000 тг</span></li>
          <li>Maxyfill 2 мл + Плазмолифтинг + Плазма Гель<span>85 000 тг</span></li>
          <li>Aribell 2 мл + Плазмолифтинг + Плазма Гель<span>200 000 тг</span></li>
          <li>Aribell 4 мл + Плазмолифтинг + Плазма Гель<span>400 000 тг</span></li>
        </ul>
        <h4>Трон Кегеля</h4>
        <ul class="price-list">
          <li>1 сеанс <span>5 000 тг</span></li>
          <li>5 сеансов <span>22 500 тг</span></li>
          <li>10 процедур <span>40 000 тг</span></li>
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
      <div class="section-card">
        <div class="category-title">💆‍♀️ Косметология</div>
        <ul class="price-list">
          <li>Aqua Exosome <span>12 000 тг</span></li>
          <li>Hyaron <span>10 000 тг</span></li>
          <li>Kiara Reju <span>20 000 тг</span></li>
          <li>Aquashine <span>45 000 тг</span></li>
          <li>Ami Eyes <span>23 000 тг</span></li>
          <li>Illuma Eyes <span>23 000 тг</span></li>
          <li>Dermaheal <span>15 000 тг</span></li>
          <li>Мезотерапия + Биоревитализация <span>22 000 тг</span></li>
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
      <div class="section-card">
        <div class="category-title">💉 IV-терапия</div>
        <ul class="price-list">
          <li>Золушка <span>12 000 тг</span></li>
          <li>Мужская капельница <span>12 000 тг</span></li>
          <li>Похудейка <span>12 000 тг</span></li>
          <li>Мультивита <span>10 000 тг</span></li>
          <li>Lipo Lab (лицо) <span>15 000 тг</span></li>
          <li>Lipo Lab (тело) <span>12 000 тг</span></li>
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

<footer style="text-align:center;padding:20px;background:#333;color:#fff">
  &copy; 2025 Dr. Fatima Mukhtarkyzy. Все права защищены.
</footer>

</body>
</html>
