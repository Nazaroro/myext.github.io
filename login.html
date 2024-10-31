<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Вхід</title>
</head>
<body>
    <h1>Вхід</h1>

    <form action="login.php" method="post">
        <label for="username">Ім'я користувача:</label>
        <input type="text" name="username" required>
        <label for="password">Пароль:</label>
        <input type="password" name="password" required>
        <input type="submit" value="Увійти">
    </form>

    <?php
    require 'includes/db.php';

    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        $username = $_POST['username'];
        $password = $_POST['password'];

        $stmt = $pdo->prepare("SELECT * FROM users WHERE username = :username");
        $stmt->execute(['username' => $username]);
        $user = $stmt->fetch(PDO::FETCH_ASSOC);

        if ($user && password_verify($password, $user['password'])) {
            echo "Вітаємо, " . htmlspecialchars($username) . "!";
            // Тут можеш зберегти сесію або кукі для входу користувача
        } else {
            echo "Неправильне ім'я користувача або пароль.";
        }
    }
    ?>
</body>
</html>
