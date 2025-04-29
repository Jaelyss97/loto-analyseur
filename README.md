# loto-analyseur
Application d'analyse des tirages Loto FDJ
loto-analyseur/
├── index.html
├── changelog.html
├── style.css
├── version.txt
└── LotoAnalyseur_v1.0.zip
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>Loto Analyseur Pro</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>Loto Analyseur Pro</h1>
    <p>Analyse les tirages FDJ et génère des grilles optimisées selon les statistiques.</p>

    <a class="btn" href="LotoAnalyseur_v1.0.zip" download>Télécharger la dernière version (.zip)</a>

    <p><a href="changelog.html">Voir le journal des mises à jour</a></p>
    <footer>
      <p>Version actuelle : <strong>1.0</strong> | Dernière mise à jour : Avril 2025</p>
    </footer>
  </div>
</body>
</html>
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f7f9fc;
  color: #333;
  text-align: center;
  margin: 0;
  padding: 0;
}
.container {
  padding: 40px;
}
.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 14px 28px;
  font-size: 18px;
  background-color: #007bff;
  color: white;
  text-decoration: none;
  border-radius: 6px;
}
.btn:hover {
  background-color: #0056b3;
}
footer {
  margin-top: 40px;
  font-size: 14px;
  color: #666;
}
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>Changelog - Loto Analyseur Pro</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>Journal des mises à jour</h1>

    <h3>v1.0 - Avril 2025</h3>
    <ul>
      <li>Import de fichiers CSV FDJ</li>
      <li>Analyse des fréquences de numéros</li>
      <li>Génération de grilles optimisées (3 modes)</li>
      <li>Interface graphique simple</li>
      <li>Création d’un installateur Windows + zip partageable</li>
    </ul>

    <p><a href="index.html">← Retour à l’accueil</a></p>
  </div>
</body>
</html>
1.0
