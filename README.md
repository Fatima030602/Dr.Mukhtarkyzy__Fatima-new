<!DOCTYPE html>
<html lang="ru">
<head>
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
  <p>Эстетическая медицина и гинекология в Алматы</p>
</header>

<nav>
  <a href="#about">О враче</a>
  <a href="#gynecology">Гинекология</a>
  <a href="#cosmetology">Косметология</a>
  <a href="#ivtherapy">IV-терапия</a>
  <a href="#contacts">Контакты</a>
</nav>

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

<section id="contacts" class="section">
  <h2>Контакты / Contacts</h2>
  <p>📞 <a href="tel:+77782251338" style="color:#007b7a;">+7 778 225 13 38</a></p>
  <p>📷 Instagram: <a href="https://instagram.com/dr.fatima_mukhtarkyzy" target="_blank" style="color:#007b7a;">@dr.fatima_mukhtarkyzy</a></p>
  <a class="cta" href="https://wa.me/77782251338?text=Здравствуйте,%20хочу%20записаться%20к%20Dr.%20Fatima" target="_blank">Записаться через WhatsApp / Book via WhatsApp</a>
</section>

<footer>
  &copy; 2025 Dr. Fatima Mukhtarkyzy. Все права защищены.
</footer>

</body>
</html>
