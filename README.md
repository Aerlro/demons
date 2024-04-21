<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Discord Bot Commands</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }
        .container {
            width: 100%;
            height: 100vh;
            background: url('black_image.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        h1 {
            font-size: 32px;
            margin-bottom: 20px;
        }
        .command {
            margin-bottom: 20px;
        }
        .command h3 {
            font-size: 24px;
        }
        .command p {
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Discord Bot Commands</h1>
        <div class="command">
            <h3>!win</h3>
            <p>Record a win</p>
        </div>
        <div class="command">
            <h3>!lose</h3>
            <p>Record a loss</p>
        </div>
        <div class="command">
            <h3>!reset</h3>
            <p>Reset game</p>
        </div>
        <div class="command">
            <h3>!set</h3>
            <p>Set configuration</p>
        </div>
        <div class="command">
            <h3>!leaderboard</h3>
            <p>Show leaderboard</p>
        </div>
        <div class="command">
            <h3>!points</h3>
            <p>Show points</p>
        </div>
        <div class="command">
            <h3>!ping</h3>
            <p>Check bot latency</p>
        </div>
    </div>
</body>
</html>
