<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Интернет-магазин</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Мой Магазин</h1>
  </header>

  <main class="product-grid">
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Товар 1">
      <h2>Товар 1</h2>
      <p>Цена: 1000₽</p>
      <button onclick="addToCart('Товар 1')">В корзину</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Товар 2">
      <h2>Товар 2</h2>
      <p>Цена: 1500₽</p>
      <button onclick="addToCart('Товар 2')">В корзину</button>
    </div>
  </main>

  <footer>
    <p>© 2025 Мой Магазин</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
