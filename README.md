# Roberto-fernandez   <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mr. Peter Griffin Game</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-image: url('https://i.imgur.com/G8n8oLR.jpeg'); /* Peter Griffin background */
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      color: white;
    }
    header {
      background-color: #39ff14;
      color: black;
      padding: 15px;
      text-align: center;
      font-size: 24px;
      font-weight: bold;
      border-bottom: 4px solid white;
    }
    .game-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .game {
      background: rgba(0, 0, 0, 0.6);
      border: 2px solid white;
      border-radius: 10px;
      margin: 10px;
      padding: 10px;
      width: 140px;
      text-align: center;
      transition: transform 0.3s;
    }
    .game:hover {
      transform: scale(1.1);
    }
    .game img {
      width: 100%;
      border-radius: 8px;
    }
    .game a {
      display: block;
      margin-top: 8px;
      color: #39ff14;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>Mr. Peter Griffin Game – Made by Amber and Roberto</header>

  <div class="game-container">

    <div class="game">
      <img src="https://i.imgur.com/PF9qLxL.png" alt="Game 1">
      <a href="https://example1.com" target="_blank">Play Game 1</a>
    </div>

    <div class="game">
      <img src="https://i.imgur.com/wVm9IuQ.png" alt="Game 2">
      <a href="https://example2.com" target="_blank">Play Game 2</a>
    </div>

    <div class="game">
      <img src="https://i.imgur.com/7OZKX7B.png" alt="Game 3">
      <a href="https://example3.com" target="_blank">Play Game 3</a>
    </div>

    <div class="game">
      <img src="https://i.imgur.com/oytvhVE.png" alt="Game 4">
      <a href="https://example4.com" target="_blank">Play Game 4</a>
    </div>

    <div class="game">
      <img src="https://i.imgur.com/L8VdVwq.png" alt="Game 5">
      <a href="https://example5.com" target="_blank">Play Game 5</a>
    </div>

    <!-- Add more games below following same format -->
    
  </div>
</body>
</html>
  
