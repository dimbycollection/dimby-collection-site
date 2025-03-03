<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dimby Collection</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
      padding-bottom: 60px; /* espace pour le footer fixe */
    }
    header {
      background-color: #007BFF;
      color: #fff;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 60px; /* ajustez la taille du logo si nécessaire */
    }
    header h1 {
      margin: 0;
      font-size: 1.5rem;
      padding-left: 10px;
    }
    nav {
      background-color: #0056b3;
      display: flex;
      justify-content: center;
      padding: 10px;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 5px 15px;
      font-size: 16px;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      margin-top: 0;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
      justify-content: center;
    }
    .gallery img {
      width: 300px; /* ajustez la taille selon vos préférences */
      max-width: 100%;
      border: 2px solid #ccc;
      border-radius: 5px;
    }
    footer {
      background-color: #007BFF;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <!-- Logo et titre -->
    <img src="images/logo.jpg" alt="Logo Dimby Collection">
    <h1>Dimby Collection</h1>
  </header>
  
  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#apropos">À propos</a>
    <a href="#services">Services</a>
    <a href="#galerie">Galerie</a>
    <a href="#contact">Contact</a>
    <!-- Lien vers la partie admin, à configurer séparément -->
    <a href="/admin">Admin</a>
  </nav>
  
  <main>
    <!-- Accueil -->
    <section id="accueil">
      <h2>Accueil</h2>
      <p>Bienvenue sur le site de Dimby Collection, votre spécialiste dans la production d'uniformes pour écoles et universités. Nous offrons des produits de qualité adaptés aux besoins du secteur éducatif.</p>
    </section>
    
    <!-- À propos -->
  <section id="apropos">
      <h2>À propos</h2>
      <p>Dimby Collection est une entreprise dédiée à la fabrication d'uniformes scolaires, de blouses et de tenues de stage. Notre expertise nous permet de créer des produits confortables, résistants et personnalisables pour répondre aux exigences de chaque établissement.</p>
      <p>Petit détail sympa : notre chien se trouve actuellement à Antsirabe, Madagascar, pour nous tenir compagnie lors de nos déplacements !</p>
    </section>
    
    <!-- Services -->
   <section id="services">
      <h2>Services</h2>
      <ul>
        <li>Fabrication d'uniformes scolaires sur mesure</li>
        <li>Conception d'uniformes universitaires adaptés</li>
        <li>Création de blouses et de tenues de stage</li>
        <li>Personnalisation et branding</li>
      </ul>
    </section>
    
    <!-- Galerie -->
  <section id="galerie">
      <h2>Galerie</h2>
      <p>Découvrez quelques-unes de nos réalisations :</p>
      <div class="gallery">
        <!-- Remplacez les chemins et les attributs alt par ceux de vos images -->
        <img src="https://github.com/dimbycollection/dimbycollection/blob/main/toge.jpg" alt="Exemple de tenue de Dimby Collection">
        <img src="https://github.com/dimbycollection/dimbycollection/blob/main/produit3.jpg" alt="Exemple de blouse de Dimby Collection">
        <img src="https://github.com/dimbycollection/dimbycollection/blob/main/blouse.jpg" alt="Uniforme scolaire Dimby Collection">
      </div>
    </section>
    
    <!-- Contact -->
    <section id="contact">
      <h2>Contact</h2>
      <p>Pour toute demande d'information ou pour obtenir un devis, contactez-nous :</p>
      <p>Email : <a href="mailto:dimbycollection@gmail.com">dimbycollection@gmail.com</a></p>
      <p>Téléphone : <a href="tel:+261343555602">+261 34 355 5602</a></p>
    </section>
  </main>
  
  <footer>
    <p>&copy; 2025 Dimby Collection. Tous droits réservés.</p>
  </footer>
</body>
</html>
