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
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Dr. Fatima Mukhtarkyzy — Клиника</title>
<style>
body {
  margin:0;
  font-family:'Segoe UI',sans-serif;
  background:#fdfdfd;
  color:#333;
}
header{
  background:linear-gradient(90deg,#007b7a,#00bfa5);
  color:#fff;
  padding:30px 20px;
  text-align:center;
}
header h1{margin:0;font-size:2.5em;}
header p{margin:5px 0 0 0;font-size:1.2em;}

nav{
  display:flex;
  justify-content:center;
  background:#fff;
  box-shadow:0 2px 10px rgba(0,0,0,0.1);
  flex-wrap:wrap;
}
nav a{
  padding:15px 25px;
  color:#007b7a;
  text-decoration:none;
  font-weight:600;
  transition:0.3s;
}
nav a:hover{
  background:#007b7a;
  color:#fff;
  border-radius:5px;
}

.section{
  max-width:1000px;
  margin:50px auto;
  padding:30px;
}
.section h2{
  text-align:center;
  color:#007b7a;
  font-size:2.2em;
  margin-bottom:40px;
}

/* О враче */
.doctor{
  display:flex;
  flex-wrap:wrap;
  gap:30px;
  align-items:flex-start;
  justify-content:center;
}
.doctor img{
  width:300px;
  border-radius:20px;
  box-shadow:0 15px 30px rgba(0,0,0,0.1);
}
.doctor-info{
  flex:1;
  min-width:300px;
}
.doctor-info p{
  margin-bottom:15px;
  line-height:1.6;
}

/* Карточки услуг */
.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:30px;
}
.card{
  background:#fff;
  border-radius:20px;
  padding:25px;
  box-shadow:0 10px 25px rgba(0,0,0,0.08);
  transition:transform 0.3s, box-shadow 0.3s;
}
.card:hover{
  transform:translateY(-10px);
  box-shadow:0 20px 50px rgba(0,0,0,0.15);
}
.card h3{
  color:#c9a36a;
  font-family:'Playfair Display', serif;
  font-size:1.8em;
  margin-bottom:20px;
  display:flex;
  align-items:center;
  gap:10px;
}
.card ul{
  list-style:none;
  padding:0;
  margin:0;
}
.card ul li{
  display:flex;
  justify-content:space-between;
  margin-bottom:10px;
  padding-bottom:5px;
  border-bottom:1px solid #eee;
}
.card .promo{
  background:#ffe6e6;
  color:#c92121;
  text-align:center;
  padding:10px;
  border-radius:10px;
  font-weight:bold;
  margin-top:15px;
}

/* CTA кнопка */
.cta{
  display:inline-block;
  margin-top:20px;
  padding:15px 30px;
  background:#25D366;
  color:#fff;
  border-radius:10px;
  text-decoration:none;
  font-weight:bold;
  box-shadow:0 5px 15px rgba(0,0,0,0.1);
  transition:0.3s;
}
.cta:hover{
  background:#128C7E;
}

/* Footer */
footer{
  background:#333;
  color:#fff;
  padding:30px;
  text-align:center;
  margin-top:50px;
}

@media(max-width:900px){
  header h1{font-size:2em;}
  .card h3{font-size:1.6em;}
}
</style>
</head>
<body>

<header>
  <h1>Dr. Fatima Mukhtarkyzy</h1>
  <p>Врач-гинеколог, маммолог, УЗИ-специалист и гинеколог-эстет</p>
  <p>Эстетическая медицина и гинекология в Алматы</p>
</header>

