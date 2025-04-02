# hakolbekeef-site hakolbekeef-site
<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>הכל בכיף - דף הבית</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">בית</a></li>
                <li><a href="#services">שירותים</a></li>
                <li><a href="#about">אודות</a></li>
                <li><a href="#contact">צור קשר</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <section id="home">
            <h1>ברוכים הבאים ל"הכל בכיף"</h1>
            <p>אנו מציעים שירותים אישיים ומקצועיים לכל המשפחה!</p>
        </section>

        <section id="services">
            <h2>השירותים שלנו</h2>
            <ul>
                <li>הליכות עם כלבים</li>
                <li>שיעורי מוזיקה</li>
                <li>קייטרינג ביתי</li>
                <li>מטלות ביתיות</li>
                <li>שיעורים פרטיים במתמטיקה ואנגלית</li>
                <li>שירותי משלוחים</li>
            </ul>
        </section>

        <section id="about">
            <h2>אודות</h2>
            <p>הכל בכיף מספק שירותים עם דגש על אישיות, מקצועיות, והנאה. כל השירותים שלנו מותאמים אישית לצרכים של כל משפחה, ומבוססים על קשרים אמינים ויחס אישי.</p>
        </section>

        <section id="contact">
            <h2>צור קשר</h2>
            <form action="#" method="POST">
                <label for="name">שם:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">אימייל:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">הודעה:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">שלח</button>
            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 הכל בכיף - כל הזכויות שמורות</p>
    </footer>
</body>
</html>
