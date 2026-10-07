# snakes<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Klasik Yılan Oyunu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="game-container">
        <h1>Yılan Oyunu</h1>
        <div class="score-board">
            <div>Skor: <span id="score">0</span></div>
            <div>En Yüksek Skor: <span id="high-score">0</span></div>
        </div>
        <canvas id="gameCanvas" width="400" height="400"></canvas>
        <button id="start-btn">Oyunu Başlat / Yeniden Başlat</button>
        <p class="controls-hint">Yön tuşları veya W-A-S-D ile oynayabilirsiniz.</p>
    </div>
    <script src="script.js"></script>
</body>
</html>
