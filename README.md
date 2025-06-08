# Wikipedia-Przyklad<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Przykład strony internetowej wzorowanej na Wikipedii">
    <title>Wikipedia - Przykład</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #0061F2;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            background-color: #f5f5f5;
            padding: 10px;
            text-align: center;
        }

        nav a {
            text-decoration: none;
            color: #0061F2;
            padding: 10px;
            margin: 0 15px;
        }

        nav a:hover {
            background-color: #ddd;
        }

        .container {
            display: flex;
            margin: 20px;
        }

        .main-content {
            flex: 1;
            padding: 20px;
            background-color: white;
            margin-right: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .sidebar {
            width: 250px;
            background-color: #f1f1f1;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .sidebar h2 {
            font-size: 18px;
            margin-bottom: 15px;
        }

        footer {
            background-color: #0061F2;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

        h1, h2, h3 {
            color: #0061F2;
        }

        .content-section {
            margin-bottom: 20px;
        }

        .content-section h2 {
            margin-top: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Wikipedia - Przykład</h1>
</header>

<nav>
    <a href="#section1">Strona Główna</a>
    <a href="#section2">Historia</a>
    <a href="#section3">Kultura</a>
    <a href="#section4">Społeczeństwo</a>
    <a href="#section5">Zobacz także</a>
</nav>

<div class="container">
    <div class="main-content">
        <div class="content-section" id="section1">
            <h2>Strona Główna</h2>
            <p>Wikipedia to internetowa encyklopedia, która jest tworzona i edytowana przez użytkowników na całym świecie. Celem Wikipedii jest gromadzenie wiedzy w formie dostępnej dla każdego internauty. Strona zawiera artykuły na temat różnych dziedzin wiedzy, takich jak nauka, historia, kultura i inne.</p>
        </div>

        <div class="content-section" id="section2">
            <h2>Historia</h2>
            <p>Wikipedia została założona 15 stycznia 2001 roku przez Jimmy'ego Walesa oraz Larry'ego Sangera. Początkowo miała być uzupełnieniem dla Nupedii, ale szybko stała się jednym z największych źródeł wiedzy w Internecie. Dzięki modelowi otwartej edycji, Wikipedia umożliwia każdemu użytkownikowi tworzenie i modyfikowanie artykułów.</p>
        </div>

        <div class="content-section" id="section3">
            <h2>Kultura</h2>
            <p>Wikipedia jest nie tylko źródłem wiedzy naukowej, ale także istotnym narzędziem kulturowym. Oferuje artykuły na temat literatury, sztuki, muzyki, filmów i innych dziedzin, które mają wpływ na kulturę globalną.</p>
        </div>

        <div class="content-section" id="section4">
            <h2>Społeczeństwo</h2>
            <p>Wikipedia odgrywa istotną rolę w społeczeństwie, umożliwiając dzielenie się wiedzą na skalę globalną. Pomimo różnych wyzwań związanych z weryfikowaniem treści, Wikipedia stała się jednym z najczęściej odwiedzanych źródeł informacji w internecie.</p>
        </div>

        <div class="content-section" id="section5">
            <h2>Zobacz także</h2>
            <ul>
                <li><a href="https://pl.wikipedia.org" target="_blank">Oficjalna strona Wikipedii</a></li>
                <li><a href="https://pl.wikipedia.org/wiki/Wikipedia:Historia" target="_blank">Historia Wikipedii</a></li>
                <li><a href="https://pl.wikipedia.org/wiki/Wikipedia:Zasady" target="_blank">Zasady Wikipedii</a></li>
            </ul>
        </div>
    </div>

    <div class="sidebar">
        <h2>Przeglądaj</h2>
        <ul>
            <li><a href="#section1">Strona Główna</a></li>
            <li><a href="#section2">Historia</a></li>
            <li><a href="#section3">Kultura</a></li>
            <li><a href="#section4">Społeczeństwo</a></li>
        </ul>
    </div>
</div>

<footer>
    <p>&copy; 2025 Wikipedia - Przykład | Wszystkie prawa zastrzeżone</p>
</footer>

</body>
</html>
