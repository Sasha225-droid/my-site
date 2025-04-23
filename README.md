<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой первый сайт</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }
        nav {
            background-color: #444;
            padding: 1em;
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать на мой сайт</h1>
    </header>
    <nav>
        <a href="#home">Главная</a>
        <a href="#about">О нас</a>
        <a href="#contact">Контакты</a>
    </nav>
    <div class="container">
        <h2>О сайте</h2>
        <p>Это пример простого сайта, созданного с использованием HTML и CSS. Вы можете добавлять сюда свой контент, изображения и функционал.</p>
        <button onclick="showMessage()">Нажми меня!</button>
    </div>
    <footer>
        <p>&copy; 2025 Мой сайт. Все права защищены.</p>
    </footer>
    <script>
        function showMessage() {
            alert("Привет! Это мой первый сайт!");
        }
    </script>
</body>
</html>
