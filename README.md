<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CryptoSkills — Закритий Криптокурс</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0a0a0a;
      color: #f8f8f8;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #ff0000;
    }
    header h1 {
      margin: 0;
      font-size: 32px;
      color: #ff0000;
    }
    .section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .section h2 {
      color: #ff0000;
      margin-bottom: 20px;
    }
    .modules, .reviews {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }
    .module, .review {
      background: #1c1c1c;
      padding: 20px;
      border-left: 4px solid #ff0000;
      border-radius: 4px;
    }
    form {
      background: #1c1c1c;
      padding: 30px;
      border: 2px solid #ff0000;
      border-radius: 6px;
    }
    input, textarea, button {
      display: block;
      width: 100%;
      margin: 15px 0;
      padding: 10px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
    }
    input, textarea {
      background: #2a2a2a;
      color: #fff;
    }
    button {
      background: #ff0000;
      color: #fff;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #cc0000;
    }
    .telegram {
      text-align: center;
      margin-top: 40px;
    }
    .telegram a {
      display: inline-block;
      padding: 15px 25px;
      background: #ff0000;
      color: #fff;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #888;
    }
    @media (max-width: 768px) {
      .modules, .reviews {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>CryptoSkills — Закритий Криптокурс</h1>
  </header>

  <section class="section">
    <h2>Що ти отримаєш?</h2>
    <div class="modules">
      <div class="module">
        <strong>Модуль 1:</strong> Основи блокчейну та крипти
      </div>
      <div class="module">
        <strong>Модуль 2:</strong> Як не втратити гроші — безпечне зберігання
      </div>
      <div class="module">
        <strong>Модуль 3:</strong> Практика DeFi, біржі, стейкінг, токеноміка
      </div>
      <div class="module">
        <strong>Модуль 4:</strong> Пошук трендів, NFT, GameFi, AirDrops
      </div>
    </div>
  </section>

  <section class="section">
    <h2>Відгуки наших студентів</h2>
    <div class="reviews">
      <div class="review">“Я за тиждень підняв x3 на стартовій монеті завдяки цьому курсу!”</div>
      <div class="review">“Дуже просте пояснення — навіть новачок зрозуміє. Респект команді.”</div>
      <div class="review">“Топова подача і класні кейси — окупив курс ще до фінального модуля.”</div>
      <div class="review">“Після курсу реально пішов прибуток. Не думав, що так можна.”</div>
    </div>
  </section>

  <section class="section">
    <h2>Заявка на курс</h2>
    <form action="https://formspree.io/f/mrbpdbga" method="POST">
      <label>Ваше ім'я:</label>
      <input type="text" name="name" required />
      
      <label>Telegram (нік або лінк):</label>
      <input type="text" name="telegram" required />
      
      <label>Чому хочете пройти курс?</label>
      <textarea name="reason" rows="4" required></textarea>

      <button type="submit">Відправити заявку</button>
    </form>
  </section>

  <div class="telegram">
    <a href="https://t.me/cryptoskillsp2" target="_blank">Написати в Telegram</a>
  </div>

  <footer>
    © 2025 CryptoSkills. All rights reserved.
  </footer>

</body>
</html>
