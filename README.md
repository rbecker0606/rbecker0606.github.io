# rbecker0606.github.io
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Obst- und Geflügelhof Becker - Neustadt</title>
    <style>
        /* Allgemeine Stile */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            padding: 20px;
            color: #fff;
            text-align: center;
        }
        h1, h2, h3 {
            margin: 0;
        }
        /* Navigation */
        nav {
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            color: #4CAF50;
        }
        /* Hauptbereich */
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        /* Hero-Bereich */
        .hero {
            background-image: url('https://example.com/hero-image.jpg'); /* Beispiel-Bild-URL ersetzen */
            background-size: cover;
            background-position: center;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }
        .hero h2 {
            font-size: 2.5em;
        }
        /* Produktbereich */
        .products {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 20px;
        }
        .product-card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 300px;
            text-align: center;
            padding: 15px;
        }
        .product-card img {
            width: 100%;
            border-radius: 8px 8px 0 0;
        }
        /* Über uns Bereich */
        .about {
            background-color: #e8f5e9;
            padding: 40px;
            border-radius: 8px;
            margin-top: 20px;
        }
        /* Kontaktbereich */
        .contact {
            background-color: #f1f1f1;
            padding: 40px;
            border-radius: 8px;
            margin-top: 20px;
        }
        .contact form input, .contact form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        .contact form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Obst- und Geflügelhof Becker</h1>
    <p>Frisches Obst, Geflügel und regionale Produkte aus Neustadt</p>
</header>

<nav>
    <a href="#produkte">Produkte</a>
    <a href="#ueber-uns">Über Uns</a>
    <a href="#kontakt">Kontakt</a>
</nav>

<section class="hero">
    <h2>Frische, Regionalität und Qualität</h2>
    <p>Besuchen Sie uns und genießen Sie die besten Produkte aus der Region.</p>
</section>

<div class="container">
    <!-- Produkte Bereich -->
    <section id="produkte">
        <h2>Unsere Produkte</h2>
        <div class="products">
            <!-- Beispiel Produkt 1 -->
            <div class="product-card">
                <img src="https://example.com/apple.jpg" alt="Frische Äpfel"> <!-- Beispiel-Bild-URL ersetzen -->
                <h3>Frische Äpfel</h3>
                <p>Saftige und knackige Äpfel, direkt vom Baum gepflückt.</p>
            </div>
            <!-- Beispiel Produkt 2 -->
            <div class="product-card">
                <img src="https://example.com/eggs.jpg" alt="Freiland Eier"> <!-- Beispiel-Bild-URL ersetzen -->
                <h3>Freiland Eier</h3>
                <p>Unsere Hühner leben im Freiland und legen täglich frische Eier.</p>
            </div>
        </div>
    </section>

    <!-- Über Uns Bereich -->
    <section id="ueber-uns" class="about">
        <h2>Über Uns</h2>
        <p>Der Obst- und Geflügelhof Becker ist ein Familienbetrieb, der seit über 30 Jahren in Neustadt frische und regionale Produkte anbietet. Unsere Produkte stammen direkt vom Hof und werden mit Liebe und Sorgfalt angebaut und gepflegt.</p>
    </section>

    <!-- Kontaktbereich -->
    <section id="kontakt" class="contact">
        <h2>Kontaktieren Sie Uns</h2>
        <form>
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Nachricht</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Absenden</button>
        </form>
    </section>
</div>

<footer style="background-color: #333; color: white; text-align: center; padding: 20px; margin-top: 20px;">
    <p>&copy; 2023 Obst- und Geflügelhof Becker. Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
