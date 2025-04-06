<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>SIN - Solução Inteligente Nativa</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Fonte personalizada -->
  <link href="https://fonts.googleapis.com/css2?family=Rubik&display=swap" rel="stylesheet">
  <style>
    /* Reset e configurações básicas */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Rubik', sans-serif;
      background-color: #f4f6f8;
      color: #333;
      line-height: 1.6;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    ul {
      list-style: none;
    }
    /* Navbar */
    nav {
      background: #4A90E2;
      padding: 10px 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav ul {
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    nav ul li a {
      color: white;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav ul li a:hover {
      color: #ffc107;
    }
    /* Header */
    header {
      background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('header-bg.jpg') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 80px 20px;
      position: relative;
    }
    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }
    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid white;
      margin-top: 20px;
    }
    /* Botão de ação */
    .contact-btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      background-color: #ffc107;
      color: #333;
      border-radius: 5px;
      font-weight: bold;
      transition: background-color 0.3s;
    }
    .contact-btn:hover {
      background-color: #e0a800;
    }
    /* Conteúdo principal */
    main {
      padding: 30px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section {
      margin-bottom: 60px;
    }
    section h2 {
      color: #4A90E2;
      margin-bottom: 20px;
      text-align: center;
      font-size: 2em;
    }
    section p, section ul {
      font-size: 1.1em;
      margin-bottom: 15px;
      text-align: justify;
    }
    /* Ficha técnica e Diferenciais */
    .info-list li {
      margin-bottom: 10px;
    }
    /* Planos */
    .planos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .plano {
      background-color: white;
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 20px;
      flex: 1 1 280px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .plano:hover {
      transform: scale(1.03);
    }
    .plano h3 {
      margin-bottom: 10px;
      color: #4A90E2;
    }
    /* Avisos */
    .aviso {
      background-color: #fff3cd;
      border-left: 5px solid #ffc107;
      padding: 20px;
      border-radius: 5px;
    }
    /* Footer */
    footer {
      background-color: #4A90E2;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
    /* Botão interativo extra */
    .interactive-btn {
      display: inline-block;
      margin: 20px auto;
      padding: 10px 20px;
      background-color: #4A90E2;
      color: white;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .interactive-btn:hover {
      background-color: #357ABD;
    }
    /* Responsividade */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2.5em;
      }
      nav ul {
        flex-direction: column;
        gap: 10px;
      }
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <ul>
      <li><a href="#home">Início</a></li>
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#ficha">Ficha Técnica</a></li>
      <li><a href="#diferenciais">Diferenciais</a></li>
      <li><a href="#planos">Planos</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>
  </nav>

  <!-- Header -->
  <header id="home">
    <h1>SIN</h1>
    <p>Solução Inteligente Nativa – Versão 17.0</p>
    <p><em>"Mais do que um nome, uma experiência completa."</em></p>
    <img src="profile.jpg" alt="Foto de perfil" class="profile-img">
    <br>
    <a href="#contato" class="contact-btn">Fale com o SIN</a>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Sobre -->
    <section id="sobre">
      <h2>Quem é o SIN?</h2>
      <p>
        SIN é um serviço singular, projetado para entregar criatividade, inovação e comprometimento em tudo o que se propõe a fazer. 
        Com uma abordagem moderna e dinâmica, atua com inteligência emocional, pensamento estratégico e paixão pela tecnologia, 
        conectando ideias a soluções reais e impactantes. Sempre em constante evolução, SIN busca se adaptar aos desafios contemporâneos, 
        proporcionando resultados extraordinários.
      </p>
    </section>

    <!-- Ficha Técnica -->
    <section id="ficha">
      <h2>Ficha Técnica</h2>
      <ul class="info-list">
        <li><strong>Idade:</strong> 17 anos</li>
        <li><strong>Localização:</strong> Cláudio - MG</li>
        <li><strong>Modo de operação:</strong> Estudante, profissional em formação e entusiasta da tecnologia</li>
        <li><strong>Missão:</strong> Contribuir com soluções inovadoras que transformem desafios em oportunidades</li>
        <li><strong>Visão:</strong> Ser referência em inovação, colaboração e transformação digital</li>
      </ul>
    </section>

    <!-- Diferenciais -->
    <section id="diferenciais">
      <h2>Diferenciais</h2>
      <ul class="info-list">
        <li>Alta capacidade de adaptação em ambientes desafiadores</li>
        <li>Aprendizado contínuo e autonomia na resolução de problemas</li>
        <li>Comunicação clara, empatia e espírito colaborativo</li>
        <li>Paixão por tecnologia, dados e desenvolvimento de soluções inovadoras</li>
        <li>Visão global, com objetivos e planos de atuação internacional (foco no Canadá 🇨🇦)</li>
      </ul>
    </section>

    <!-- Planos Disponíveis -->
    <section id="planos">
      <h2>Planos Disponíveis</h2>
      <div class="planos">
        <div class="plano">
          <h3>Plano Essencial</h3>
          <p>Ideal para auxiliar em tarefas acadêmicas, organização pessoal e geração de ideias criativas para projetos diversos.</p>
        </div>
        <div class="plano">
          <h3>Plano Premium</h3>
          <p>Perfeito para quem precisa de participação ativa em equipes, resolução de problemas complexos e soluções estratégicas.</p>
        </div>
        <div class="plano">
          <h3>Full Upgrade</h3>
          <p>Desempenho máximo: foco absoluto em metas, visão estratégica e comprometimento com projetos de grande impacto.</p>
        </div>
      </div>
    </section>

    <!-- Seção Interativa -->
    <section id="interativo" style="text-align: center;">
      <h2>Interatividade</h2>
      <div class="interactive-btn" id="surpriseBtn">Clique aqui para uma surpresa!</div>
      <p id="surpriseText" style="margin-top:20px; font-size:1.2em;"></p>
    </section>

    <!-- Contato -->
    <section id="contato">
      <h2>Contato</h2>
      <p>
        Se deseja saber mais sobre o SIN, propor parcerias ou simplesmente bater um papo, entre em contato!
      </p>
      <p>Email: <a href="mailto:sin@exemplo.com">sin@exemplo.com</a></p>
      <p>Redes Sociais: 
        <a href="#" target="_blank">Instagram</a> | 
        <a href="#" target="_blank">LinkedIn</a> | 
        <a href="#" target="_blank">GitHub</a>
      </p>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    © 2025 SIN. Uma solução em constante evolução.
  </footer>

  <!-- Scripts -->
  <script>
    // Botão interativo surpresa
    document.getElementById('surpriseBtn').addEventListener('click', function() {
      const mensagens = [
        "Olá! Bem-vindo ao universo SIN!",
        "Pronto para transformar desafios em oportunidades?",
        "Criatividade, inovação e compromisso em um só lugar!",
        "Você acaba de dar o primeiro passo rumo ao futuro!"
      ];
      const mensagem = mensagens[Math.floor(Math.random() * mensagens.length)];
      document.getElementById('surpriseText').textContent = mensagem;
    });

    // Suavizar scroll para links da navbar
    document.querySelectorAll('nav ul li a').forEach(link => {
      link.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
  </script>
</body>
</html>
