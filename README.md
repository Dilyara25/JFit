# JFit(авторизация)
Разработка мобильного приложения трекинга активности и здоровья.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Авторизация</title>
    <style>
        body {
            background-color: #f2f2f2;
            font-family: sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            background-color: #fff;
            padding: 30px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 350px;
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #ff8c00; /* Оранжевый цвет */
        }

        input[type="text"], input[type="password"] {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            margin-bottom: 15px;
        }

        button {
            background-color: #ff8c00; /* Оранжевый цвет */
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }

        button:hover {
            background-color: #ff7000; /* Темнее оранжевый */
        }

        .forgot-password {
            text-align: center;
            margin-bottom: 15px;
        }

        .forgot-password a {
            color: #ff8c00; /* Оранжевый цвет */
            text-decoration: none;
        }

        .forgot-password a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Авторизация</h2>
        <form action="#">
            <label for="username">Почта</label>
            <input type="text" id="username" name="username">
            <label for="password">Пароль</label>
            <input type="password" id="password" name="password">
            <button type="submit">Войти</button>
        </form>
    </div>
</body>
</html>
