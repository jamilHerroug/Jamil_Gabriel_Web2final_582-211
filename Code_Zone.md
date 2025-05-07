<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Noël dans le Parc</title>
  <link href="https://fonts.googleapis.com/css2?family=EB+Garamond&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'EB Garamond', serif;
      background: #fff;
      border: 10px solid #4caf50;
      padding: 0;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 20px;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .nav {
      display: flex;
      gap: 10px;
    }

    .nav button {
      background-color: #2e5d2e;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      font-size: 14px;
      cursor: pointer;
    }

    .search {
      padding: 10px;
      background: #ccc;
      border: none;
      border-radius: 6px;
    }

    main {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 30px;
    }

    .title {
      font-size: 60px;
      font-weight: bold;
      line-height: 1.2;
    }

    .billet-btn {
      background-color: #2e5d2e;
      color: white;
      padding: 15px 30px;
      border: none;
      border-radius: 8px;
      font-size: 18px;
      margin-top: 20px;
      display: inline-block;
    }

    .mascotte {
      max-height: 250px;
    }

    .infolettre {
      border: 2px solid black;
      padding: 20px;
      margin-top: 20px;
      width: 300px;
    }

    .infolettre h3 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    .infolettre input {
      display: block;
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 2px solid black;
      font-family: 'EB Garamond', serif;
      font-size: 16px;
    }

    .sponsor-banner {
      background: white;
      border: 2px solid black;
      margin: 20px;
      padding: 10px;
      overflow: hidden;
      white-space: nowrap;
      box-sizing: border-box;
    }

    .sponsor-content {
      display: inline-block;
      animation: scroll 20s linear infinite;
    }

    @keyframes scroll {
      from { transform: translateX(100%); }
      to { transform: translateX(-100%); }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Cabin_icon.png" alt="Logo" height="50">
      <h1><span style="color:#2e5d2e;">NOËL</span> <span style="color:#c94a44;">DANS LE PARC</span></h1>
    </div>
    <div class="nav">
      <button>Sapin</button>
      <button>Nouvelles et Infos</button>
      <button>Contacts</button>
    </div>
    <input type="text" placeholder="Rechercher" class="search">
  </header>

  <main>
    <div>
      <div class="title">Noël<br>dans le<br>parc</div>
      <a href="#" class="billet-btn">ACHETER DES BILLETS</a>
    </div>
    <img src="https://i.ibb.co/K9MTX2m/renne-noel.png" alt="Renne" class="mascotte">
    <div class="infolettre">
      <h3>Inscription à l’infolettre</h3>
      <input type="text" placeholder="Prenom">
      <input type="text" placeholder="Nom">
      <input type="email" placeholder="E-Mail">
    </div>
  </main>

  <div class="sponsor-banner">
    <div class="sponsor-content">
      🎁 Merci à nos partenaires : Coca-Cola 🎄 Loto-Québec 🎁 Radio-Canada 🎄 Chocolat Favoris 🎁 Desjardins 🎄 Metro 🎁
    </div>
  </div>
</body>
</html>

