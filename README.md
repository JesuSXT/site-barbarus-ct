# site-barbarus-ct
site front demonstrativo
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Barbarus CT</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f0f0f;
      color: #fff;
      line-height: 1.6;
    }

    header {
      position: fixed;
      width: 100%;
      top: 0;
      background: #000;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      z-index: 1000;
    }

    header h1 {
      color: #ff3c00;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff3c00;
    }

    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9));
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    .hero p {
      margin-bottom: 20px;
    }

    .btn {
      padding: 12px 25px;
      background: #ff3c00;
      color: #fff;
      border: none;
      cursor: pointer;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #ff5e2e;
    }

    section {
      padding: 80px 30px;
      max-width: 1100px;
      margin: auto;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }

    .reviews {
      display: grid;
      gap: 20px;
      margin-top: 20px;
    }

    .review {
      background: #1a1a1a;
      padding: 15px;
      border-left: 4px solid #ff3c00;
    }

    footer {
      background: #000;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: none;
      margin-top: 20px;
    }

    @media(max-width: 768px) {
      .hero h2 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Barbarus CT</h1>
  <nav>
    <a href="#inicio">Início</a>
    <a href="#sobre">Sobre</a>
    <a href="#estrutura">Estrutura</a>
    <a href="#avaliacoes">Avaliações</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section class="hero" id="inicio">
  <h2>Transforme seu corpo</h2>
  <p>Supere seus limites com treino de alta performance</p>
  <a href="https://wa.me/5521979101050" class="btn">Agende uma aula</a>
</section>

<section id="sobre">
  <h2>Sobre a Academia</h2>
  <p>
    O Barbarus CT é um centro de treinamento focado em evolução constante.
    Contamos com um ambiente acolhedor, professores altamente qualificados
    e treinos personalizados para cada aluno.
  </p>
</section>

<section id="estrutura">
  <h2>Estrutura e Diferenciais</h2>
  <div class="cards">
    <div class="card">Equipamentos de qualidade</div>
    <div class="card">Excelente estrutura</div>
    <div class="card">Treinadores experientes</div>
    <div class="card">Crossfit e musculação</div>
  </div>
</section>

<section id="avaliacoes">
  <h2>Avaliações ⭐ 5.0</h2>
  <div class="reviews">
    <div class="review">"Ótimo ambiente, excelentes professores."</div>
    <div class="review">"Ótima estrutura e equipamentos bons."</div>
    <div class="review">"Depois que você conhece esse CT, o treino deixa de ser obrigação."</div>
  </div>
</section>

<section id="contato">
  <h2>Contato</h2>
  <p><strong>Endereço:</strong> Rua Dênis Emanuel, 158 - Jardim Alvorada</p>
  <p><strong>Telefone:</strong> (21) 97910-1050</p>

  <a href="https://wa.me/5521979101050" class="btn">Fale no WhatsApp</a>

  <iframe 
    src="https://maps.google.com/maps?q=Rua%20Dênis%20Emanuel%20158%20Nova%20Iguaçu&t=&z=13&ie=UTF8&iwloc=&output=embed">
  </iframe>
</section>

<footer>
  <p>© 2026 Barbarus CT - Todos os direitos reservados</p>
</footer>

</body>
</html>
