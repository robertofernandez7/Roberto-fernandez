# Roberto fernandez <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mr. Peter Griffin Game – Made by Amber and Roberto</title>
  <!-- Google Classroom favicon -->
  <link rel="icon" type="image/png" href="google-classroom-icon.png">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-image: url('https://sstournamentdesigns.neocities.org/CartoonCharacters/Graphics/pg16/bg6_pg16.jpg');
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      color: white;
    }
    header {
      background-color: #39FF14;
      color: #000;
      text-align: center;
      padding: 20px;
      font-size: 2em;
      font-weight: bold;
    }
    .subtitle {
      text-align: center;
      color: #39FF14;
      font-size: 1em;
      margin-bottom: 20px;
    }
    .game-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 15px;
      padding: 10px;
    }
    .game {
      background: rgba(0,0,0,0.6);
      border-radius: 8px;
      overflow: hidden;
      text-align: center;
      transition: transform 0.2s;
    }
    .game:hover { transform: scale(1.05); }
    .game img {
      width: 100%;
      display: block;
    }
    .game a {
      display: block;
      padding: 8px;
      color: #39FF14;
      text-decoration: none;
      font-weight: bold;
    }
    .section-title {
      margin: 30px 0 10px;
      text-align: center;
      font-size: 1.5em;
      color: #39FF14;
    }
    .proxies {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      padding: 20px;
    }
    .proxy-btn {
      background: #000;
      color: #39FF14;
      text-decoration: none;
      padding: 10px 20px;
      border-radius: 6px;
      font-weight: bold;
      transition: background 0.2s;
    }
    .proxy-btn:hover {
      background: #39FF14;
      color: #000;
    }
    footer {
      text-align: center;
      color: #ccc;
      padding: 20px 0;
      font-size: 0.9em;
    }
    /* Block back button */
    <script>
      history.pushState(null, null, location.href);
      window.onpopstate = ()=> history.go(1);
    </script>
  </style>
