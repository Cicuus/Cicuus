<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.KY.hu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Üdvözöllek a www.KY.hu weboldalon!</h1>
        <nav>
            <ul>
                <li><a href="#about">Rólam</a></li>
                <li><a href="#music">Zene</a></li>
                <li><a href="#contact">Kapcsolat</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Rólam</h2>
        <p>Üdvözöllek! Kilián vagyok, és az oldalaimon osztom meg zenéimet és projektemet. Itt többet megtudhatsz rólam és munkáimról.</p>
    </section>

    <section id="music">
        <h2>Zene</h2>
        <p>Itt találhatók a legújabb dalaim, videóim és projektem. Képviselőm a rap, hip-hop, pop és rock stílusokat.</p>
        <!-- Itt lehetőség van beágyazni videókat vagy zenei lejátszókat -->
    </section>

    <section id="contact">
        <h2>Kapcsolatfelvétel</h2>
        <p>Ha bármit szeretnél tőlem kérdezni, vagy kapcsolatba lépni, töltsd ki az alábbi űrlapot!</p>
        <form action="#" method="post">
            <label for="name">Név:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Üzenet:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Küldés</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Kilián. Minden jog fenntartva.</p>
    </footer>
</body>
</html>
