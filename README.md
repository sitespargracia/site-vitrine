<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sites par Gracia</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      position: relative;
      height: 100vh;
      overflow: hidden;
    }

    header img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      filter: brightness(0.6);
    }

    .overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      color: white;
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.6);
      border-radius: 10px;
    }

    .overlay h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    .overlay p {
      font-size: 1.2rem;
      margin: 0;
    }

    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      margin-top: 40px;
    }

    section h2 {
      color: #0080ff;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li::before {
      content: "✔️";
      margin-right: 8px;
    }

    .cta {
      background: #0080ff;
      color: white;
      padding: 12px 25px;
      display: inline-block;
      margin-top: 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      margin-top: 20px;
    }

    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }

    button {
      background-color: #0080ff;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }

    .socials {
      margin-top: 30px;
      text-align: center;
    }

    .socials a {
      margin: 0 10px;
      text-decoration: none;
      color: #0080ff;
      font-weight: bold;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .overlay h1 {
        font-size: 1.8rem;
      }
      .overlay p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="IMG_0616.jpeg" alt="Gracia Mavinga - Création de sites" />
    <div class="overlay">
      <h1>Sites par Gracia</h1>
      <p>Je crée des sites vitrines modernes pour les commerces et les entrepreneurs.</p>
    </div>
  </header>

  <section>
    <h2>Vous n'avez pas encore de site pour votre boutique ?</h2>
    <p>Je vous propose un service simple, rapide et personnalisé pour créer un site vitrine professionnel.</p>
    <ul>
      <li><strong>Site prêt en 1 semaine</strong> : Livraison rapide et efficace</li>
      <li><strong>Prix abordable</strong> : Entre 200 € et 1000 €, selon vos besoins</li>
      <li><strong>Design moderne</strong> : Adapté à votre image de marque</li>
      <li><strong>Interface intuitive</strong> : Facile à utiliser pour vous</li>
      <li><strong>Support réactif</strong> : Assistance avant, pendant et après la création</li>
    </ul>
    <p><strong>Contact :</strong> 07 66 55 74 57</p>
    <p><strong>Email :</strong> mavingag25@gmail.com</p>
    <a class="cta" href="tel:+33766557457">📞 Appelez-moi</a>
  </section>

  <section>
    <h2>Contactez-moi par message</h2>
    <form action="mailto:mavingag25@gmail.com" method="POST" enctype="text/plain">
      <input type="text" name="Nom" placeholder="Votre nom" required>
      <input type="email" name="Email" placeholder="Votre adresse email" required>
      <textarea name="Message" placeholder="Votre message" rows="5" required></textarea>
      <button type="submit">Envoyer le message</button>
    </form>
  </section>

  <section class="socials">
    <h2>Suivez-moi sur les réseaux</h2>
    <a href="https://www.instagram.com/" target="_blank">Instagram</a>
    <a href="https://www.facebook.com/" target="_blank">Facebook</a>
    <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
  </section>

  <footer>
    &copy; 2025 Gracia Mavinga. Tous droits réservés.
  </footer>

</body>
</html>