</head>
<body>

  <header>Mr. Peter Griffin Game</header>
  <div class="subtitle">Made by Amber and Roberto</div>

  <!-- Games Grid -->
  <div class="game-grid">
    <div class="game">
      <a href="https://tinyurl.com/robbballstars" target="_blank">
        <img src="https://static.vecteezy.com/system/resources/previews/002/371/643/non_2x/vector-basketball-icon.jpg" alt="Basketball Stars">
        Basketball Stars
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robsnowrider3d" target="_blank">
        <img src="https://via.placeholder.com/150?text=Snow+Rider+3D" alt="Snow Rider 3D">
        Snow Rider 3D
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robsubwaysurfers" target="_blank">
        <img src="https://play-lh.googleusercontent.com/C9yctHz94zz4GLYZ_QDRZKN4oD5OSJW99moQtTjG1RhyFik6xP-iY34Pp7PGQikUsg" alt="Subway Surfers">
        Subway Surfers
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robrun3" target="_blank">
        <img src="https://play-lh.googleusercontent.com/XxkSPlKxNcN9GfjQHwzO7yoNUw2G8PpPzK6np5Z6SxDbxexmFQyHTD7qPSHPWB9JIQ" alt="Run 3">
        Run 3
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robtemplerun2" target="_blank">
        <img src="https://via.placeholder.com/150?text=Temple+Run+2" alt="Temple Run 2">
        Temple Run 2
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robgeometrydash" target="_blank">
        <img src="https://via.placeholder.com/150?text=Geometry+Dash" alt="Geometry Dash">
        Geometry Dash
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robbitlife" target="_blank">
        <img src="https://play-lh.googleusercontent.com/H8Y3pxK9rhr7CuYhzRQMXbg1Hcf7hV2MQ67A3yZMNxvGmJ9fHkHVO7ZDnh6HGqekzw" alt="BitLife">
        BitLife
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robcookieclicker" target="_blank">
        <img src="https://via.placeholder.com/150?text=Cookie+Clicker" alt="Cookie Clicker">
        Cookie Clicker
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robdrivemad" target="_blank">
        <img src="https://via.placeholder.com/150?text=Drive+Mad" alt="Drive Mad">
        Drive Mad
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robclusterrush" target="_blank">
        <img src="https://via.placeholder.com/150?text=Cluster+Rush" alt="Cluster Rush">
        Cluster Rush
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robfnaf1" target="_blank">
        <img src="https://cdn.mobygames.com/covers/8366332-five-nights-at-freddys-mobile-front-cover.jpg" alt="FNaF 1">
        Five Nights at Freddy’s 1
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robfnaf2" target="_blank">
        <img src="https://via.placeholder.com/150?text=FNaF+2" alt="FNaF 2">
        Five Nights at Freddy’s 2
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robfnaf3" target="_blank">
        <img src="https://via.placeholder.com/150?text=FNaF+3" alt="FNaF 3">
        Five Nights at Freddy’s 3
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robfnaf4" target="_blank">
        <img src="https://via.placeholder.com/150?text=FNaF+4" alt="FNaF 4">
        Five Nights at Freddy’s 4
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robfnf" target="_blank">
        <img src="https://via.placeholder.com/150?text=FNF" alt="Friday Night Funkin’">
        Friday Night Funkin’
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robmcclassic" target="_blank">
        <img src="https://via.placeholder.com/150?text=Minecraft+Classic" alt="Minecraft Classic">
        Minecraft Classic
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/rob1v1lol" target="_blank">
        <img src="https://static-cdn.jtvnw.net/ttv-boxart/1v1.lol-285x380.jpg" alt="1v1.LOL">
        1v1.LOL
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robretrobowl" target="_blank">
        <img src="https://via.placeholder.com/150?text=Retro+Bowl" alt="Retro Bowl">
        Retro Bowl
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robjustfall" target="_blank">
        <img src="https://via.placeholder.com/150?text=Just+Fall" alt="Just Fall">
        JustFall.LOL
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robovercoming" target="_blank">
        <img src="https://via.placeholder.com/150?text=Getting+Over+It" alt="Getting Over It">
        Getting Over It
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robshellshockers" target="_blank">
        <img src="https://via.placeholder.com/150?text=Shell+Shockers" alt="Shell Shockers">
        Shell Shockers
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robtunnelrush" target="_blank">
        <img src="https://via.placeholder.com/150?text=Tunnel+Rush" alt="Tunnel Rush">
        Tunnel Rush
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robstackbump3d" target="_blank">
        <img src="https://via.placeholder.com/150?text=Stack+Bump+3D" alt="Stack Bump 3D">
        Stack Bump 3D
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robdriftboss" target="_blank">
        <img src="https://via.placeholder.com/150?text=Drift+Boss" alt="Drift Boss">
        Drift Boss
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robsmashkarts" target="_blank">
        <img src="https://via.placeholder.com/150?text=Smash+Karts" alt="Smash Karts">
        Smash Karts
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robslope" target="_blank">
        <img src="https://static.wikia.nocookie.net/slope/images/f/fd/Slope-game-icon.png" alt="Slope">
        Slope
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robwhg" target="_blank">
        <img src="https://via.placeholder.com/150?text=World’s+Hardest+Game" alt="World’s Hardest Game">
        World’s Hardest Game
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robmotox3m" target="_blank">
        <img src="https://images.crazygames.com/games/moto-x3m/cover-1592488384138.png" alt="Moto X3M">
        Moto X3M
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robpaperio2" target="_blank">
        <img src="https://via.placeholder.com/150?text=Paper.io+2" alt="Paper.io 2">
        Paper.io 2
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robtictactoe" target="_blank">
        <img src="https://via.placeholder.com/150?text=Tic+Tac+Toe" alt="Tic Tac Toe">
        Tic Tac Toe
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robdino" target="_blank">
        <img src="https://via.placeholder.com/150?text=Chrome+Dino" alt="Google Dino">
        Google Dino
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robtetris" target="_blank">
        <img src="https://via.placeholder.com/150?text=Tetris" alt="Tetris">
        Tetris
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/rob2048" target="_blank">
        <img src="https://via.placeholder.com/150?text=2048" alt="2048">
        2048
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robvex6" target="_blank">
        <img src="https://via.placeholder.com/150?text=Vex+6" alt="Vex 6">
        Vex 6
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robzombsroyale" target="_blank">
        <img src="https://via.placeholder.com/150?text=Zombs+Royale" alt="Zombs Royale">
        Zombs Royale
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robcrossyroad" target="_blank">
        <img src="https://via.placeholder.com/150?text=Crossy+Road" alt="Crossy Road">
        Crossy Road
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robamongus" target="_blank">
        <img src="https://via.placeholder.com/150?text=Among+Us" alt="Among Us">
        Among Us (Web)
      </a>
    </div>
    <div class="game">
      <a href="https://tinyurl.com/robdrawthehill" target="_blank">
        <img src="https://via.placeholder.com/150?text=Draw+the+Hill" alt="Draw the Hill">
        Draw the Hill
      </a>
    </div>
  </div>

  <!-- Proxies Section -->
  <div class="section-title">Proxies (School Bypass)</div>
  <div class="proxies">
    <a class="proxy-btn" href="https://ubg98.github.io/" target="_blank">ubg98.github.io</a>
    <a class="proxy-btn" href="https://classroom6x.com/" target="_blank">classroom6x.com</a>
    <a class="proxy-btn" href="https://3kh0.github.io/" target="_blank">3kh0.github.io</a>
    <a class="proxy-btn" href="https://sites.google.com/view/classroom6x/" target="_blank">sites.google.com/view/classroom6x</a>
    <a class="proxy-btn" href="https://mathgames66.github.io/" target="_blank">mathgames66.github.io</a>
    <a class="proxy-btn" href="https://urlebird.com" target="_blank">urlebird.com (TikTok)</a>
  </div>

  <footer>&copy; 2025 Amber & Roberto. All rights reserved.</footer>
</body>
</html>
