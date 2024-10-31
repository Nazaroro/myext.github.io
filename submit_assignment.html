<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Надіслати завдання</title>
</head>
<body>
    <form action="submit_assignment.php" method="post">
        <label>Ваша відповідь:</label>
        <textarea name="answer" required></textarea><br>
        <input type="submit" value="Надіслати">
    </form>

    <?php
    session_start();
    require 'includes/db.php';

    if ($_SERVER['REQUEST_METHOD'] == 'POST') {
        $user_id = $_SESSION['user_id'];
        $course_id = $_POST['course_id'];
        $answer = $_POST['answer'];

        $stmt = $pdo->prepare("INSERT INTO assignments (course_id, user_id, answer) VALUES (?, ?, ?)");
        $stmt->execute([$course_id, $user_id, $answer]);
        echo "Відповідь надіслано на перевірку!";
    }
    ?>
</body>
</html>