<nav>
@@ -54,111 +169,85 @@
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
<section id="about" class="section">
  <h2>О враче / About the Doctor</h2>
  <div class="doctor">
    <img src="doctor_photo.jpg" alt="Dr. Fatima Mukhtarkyzy">
    <div class="doctor-info">
      <p>🎓 Окончила Южно-Казахстанский государственный институт в 2001 году по специальности акушерство и гинекология, «Лечебное дело».</p>
      <p>Фатима Мұхтарқызы — опытный гинеколог с более чем 22-летним стажем, посвятившая свою жизнь женскому здоровью и качеству жизни.</p>
      <p>Специализация: диагностика и лечение всех гинекологических заболеваний, восстановление интимного здоровья, улучшение сексуальной жизни.</p>
      <p>Методы: СО₂-лазер, SMAS-лифтинг, аппаратная гинекология, плазма-лифтинг, контурная пластика филлерами, плазмотерапия и плазма-гели.</p>
      <a class="cta" href="https://wa.me/77782251338?text=Здравствуйте,%20хочу%20записаться%20к%20Dr.%20Fatima" target="_blank">Записаться через WhatsApp / Book via WhatsApp</a>
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
<section id="gynecology" class="section">
  <div class="cards">
    <div class="card">
      <h3>🩺 Гинекология</h3>
      <ul>
        <li>CO2 Laser + PRP + Filler <span style="color:red;">-50 000 тг</span></li>
        <li>PRP + Plasma Gel (4 vials) <span>25 000 тг</span></li>
        <li>Estefill 2ml + PRP <span>105 000 тг</span></li>
        <li>Estefill 4ml + PRP <span>105 000 тг</span></li>
        <li>Chaeum 2ml + PRP <span>70 000 тг</span></li>
        <li>Chaeum 4ml + PRP <span>70 000 тг</span></li>
        <li>Maxyfill 2ml + PRP <span>85 000 тг</span></li>
        <li>Aribell 2ml + PRP <span>200 000 тг</span></li>
        <li>Aribell 4ml + PRP <span>400 000 тг</span></li>
        <li>Tron Kegel 1 session <span>5 000 тг</span></li>
        <li>Tron Kegel 5 sessions <span>22 500 тг</span></li>
        <li>Tron Kegel 10 sessions <span>40 000 тг</span></li>
      </ul>
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
<section id="cosmetology" class="section">
  <div class="cards">
    <div class="card">
      <h3>💆‍♀️ Косметология / Cosmetology</h3>
      <ul>
        <li>Aqua Exosome <span>12 000 тг</span></li>
        <li>Hyaron <span>10 000 тг</span></li>
        <li>Kiara Reju <span>20 000 тг</span></li>
        <li>Aquashine <span>45 000 тг</span></li>
        <li>Ami Eyes <span>23 000 тг</span></li>
        <li>Illuma Eyes <span>23 000 тг</span></li>
        <li>Dermaheal <span>15 000 тг</span></li>
        <li>Mesotherapy + Biorevitalization <span>22 000 тг</span></li>
        <li>Plasma + Biorevitalization <span>22 000 тг</span></li>
      </ul>
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
<section id="ivtherapy" class="section">
  <div class="cards">
    <div class="card">
      <h3>💉 IV-терапия / IV Therapy</h3>
      <ul>
        <li>Cinderella drip <span>12 000 тг</span></li>
        <li>Male drip <span>12 000 тг</span></li>
        <li>Weight loss drip <span>12 000 тг</span></li>
        <li>Multivita drip <span>10 000 тг</span></li>
        <li>Lipo Lab (Face) <span>15 000 тг</span></li>
        <li>Lipo Lab (Body) <span>12 000 тг</span></li>
      </ul>
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
<section id="contacts" class="section">
  <h2>Контакты / Contacts</h2>
  <p>📞 <a href="tel:+77782251338" style="color:#007b7a;">+7 778 225 13 38</a></p>
  <p>📷 Instagram: <a href="https://instagram.com/dr.fatima_mukhtarkyzy" target="_blank" style="color:#007b7a;">@dr.fatima_mukhtarkyzy</a></p>
  <a class="cta" href="https://wa.me/77782251338?text=Здравствуйте,%20хочу%20записаться%20к%20Dr.%20Fatima" target="_blank">Записаться через WhatsApp / Book via WhatsApp</a>
</section>

<footer style="text-align:center;padding:20px;background:#333;color:#fff">
<footer>
  &copy; 2025 Dr. Fatima Mukhtarkyzy. Все права защищены.
</footer>
