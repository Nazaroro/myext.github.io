<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Реєстрація</title>
</head>
<body>
    <h1>Реєстрація</h1>

    <form action="register.php" method="post">
        <label for="username">Ім'я користувача:</label>
        <input type="text" name="username" required>
        <label for="password">Пароль:</label>
        <input type="password" name="password" required>
        <input type="submit" value="Зареєструватись">
    </form>

    <?php
    require 'includes/db.php';

    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        $username = $_POST['username'];
        $password = password_hash($_POST['password'], PASSWORD_BCRYPT);

        $stmt = $pdo->prepare("INSERT INTO users (username, password) VALUES (:username, :password)");
        $stmt->execute(['username' => $username, 'password' => $password]);

        echo "Користувача успішно зареєстровано!";
    }
    ?>
</body>
</html>
