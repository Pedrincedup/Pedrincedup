<img src="https://media.tenor.com/I8EYt8fJnNYAAAAM/bumble-bee.gif" alt="Bumble Bee" class="rounded-border">
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Palmeiras - O Maior Campeão do Brasil</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      /* Background com foto oficial do Allianz Parque (Palmeiras) */
      background-image: url('https://images.alphacoders.com/130/1308599.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      
      min-height: 100vh;
      font-family: 'Arial', sans-serif;
      color: white;
      position: relative;
    }

    /* Camada escura para melhorar legibilidade */
    body::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 40, 0, 0.7); /* Verde do Palmeiras com transparência */
      z-index: 1;
    }

    .container {
      position: relative;
      z-index: 2;
      text-align: center;
      padding: 100px 20px;
    }

    h1 {
      font-size: 3.5rem;
      margin-bottom: 1rem;
      text-shadow: 0 0 10px rgba(0, 0, 0, 0.8);
    }

    p {
      font-size: 1.5rem;
      margin-bottom: 2rem;
    }

    .btn {
      background: #006633;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.2rem;
      font-weight: bold;
      border-radius: 50px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #008040;
      transform: scale(1.05);
    }

    .logo {
      width: 80px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <div class="container">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Palmeiras_logo.svg/1200px-Palmeiras_logo.svg.png" alt="Palmeiras" class="logo">
    <h1>Sociedade Esportiva Palmeiras</h1>
    <p>O Maior Campeão do Brasil</p>
    <button class="btn">Seja Sócio Avanti</button>
  </div>

</body>
</html>
