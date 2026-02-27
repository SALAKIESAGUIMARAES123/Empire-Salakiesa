<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Minha Página Completa</title>
  <style>
    
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: ,N#e2d515;
      color: #333;
    }

    header {
      background-color: #0a0a09;
      color: rgb(163, 132, 30);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 28px;
    }

    nav a {
      color: rgb(129, 111, 30);
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background-image: url('Hacker.jpeg');
      background-size: cover;
      background-position: center;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: rgb(158, 149, 22);
      text-shadow: 2px 2px 5px rgb(0, 0, 0);
      text-align: center;
    }
    

    .hero h2 {
      font-size: 48px;
    }

    .container {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .card {
      background-color:rgb(161, 153, 34);
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card .content {
      padding: 20px;
      text-align: center;
    }

    .card button {
      background-color: #c9bd19;
      color: rgb(0, 0, 0);
      border: none;
      padding: 10px 20px;
      margin-top: 15px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
      transition: background 0.3s;
    }

    .card button:hover {
      background-color: #8b822b;
    }

    footer {
      background-color: #333;
      color: rgb(255, 255, 255);
      padding: 20px;
      text-align: center;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>SALAKIESA EMPIRE</h1>
    <nav>
      <a href="#">Início</a>
      <a href="#">Serviços</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>DOWLOADS RÁPIDO NO CANAL SALAKIESA</h2>
  </section>
  <link rel="stylesheet" href="estilo.css">
  
  <section class="container">
    <h2 style="text-align:center; margin-bottom: 30px;">Galeria de Projetos</h2>
    <div class="grid">
      <div class="card">
        <img src="Captura de ecrã 2020-01-02, às 07.53.21.png" alt="Projeto 1">
        <div class="content">
          <h3>VIDEO AULAS</h3>
          <p>NOVIDADES!</p>
          <button onclick="alert('Você clicou no Projeto 1')">Ver Mais</button>
        </div>
      </div>

      <div class="card">
        <img src="Dispositivo-entrada-saida.jpeg" alt="Projeto 2">
        <div class="content">
          <h3>Tecnologia</h3>
          <p>Saiba agora</p>
          <button onclick="alert('Você clicou no Projeto 2')">Ver Mais</button>
        </div>
      </div>

      <div class="card">
        <img src="20250526_1314_Zumbis em Guerra Apocalíptica_remix_01jw685wgefx9se52zc8n1rf9y 2.png" alt="Projeto 3">
        <div class="content">
          <h3>O MUNDO DIGITAL</h3>
          <p></p>
          <button onclick="alert('Você clicou no Projeto 3')">Ver Mais</button>
          
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 SALALAKIESA. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
