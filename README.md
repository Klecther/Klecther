<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <title>Мой репозиторий</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background: #f5f5f5;
        color: #333;
        max-width: 800px;
        margin: 40px auto;
        padding: 20px;
      }
      h1 {
        text-align: center;
        color: #2c3e50;
      }
      .tech-badges {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 10px;
        margin-bottom: 30px;
      }
      .badge img {
        height: 32px; /* аккуратный размер значков */
        border-radius: 6px;
      }
      .car-image {
        width: 100%;
        max-width: 600px;
        display: block;
        margin: 0 auto;
        border-radius: 12px;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      }
    </style>
  </head>
  <body>
    <h1>Мой крутой репозиторий 🚗</h1>

    <div class="tech-badges">
      <div class="badge">
        <img src="https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python" alt="Python" />
      </div>
      <div class="badge">
        <img src="https://img.shields.io/badge/C%2B%2B-20-red?style=for-the-badge&logo=cplusplus" alt="C++" />
      </div>
      <div class="badge">
        <img src="https://img.shields.io/badge/HTML5-E35D4E?style=for-the-badge&logo=html5" alt="HTML5" />
      </div>
      <div class="badge">
        <img src="https://img.shields.io/badge/CSS3-29A9E1?style=for-the-badge&logo=css3" alt="CSS3" />
      </div>
    </div>

    <!-- Картинка с машиной -->
    <img src="https://images.unsplash.com/photo-1568605117036-f601d15a4fff?w=800&q=80" alt="Крутая тачка" class="car-image" />
  </body>
</html>
