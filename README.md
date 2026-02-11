<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Feliz San Valentín ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      font-family: 'Segoe UI', sans-serif;
      color: white;
      text-align: center;
    }

    .card {
      background: rgba(255,255,255,0.15);
      padding: 40px;
      border-radius: 24px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.2);
      max-width: 400px;
      backdrop-filter: blur(8px);
      animation: fadeIn 1.5s ease;
    }

    h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    .heart {
      font-size: 3rem;
      animation: beat 1.2s infinite;
      margin: 15px 0;
    }

    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Feliz San Valentín 💘</h1>
    <div class="heart">❤️</div>
    <p>
      Este link es solo para decirte algo simple:
      gracias por existir, por quedarte y por hacer mis días más bonitos.
    </p>
    <p>
      Hoy y siempre, tú eres mi lugar favorito.
    </p>
    <p>— Con cariño ✨</p>
  </div>
</body>
</html>
