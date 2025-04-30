<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formateur Pro | Expert en Formation en Ligne</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #0073e6;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        nav {
            background-color: #004a99;
            text-align: center;
            padding: 15px 0;
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background-color: #e6f0ff;
            padding: 60px 20px;
            text-align: center;
        }

        .hero h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.1em;
            max-width: 600px;
            margin: auto;
        }

        .services, .contact {
            max-width: 1000px;
            margin: 60px auto;
            padding: 0 20px;
        }

        .services h2, .contact h2 {
            text-align: center;
            margin-bottom: 40px;
        }

        .service-list {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: space-between;
        }

        .service {
            flex: 1 1 calc(33% - 30px);
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }

        .service h3 {
            margin-top: 0;
            color: #0073e6;
        }

        .contact form {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .contact label {
            display: block;
            margin: 15px 0 5px;
        }

        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .contact button {
            background-color: #0073e6;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            margin-top: 20px;
            cursor: pointer;
        }

        footer {
            background-color: #004a99;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 60px;
        }

        @media (max-width: 768px) {
            .service-list {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Formateur Pro</h1>
        <p>Créateur de formations en ligne | Expertise, pédagogie, résultats</p>
    </header>

    <nav>
        <a href="#">Accueil</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h2>Votre expert en création de formations en ligne</h2>
        <p>Je vous accompagne dans la conception, la mise en ligne et la vente de vos formations. Transformez vos connaissances en revenus.</p>
    </section>

    <section class="services" id="services">
        <h2>Mes services</h2>
        <div class="service-list">
            <div class="service">
                <h3>Conception pédagogique</h3>
                <p>Création de parcours de formation efficaces et adaptés à votre public cible.</p>
            </div>
            <div class="service">
                <h3>Production vidéo</h3>
                <p>Enregistrement, montage et mise en ligne de vidéos professionnelles pour vos modules.</p>
            </div>
            <div class="service">
                <h3>Accompagnement technique</h3>
                <p>Intégration sur les plateformes (Teachable, Podia, Moodle, etc.) et assistance personnalisée.</p>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Contactez-moi</h2>
        <form>
            <label for="name">Nom</label>
            <input type="text" id="name" name="name" placeholder="Votre nom">

            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Votre adresse email">

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" placeholder="Expliquez-moi votre projet..."></textarea>

            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        &copy; 2025 Formateur Pro. Tous droits réservés.
    </footer>

</body>
</html>
