<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jeux d'Entraînement au Temps de Réaction</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Jeux d'Entraînement au Temps de Réaction</h1>
    <div class="game-container" id="reaction-time-container">
        <h2>Jeu de Réaction au Changement de Couleur</h2>
        <div id="reaction-time-game" onclick="recordReactionTime()">
            <p id="reaction-time-message">Cliquez ici quand la couleur change</p>
        </div>
        <p id="reaction-time-result"></p>
    </div>
    <div class="game-container" id="target-game-container">
        <h2>Jeu de Cibles</h2>
        <div id="target-game">
            <button onclick="startTargetGame()">Démarrer le jeu</button>
        </div>
        <p id="target-game-result"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>



