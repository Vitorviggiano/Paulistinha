<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Chaveiro Paulistinha e Auto Vidros</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #0d47a1;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px 20px;
      transition: all 0.3s ease-in-out;
    }
    .container {
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #0d47a1;
    }
    ul {
      padding-left: 20px;
    }
    .btn {
      display: inline-block;
      margin: 10px 10px 0 0;
      padding: 10px 20px;
      background: #0d47a1;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .btn:hover {
      background: #1565c0;
    }
    footer {
      background: #0d47a1;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .mapa iframe {
      width: 100%;
      height: 300px;
      border: 0;
    }
    .servicos {
      background: #e3f2fd;
      border-left: 5px solid #0d47a1;
      padding: 20px;
      border-radius: 8px;
    }
    .contato-icons i {
      margin-right: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>Chaveiro Paulistinha e Auto Vidros</h1>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section id="sobre" class="container">
  <h2>Sobre Nós</h2>
  <p>Localizado na Rua Siqueira Bueno, 1384, o <strong>Chaveiro Paulistinha e Auto Vidros</strong> oferece serviços rápidos e de confiança em chaves, fechaduras e vidros automotivos. Com anos de experiência e dedicação, buscamos sempre a satisfação de nossos clientes.</p>
</section>

<section id="servicos" class="container servicos">
  <h2>Nossos Serviços</h2>
  <ul>
    <li><i class="fas fa-key"></i> Confecção de chaves comuns e codificadas</li>
    <li><i class="fas fa-door-open"></i> Abertura de veículos e residências</li>
    <li><i class="fas fa-lock"></i> Troca e instalação de fechaduras</li>
    <li><i class="fas fa-car"></i> Vidros automotivos: troca e reparo</li>
    <li><i class="fas fa-lightbulb"></i> Polimento de faróis</li>
  </ul>
</section>

<section id="contato" class="container">
  <h2>Contato</h2>
  <p><strong>Endereço:</strong> Rua Siqueira Bueno, 1384</p>
  <div class="contato-icons">
    <p><i class="fas fa-phone"></i> (11) 99500-5403</p>
    <p><i class="fas fa-phone"></i> (11) 96366-6850</p>
  </div>
  <a class="btn" href="tel:+5511995005403"><i class="fas fa-phone-alt"></i> Ligar agora</a>
  <a class="btn" href="https://wa.me/5511995005403" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>

  <div class="mapa" style="margin-top:30px;">
    <h3>Como chegar:</h3>
    <iframe src="https://www.google.com/maps?q=Rua+Siqueira+Bueno,+1384,+São+Paulo&output=embed" allowfullscreen></iframe>
  </div>
</section>

<footer>
  <p>&copy; 2025 Chaveiro Paulistinha e Auto Vidros. Todos os direitos reservados.</p>
</footer>

</body>
</html>
