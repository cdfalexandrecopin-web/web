<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Lycée Exemple</title>

<style>
body {
    font-family: Arial;
    margin: 0;
}

/* Header */
header {
    background-color: #004aad;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Menu */
nav {
    background-color: #333;
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    margin: 15px;
    text-decoration: none;
    font-weight: bold;
}

/* Contenu */
section {
    padding: 20px;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
}
</style>

</head>

<body>

<header>
    <h1>Lycée Exemple</h1>
</header>

<nav>
    <a href="#accueil">Accueil</a>
    <a href="#etablissement">Établissement</a>
    <a href="#formations">Formations</a>
    <a href="#vie">Vie scolaire</a>
    <a href="#contact">Contact</a>
</nav>

<!-- Accueil -->
<section id="accueil">
    <h2>Bienvenue</h2>
    <p>Bienvenue sur le site de notre lycée.</p>
    <ul>
        <li>Portes ouvertes bientôt</li>
        <li>Nouveaux projets pédagogiques</li>
        <li>Sortie scolaire prévue</li>
    </ul>
</section>

<!-- Établissement -->
<section id="etablissement">
    <h2>L’établissement</h2>
    <p>Notre lycée propose un enseignement de qualité depuis plusieurs années.</p>
    <p>Nos valeurs : réussite, respect, innovation.</p>
</section>

<!-- Formations -->
<section id="formations">
    <h2>Formations</h2>
    <h3>BAC PRO CIEL</h3>
    <p>Formation en informatique et réseaux.</p>

    <h3>BTS SIO</h3>
    <p>Formation supérieure en services informatiques.</p>
</section>

<!-- Vie scolaire -->
<section id="vie">
    <h2>Vie scolaire</h2>
    <ul>
        <li>Club informatique</li>
        <li>Club sport</li>
        <li>Projets éducatifs</li>
    </ul>
</section>

<!-- Contact -->
<section id="contact">
    <h2>Contact</h2>
    <p>Adresse : 123 rue du Lycée</p>
    <p>Téléphone : 01 23 45 67 89</p>
    <p>Email : contact@lycee.fr</p>

    <form>
        <input type="text" placeholder="Nom"><br><br>
        <input type="email" placeholder="Email"><br><br>
        <textarea placeholder="Message"></textarea><br><br>
        <button>Envoyer</button>
    </form>
</section>

<footer>
    <p>© 2026 Lycée Exemple</p>
</footer>

</body>
</html>
