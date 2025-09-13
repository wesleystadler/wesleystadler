<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio - Wesley Stadler</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      background: #0f172a;
      color: #f1f5f9;
      margin: 0;
      line-height: 1.6;
    }
    header {
      text-align: center;
      padding: 4rem 1rem;
      background: #1e293b;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
    }
    header p {
      color: #94a3b8;
      font-size: 1.2rem;
    }
    main {
      max-width: 1100px;
      margin: auto;
      padding: 2rem 1rem;
    }
    h2 {
      border-left: 6px solid #38bdf8;
      padding-left: 0.5rem;
      color: #38bdf8;
      margin-bottom: 1rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: #1e293b;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .card-body {
      padding: 1rem;
    }
    .card-body h3 {
      margin-bottom: 0.5rem;
    }
    .card-body p {
      color: #cbd5e1;
      font-size: 0.95rem;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #1e293b;
      color: #94a3b8;
      margin-top: 2rem;
    }
    a {
      color: #38bdf8;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Wesley Stadler</h1>
    <p>Designer Gráfico | Arte-finalista | Estudante de Design (Uniso - Noturno)</p>
  </header>

  <main>
    <section>
      <h2>💡 Sobre mim</h2>
      <p>Tenho 7 anos de experiência em arte-finalismo, criação de materiais gráficos e vetorização. Trabalho principalmente com <strong>Corel Draw</strong>, mas também utilizo <strong>Photoshop, Illustrator e Canva</strong>. Produzo artes para redes sociais, impressos e identidades visuais, além de gravação e edição de vídeos (CapCut e Premiere).</p>
    </section>

    <section>
      <h2>🚀 Habilidades</h2>
      <ul>
        <li>🎨 Arte-finalismo (7 anos de experiência)</li>
        <li>🖌️ Corel Draw, Photoshop, Illustrator, Canva</li>
        <li>📢 Criação de posts, publicidades, folders e readers</li>
        <li>✍️ Vetorização de logotipos e artes</li>
        <li>🎥 Gravação e edição de vídeos curtos e longos</li>
      </ul>
    </section>

    <section>
      <h2>🎨 Projetos</h2>
      <div class="grid">
        <div class="card">
          <img src="post-retifica.png" alt="Arte Retífica da Barba">
          <div class="card-body">
            <h3>Campanha Barbearia</h3>
            <p>Peças para redes sociais e materiais promocionais da barbearia <em>Retífica da Barba</em>.</p>
          </div>
        </div>
        <div class="card">
          <img src="mockup-namorados.png" alt="Mockup Dia dos Namorados">
          <div class="card-body">
            <h3>Dia dos Namorados</h3>
            <p>Arte personalizada e aplicação em mockup de vestuário.</p>
          </div>
        </div>
        <div class="card">
          <img src="cartao-seguros.png" alt="Cartão de Visita Seguros">
          <div class="card-body">
            <h3>Identidade Corporativa</h3>
            <p>Cartões de visita e materiais gráficos para consultoria de seguros.</p>
          </div>
        </div>
        <div class="card">
          <img src="manual-bebidas.png" alt="Manual de Bebidas">
          <div class="card-body">
            <h3>Design Editorial</h3>
            <p>Manual de preparo de bebidas geladas para cafeteria.</p>
          </div>
        </div>
      </div>
    </section>

    <section>
      <h2>📫 Contato</h2>
      <p>📱 Telefone/WhatsApp: <a href="tel:+5515997770666">(15) 99777-0666</a></p>
      <p>📧 Email: <a href="mailto:wesley.stadler388@gmail.com">wesley.stadler388@gmail.com</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/seu-perfil" target="_blank">linkedin.com/in/seu-perfil</a></p>
      <p>Instagram: <a href="https://instagram.com/seuusuario" target="_blank">@seuusuario</a></p>
    </section>
  </main>

  <footer>
    <p>© 2025 Wesley Stadler - Todos os direitos reservados</p>
  </footer>
</body>
</html>

