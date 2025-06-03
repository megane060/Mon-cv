# Mon-cv<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Formulaire Stylisé</title>
  <style>
    body {
      background-color: #f0f4f8;
      font-family: Arial, sans-serif;
    }

    form {
      background-color: #ffffff;
      width: 350px;
      margin: 50px auto;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h2 {
      text-align: center;
      color: #333;
    }

    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
      color: #333;
    }

    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }

    .genre-options {
      margin-top: 10px;
    }

    .genre-options input {
      margin-right: 5px;
    }

    .buttons {
      margin-top: 20px;
      display: flex;
      justify-content: space-between;
    }

    button {
      width: 48%;
      padding: 10px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    button[type="submit"] {
      background-color: #4CAF50;
      color: white;
    }

    button[type="reset"] {
      background-color: #f44336;
      color: white;
    }

    button:hover {
      opacity: 0.9;
    }
  </style>
</head>
<body>

  <form action="#" method="post">
    <h2>Formulaire</h2>

    <label for="nom">Nom *</label>
    <input type="text" id="nom" name="nom" required>

    <label for="prenom">Prénom *</label>
    <input type="text" id="prenom" name="prenom" required>

    <label>Genre *</label>
    <div class="genre-options">
      <input type="radio" id="masculin" name="genre" value="masculin" required>
      <label for="masculin" style="display:inline;">Masculin</label>

      <input type="radio" id="feminin" name="genre" value="feminin" required>
      <label for="feminin" style="display:inline;">Féminin</label>
    </div>

    <label for="password">Mot de passe *</label>
    <input type="password" id="password" name="password" required>

    <div class="buttons">
      <button type="submit">Valider</button>
      <button type="reset">Annuler</button>
    </div>
  </form>

</body>
</html>
