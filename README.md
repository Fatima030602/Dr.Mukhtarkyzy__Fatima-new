<section id="pricelist" style="padding:100px 8%; background-color:#faf8f6;">
  <h2 style="font-family:'Playfair Display', serif; font-size:2.8rem; text-align:center; margin-bottom:60px;">
    Прайс-лист Dr. Fatima Mukhtarkyzy
  </h2>

  <style>
    /* Базовые стили */
    .price-grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 50px;
    }

    .category-card {
      background: #fff;
      padding: 25px;
      border-radius: 25px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.05);
      transition: all 0.3s ease;
      position: relative;
    }

    .category-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 25px 50px rgba(0,0,0,0.1);
    }

    .category-title {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      color: #c9a36a;
      margin-bottom: 25px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .category-title i {
      font-size: 1.5rem;
      color: #c92121;
    }

    ul.price-list {
      list-style: none;
      padding: 0;
      margin: 0;
      font-family: 'Inter', sans-serif;
      line-height: 1.8;
    }

    ul.price-list li {
      display: flex;
      justify-content: space-between;
      margin-bottom: 8px;
      position: relative;
      padding-right: 10px;
    }

    /* Цветные теги */
    .tag {
      background-color: #c92121;
      color: #fff;
      font-size: 0.85rem;
      padding: 2px 8px;
      border-radius: 12px;
      position: absolute;
      right: 0;
      top: 0;
    }

    /* Hover на li */
    ul.price-list li:hover {
      color: #c9a36a;
    }

    /* Сетка для косметологии и IV терапии */
    .sub-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
      gap: 30px;
    }

    @media(max-width:900px) {
      .category-title { font-size:1.8rem; }
    }
  </style>

  <div class="price-grid">

    <!-- ГИНЕКОЛОГИЯ -->
    <div class="category-card">
      <div class="category-title"><i>🩺</i> Гинекология</div>

      <ul class="price-list">
        <li>
          АКЦИЯ! CO2 лазер + Плазмолифтинг + Плазма Гель + Филлеры
          <span class="tag">-50 000 тг</span>
        </li>
        <li>Плазмолифтинг + Плазма Гель (4 пробирки)<span>25 000 тг</span></li>

        <li><strong>Филлеры гинекологические</strong></li>
        <li>Estefill 2 мл + Плазмолифтинг + Плазма Гель <span>105 000 тг</span></li>
        <li>Estefill 4 мл + Плазмолифтинг + Плазма Гель <span>105 000 тг</span></li>
        <li>Chaeum 2 мл + Плазмолифтинг + Плазма Гель <span>70 000 тг</span></li>
        <li>Chaeum 4 мл + Плазмолифтинг + Плазма Гель <span>70 000 тг</span></li>
        <li>Maxyfill 2 мл + Плазмолифтинг + Плазма Гель <span>85 000 тг</span></li>
        <li>Aribell 2 мл + Плазмолифтинг + Плазма Гель <span>200 000 тг</span></li>
        <li>Aribell 4 мл + Плазмолифтинг + Плазма Гель <span>400 000 тг</span></li>

        <li><strong>Трон Кегеля</strong></li>
        <li>1 сеанс <span>5 000 тг</span></li>
        <li>5 сеансов <span>22 500 тг</span></li>
        <li>10 процедур <span>40 000 тг</span></li>
      </ul>
    </div>

    <!-- КОСМЕТОЛОГИЯ -->
    <div class="category-card">
      <div class="category-title"><i>💆‍♀️</i> Косметология</div>
      <div class="sub-grid">
        <div>
          <strong>Биоревитализация (увлажнение кожи)</strong>
          <ul class="price-list">
            <li>Aqua Exosome <span>12 000 тг</span></li>
            <li>Hyaron <span>10 000 тг</span></li>
            <li>Kiara Reju <span>20 000 тг</span></li>
            <li>Aquashine <span>45 000 тг</span></li>
          </ul>
        </div>
        <div>
          <strong>Биоревитализация вокруг глаз</strong>
          <ul class="price-list">
            <li>Ami Eyes <span>23 000 тг</span></li>
            <li>Illuma Eyes <span>23 000 тг</span></li>
          </ul>
        </div>
        <div>
          <strong>Мезотерапия</strong>
          <ul class="price-list">
            <li>Dermaheal <span>15 000 тг</span></li>
            <li>Мезотерапия + Биоревитализация <span>22 000 тг</span></li>
            <li>Плазма + Биоревитализация <span>22 000 тг</span></li>
          </ul>
        </div>
      </div>
    </div>

    <!-- IV-ТЕРАПИЯ -->
    <div class="category-card">
      <div class="category-title"><i>💉</i> IV-терапия</div>
      <div class="sub-grid">
        <div>
          <strong>Капельницы</strong>
          <ul class="price-list">
            <li>Золушка <span>12 000 тг</span></li>
            <li>Мужская капельница <span>12 000 тг</span></li>
            <li>Похудейка <span>12 000 тг</span></li>
            <li>Мультивита <span>10 000 тг</span></li>
          </ul>
        </div>
        <div>
          <strong>Липолитики</strong>
          <ul class="price-list">
            <li>Lipo Lab (лицо) <span>15 000 тг</span></li>
            <li>Lipo Lab (тело) <span>12 000 тг</span></li>
          </ul>
        </div>
      </div>
    </div>

  </div>
</section>

