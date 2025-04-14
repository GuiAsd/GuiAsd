<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BuyZone</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>BiznesZone</h1>
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
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #222;
  color: white;
  padding: 20px;
  text-align: center;
}

.product-grid {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  padding: 20px;
  gap: 20px;
}

.product {
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 10px;
  width: 220px;
  text-align: center;
  background-color: #f9f9f9;
}

.product img {
  max-width: 100%;
  height: auto;
}

button {
  margin-top: 10px;
  padding: 10px;
  background-color: #28a745;
  border: none;
  color: white;
  cursor: pointer;
  border-radius: 5px;
}

button:hover {
  background-color: #218838;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #eee;
}
