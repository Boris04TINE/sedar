<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="SEDAR AGENCY - Conseil marketing, branding et stratégie digitale">
    <title>SEDAR AGENCY</title>
    <style>
        /* Palette de couleurs */
        :root {
            --bleu-principal: #1D2A45;
            --bleu-clair: #294a7d;
            --or: #C8A74E;
            --ivoire: #F9F6F1;
            --gris-clair: #E5E5E5;
            --blanc: #FFFFFF;
        }

        /* Styles généraux */
        body {
            font-family: Arial, sans-serif;
            background-color: var(--ivoire);
            margin: 0;
            padding: 0;
        }

        header {
            background-color: var(--bleu-principal);
            padding: 20px 0;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        nav .logo img {
            width: 150px;
        }

        nav ul {
            display: flex;
            gap: 20px;
        }

        nav a {
            color: var(--ivoire);
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: var(--or);
        }

        /* Section d'accueil */
        main {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .intro {
            background-color: var(--blanc);
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
        }

        .intro h1 {
            color: var(--bleu-principal);
            font-size: 36px;
        }

        .intro p {
            font-size: 18px;
            color: var(--gris-clair);
            line-height: 1.6;
        }

        .cta-button {
            background-color: var(--bleu-principal);
            color: var(--ivoire);
            padding: 15px 25px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
        }

        .cta-button:hover {
            background-color: var(--or);
        }

        /* Section Blog */
        section.blog {
            background-color: var(--blanc);
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
        }

        section.blog h2 {
            color: var(--bleu-principal);
        }

        .card {
            background-color: var(--gris-clair);
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .card h3 {
            color: var(--bleu-principal);
        }

        .card p {
            color: var(--gris-clair);
        }

        .card a {
            color: var(--or);
            text-decoration: none;
        }

        /* Section Portfolio */
        section.portfolio {
            background-color: var(--blanc);
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
        }

        section.portfolio h2 {
            color: var(--bleu-principal);
        }

        .portfolio-item {
            background-color: var(--gris-clair);
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        /* Section Contact */
        section.contact {
            background-color: var(--blanc);
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
        }

        section.contact h1 {
            color: var(--bleu-principal);
        }

        .contact-info p {
            color: var(--bleu-principal);
            font-size: 18px;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 8px;
            border: 1px solid var(--gris-clair);
            font-size: 16px;
        }

        form button {
            background-color: var(--bleu-principal);
            color: var(--ivoire);
            padding: 15px 25px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
        }

        form button:hover {
            background-color: var(--or);
        }

        footer {
            background-color: var(--bleu-principal);
            color: var(--ivoire);
            padding: 20px 0;
            text-align: center;
        }

        footer ul {
            list-style: none;
            padding: 0;
        }

        footer ul li {
            display: inline;
            margin: 0 15px;
        }

        footer ul li a {
            color: var(--ivoire);
            text-decoration: none;
        }

        footer ul li a:hover {
            color: var(--or);
        }

        /* Animations */
        .cta-button, nav a {
            transition: all 0.3s ease-in-out;
        }

        .cta-button:hover, nav a:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <nav>
            <div class="logo">
                <img src="C:\Users\HP\Documents\sedar agency\sedar.png" alt="Logo SEDAR AGENCY">
            </div>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Section - Accueil -->
    <main id="accueil">
        <section class="intro">
            <h1>Bienvenue chez SEDAR AGENCY</h1>
            <p>Nous sommes une agence de conseil en marketing digital, branding et stratégie. Notre mission est de vous accompagner dans la croissance de votre entreprise en mettant en place des solutions innovantes et personnalisées.</p>
            <button class="cta-button">Contactez-nous</button>
        </section>
    </main>

    <!-- Section Blog -->
    <section class="blog" id="blog">
        <h2>Notre Blog</h2>
        <div class="card">
            <h3>3 leviers pour booster votre présence digitale</h3>
            <p>Découvrez les actions clés pour faire rayonner votre marque en ligne.</p>
            <a href="C:\Users\HP\Documents\sedar agency\article1.html">Lire l'article &rarr;</a>
        </div>
        <div class="card">
            <h3>Pourquoi le branding est vital pour les PME</h3>
            <p>Construire une identité forte vous distingue et fidélise vos clients.</p>
            <a href="C:\Users\HP\Documents\sedar agency\article2.html">Lire l'article &rarr;</a>
        </div>
        <div class="card">
            <h3>5 erreurs fréquentes en marketing digital</h3>
            <p>Ne tombez plus dans les pièges classiques des campagnes digitales.</p>
            <a href="#">Lire l'article &rarr;</a>
        </div>
    </section>

    <!-- Section Portfolio -->
    <section class="portfolio" id="portfolio">
        <h2>Nos Projets</h2>
        <div class="portfolio-item">
            <h3>Création de site web pour XYZ</h3>
            <p>Un projet complet de stratégie digitale et de développement web.</p>
        </div>
        <div class="portfolio-item">
            <h3>Branding et stratégie pour ABC</h3>
            <p>Redéfinition de l'identité visuelle et stratégie de communication.</p>
        </div>
        <div class="portfolio-item">
            <h3>Campagne marketing pour DEF</h3>
            <p>Optimisation de la présence digitale et acquisition de clients en ligne.</p>
        </div>
    </section>

    <!-- Section Contact -->
    <section class="contact" id="contact">
        <h1>Contactez-nous</h1>
        <div class="contact-info">
            <p><strong>Numéro de téléphone : </strong> 78 191 54 38</p>
            <p><strong>Email : </strong> boristine14@gmail.com</p>
        </div>
        
        <h2>Envoyez-nous un message</h2>
        <form action="https://formsubmit.co/mailto:boristine14@gmail.com" method="post" enctype="text/plain">
            <input type="text" name="nom" placeholder="Votre nom" required>
            <input type="email" name="email" placeholder="Votre email" required>
            <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-nav">
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
        <div class="footer-info">
            <p>&copy; 2025 SEDAR AGENCY. Tous droits réservés.</p>
        </div>
    </footer>

    <!-- JavaScript pour les animations -->
    <script>
        const ctaButton = document.querySelector('.cta-button');
        ctaButton.addEventListener('click', function() {
            window.location.href = '#contact'; // Redirection vers la section Contact
        });
    </script>

</body>
</html>
