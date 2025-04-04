<!DOCTYPE html>
<html lang="fr">
<head>
  <nav>
  <a href="#">Accueil</a>
  <a href="#">Produits</a>
  <a href="#">Avis</a>
  <a href="#">À Propos</a>
  <a href="#">Contact</a>
  <span id="cart">Panier (0)</span>
</nav>
  <button onclick="addToCart()">Ajouter au panier</button>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Prudhommesvente</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">Prudhommesvente</div>
    
  </header>

  <section class="hero">
    <h1>Précision et Style au Bout des Doigts</h1>
    <p>Découvrez nos tondeuses 2 en 1 pour cheveux et barbe</p>
    <a href="#produits" class="cta-button">Voir nos produits</a>
  </section>

  <section id="produits" class="products">
    <h2>Nos Produits</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://via.placeholder.com/200x200" alt="Tondeuse">
        <h3>Tondeuse 2 en 1</h3>
        <p>Pratique, élégante et précise</p>
        <button>Acheter maintenant</button>
      </div>
      <!-- Tu peux copier ce bloc pour ajouter plus de produits -->
    </div>
  </section>

  <footer>
    <nav>
      <a href="#">Accueil</a>
      <a href="#">Produits</a>
      <a href="#">Avis</a>
      <a href="#">À Propos</a>
      <a href="#">Contact</a>
    </nav>
    <form action="mailto:borismbytha@gmail.com" method="post" enctype="text/plain">
    <p>&copy; 2025 Prudhommesvente. Tous droits réservés.</p>
  </footer>
</body>
</html>
