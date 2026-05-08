<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>O filme você que escolhe</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #0f5132, #198754, #14532d);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      overflow: hidden;
      position: relative;
    }

    .background-letters {
      position: absolute;
      width: 100%;
      height: 100%;
      overflow: hidden;
      z-index: 0;
      opacity: 0.08;
      font-size: 30px;
      line-height: 40px;
      color: white;
      user-select: none;
      padding: 20px;
    }

    .container {
      position: relative;
      z-index: 1;
      width: 90%;
      max-width: 500px;
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(10px);
      border-radius: 30px;
      padding: 30px;
      text-align: center;
      box-shadow: 0 8px 30px rgba(0,0,0,0.3);
    }

    h1 {
      margin-bottom: 10px;
      font-size: 2rem;
    }

    p {
      margin-bottom: 25px;
      opacity: 0.9;
    }

    .link {
      display: flex;
      align-items: center;
      gap: 15px;
      background: rgba(255,255,255,0.12);
      padding: 15px;
      border-radius: 18px;
      margin-bottom: 15px;
      text-decoration: none;
      color: white;
      transition: 0.3s ease;
    }

    .link:hover {
      transform: scale(1.03);
      background: rgba(255,255,255,0.2);
    }

    .emoji {
      font-size: 28px;
    }

    .heart {
      font-size: 24px;
      margin-top: 15px;
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="background-letters">
    G D G D G D G D G D G D G D G D G D G D G D G D G D G D
    <br><br>
    G D G D G D G D G D G D G D G D G D G D G D G D G D G D
    <br><br>
    G D G D G D G D G D G D G D G D G D G D G D G D G D G D
  </div>

  <div class="container">
    <h1>💚 O filme você que escolhe 💚</h1>
    <p>Escolha um vídeo especial para assistir ✨</p>

    <a class="link" href="https://youtu.be/XY-SXwHI-ys?si=8LZd_YaZX3nC-Atb" target="_blank">
      <div class="emoji">🎬</div>
      <div>Filme 1</div>
    </a>

    <a class="link" href="https://youtu.be/25wXYdzGwbM?si=GhYZdK5AMqeTSs52" target="_blank">
      <div class="emoji">🍿</div>
      <div>Filme 2</div>
    </a>

    <a class="link" href="https://youtu.be/w2rvy4NE1xo?si=NHOItJCchMMYYKb0" target="_blank">
      <div class="emoji">💌</div>
      <div>Filme 3</div>
    </a>

    <a class="link" href="https://youtu.be/uFyI2tW2P64?si=oWB1vx_IXJmk77TU" target="_blank">
      <div class="emoji">🌹</div>
      <div>Filme 4</div>
    </a>

    <a class="link" href="https://youtu.be/lTx_KbL7XUQ?si=knPl1BAWB2FG6eiT" target="_blank">
      <div class="emoji">✨</div>
      <div>Filme 5</div>
    </a>

    <div class="heart">💚 G + D 💚</div>
  </div>
</body>
</html>
