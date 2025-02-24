<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fußballer der Welt</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
        }
        .player {
            display: flex;
            align-items: center;
            margin: 20px 0;
        }
        .player img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
            margin-right: 20px;
        }
        .player-info {
            flex-grow: 1;
        }
        .player-name {
            font-size: 24px;
            font-weight: bold;
        }
        .player-position {
            font-size: 18px;
            color: #666;
        }
    </style>
</head>
<body>

<header>
    <h1>Bekannte Fußballer der Welt</h1>
</header>

<div class="container">
    <div class="player">
        <img src="https://example.com/player1.jpg" alt="Lionel Messi">
        <div class="player-info">
            <div class="player-name">Lionel Messi</div>
            <div class="player-position">Stürmer - Paris Saint-Germain</div>
        </div>
    </div>
    <div class="player">
        <img src="https://example.com/player2.jpg" alt="Cristiano Ronaldo">
        <div class="player-info">
            <div class="player-name">Cristiano Ronaldo</div>
            <div class="player-position">Stürmer - Al Nassr</div>
        </div>
    </div>
    <div class="player">
        <img src="https://example.com/player3.jpg" alt="Neymar Jr.">
        <div class="player-info">
            <div class="player-name">Neymar Jr.</div>
            <div class="player-position">Stürmer - Al Hilal</div>
        </div>
    </div>
    <div class="player">
        <img src="https://example.com/player4.jpg" alt="Kylian Mbappé">
        <div class="player-info">
            <div class="player-name">Kylian Mbappé</div>
            <div class="player-position">Stürmer - Paris Saint-Germain</div>
        </div>
    </div>
</div>

</body>
</html>
