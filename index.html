<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Онлайн-курси</title>
    <script>
        function validateForm() {
            const title = document.forms["courseForm"]["title"].value;
            const videoPath = document.forms["courseForm"]["video_path"].value;

            if (title === "" || videoPath === "") {
                alert("Всі поля повинні бути заповнені.");
                return false;
            }
            return true;
        }

        function loadCourses() {
            fetch('load_courses.php')
                .then(response => response.json())
                .then(data => {
                    const courseList = document.getElementById('courseList');
                    courseList.innerHTML = '';

                    if (data.length > 0) {
                        data.forEach(course => {
                            const listItem = document.createElement('li');
                            listItem.innerHTML = `
                                ${course.title}
                                <a href="${course.video_path}">Переглянути відео</a>`;
                            courseList.appendChild(listItem);
                        });
                    } else {
                        courseList.innerHTML = '<p>Немає доступних курсів.</p>';
                    }
                })
                .catch(error => console.error('Error loading courses:', error));
        }

        window.onload = loadCourses; // Завантажуємо курси під час завантаження сторінки
    </script>
</head>
<body>
    <h1>Доступні курси</h1>

    <form name="courseForm" action="add_course.php" method="post" onsubmit="return validateForm()">
        <label for="title">Назва курсу:</label>
        <input type="text" name="title" required>
        <label for="video_path">Посилання на відео:</label>
        <input type="text" name="video_path" required>
        <input type="submit" value="Додати курс">
    </form>

    <ul id="courseList"></ul>

    <p><a href="register.php">Зареєструватися</a> | <a href="login.php">Увійти</a></p>
    <p><a href="check_homework.php">Перевірка домашніх завдань</a></p>

    <!-- Додаємо напис про автора -->
    <footer>
        <p style="text-align: center; margin-top: 20px;">Created by Nazar Kyrychenko</p>
    </footer>
</body>
</html>
