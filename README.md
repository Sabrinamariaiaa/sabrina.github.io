<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glow Beauty</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #F5C6CE; /* Ljusrosa bakgrund */
            color: #000; /* Svart text */
            margin: 0;
            padding: 0;
            display: flex;
            height: 100vh;
            flex-direction: column;
        }

        /* Menyn på vänster sida */
        nav {
            background-color: #FFF9F3; /* Ljus bakgrund för menyn */
            padding: 20px;
            width: 200px;
            height: 100%;
            position: fixed;
            left: 0;
            top: 0;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        nav a {
            text-decoration: none;
            color: black;
            font-size: 18px;
            margin-bottom: 15px;
        }

        /* Innehållssektion */
        main {
            margin-left: 220px; /* Ger plats för menyn */
            padding: 20px;
            flex-grow: 1;
        }

        /* Footer */
        footer {
            background-color: #FFF9F3;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            left: 220px;
            right: 0;
        }

        footer a {
            color: black;
            text-decoration: none;
            margin: 0 15px;
        }

    </style>
</head>
<body>

    <!-- Meny till vänster -->
    <nav>
        <div>
            <a href="#">Hem</a>
            <a href="#">Produkter</a>
            <a href="#">Nyheter</a>
            <a href="#">Blogg</a>
        </div>
    </nav>

    <!-- Huvudinnehåll -->
    <main>
        <h1>Välkommen till Fiktivt Sminkmärke</h1>
        <p>Här hittar du de senaste produkterna och tipsen för att skapa den perfekta looken. Upptäck våra kollektioner och bli inspirerad av våra blogginlägg.</p>
    </main>

    <!-- Footer längst ner -->
    <footer>
        <a href="#">Kontakt</a>
        <a href="#">Om oss</a>
    </footer>

</body>
</html>
