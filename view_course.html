<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Перегляд курсу</title>
</head>
<body>
    <?php
    require 'includes/db.php';
    $course_id = $_GET['course_id'];

    $stmt = $pdo->prepare("SELECT * FROM courses WHERE id = ?");
    $stmt->execute([$course_id]);
    $course = $stmt->fetch();

    if ($course) {
        echo "<h2>" . htmlspecialchars($course['title']) . "</h2>";
        echo "<p>" . htmlspecialchars($course['description']) . "</p>";

        // Відображення відео
        echo "<h3>Відео:</h3>";
        $stmt = $pdo->prepare("SELECT * FROM videos WHERE course_id = ?");
        $stmt->execute([$course_id]);
        $videos = $stmt->fetchAll();

        foreach ($videos as $video) {
            echo "<p><a href='" . htmlspecialchars($video['video_path']) . "' target='_blank'>" . htmlspecialchars($video['title']) . "</a></p>";
        }
    } else {
        echo "Курс не знайдено!";
    }
    ?>
</body>
</html>
