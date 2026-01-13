<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Wesley Stadler — Portfólio</title>

  <style>
    :root{
      --bg:#0f172a;
      --card:#111827;
      --accent:#f59e0b;
      --muted:#94a3b8;
      --text:#f8fafc;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:Arial,Helvetica,sans-serif;
      background:var(--bg);
      color:var(--text);
    }
    header{
      padding:48px 16px;
      text-align:center;
      background:#0b1220;
    }
    header h1{margin:0;font-size:34px}
    header p{margin-top:8px;color:var(--muted)}
    main{
      max-width:1200px;
      margin:32px auto;
      padding:0 16px;
    }
    h2{
      color:var(--accent);
      border-left:6px solid var(--accent);
      padding-left:10px;
      margin:40px 0 16px;
    }
    ul{color:var(--muted)}
    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(350px, 1fr));
      gap:24px;
    }
    .card{
      background:var(--card);
      border-radius:10px;
      overflow:hidden;
      box-shadow:0 6px 20px rgba(0,0,0,.6);
      text-align:center;
    }
    .card img,
    .card iframe,
    .card video{
      width:100%;
      max-height:360px;
      object-fit:contain;
      display:block;
      background:#000;
      border:none;
    }
    .card-body{padding:14px}
    .card-body h3{margin:0 0 6px;font-size:18px}
    .card-body p{margin:0;color:#d1d5db;font-size:14px}
    .card-body a{
      display:inline-block;
      margin-top:8px;
      color:var(--accent);
      font-weight:bold;
      text-decoration:none;
    }
    footer{
      margin-top:48px;
      padding:24px;
      text-align:center;
      background:#071018;
      color:var(--muted);
    }
    @media(max-width:768px){
      .grid{grid-template-columns:1fr}
    }
  </style>
</head>

<body>

<header>
  <h1>Wesley Stadler</h1>
  <p>Cursando Design (UNISO — Noturno)</p>
</header>

<main>

<section>
  <h2>💡 Sobre mim</h2>
  <p>
    Estou cursando Design na UNISO, possuo 7 anos de experiência com produção de mídia e arte-finalismo.
    Trabalho com criação gráfica, edição de vídeos curtos e longos para redes sociais
    e busco oportunidades alinhadas à área que estou cursando.
  </p>

  <h2>🚀 Habilidades</h2>
  <ul>
    <li>Corel Draw</li>
    <li>Photoshop / Illustrator</li>
    <li>CapCut</li>
    <li>Premiere</li>
  </ul>
</section>

<!-- PROJETOS -->
<h2>🎨 Projetos</h2>
<div class="grid">

  <div class="card">
    <img src="https://github.com/user-attachments/assets/22a49177-0a6a-4f6b-b8f1-a7fd649f73f7">
    <div class="card-body">
      <h3>Tag / Etiqueta</h3>
      <p>Etiqueta para produto</p>
    </div>
  </div>

  <div class="card">
    <img src="https://github.com/user-attachments/assets/dc327707-d8b2-4598-943d-08c415103a9a">
    <div class="card-body">
      <h3>Campanha Barbearia</h3>
      <p>Retífica da Barba — Social Media</p>
    </div>
  </div>

  <div class="card">
    <img src="https://github.com/user-attachments/assets/4119bafc-da55-4011-a4a5-8cb6d3b6e0e3">
    <div class="card-body">
      <h3>Barbeiro a Domicílio</h3>
      <p>Flyer promocional</p>
    </div>
  </div>

  <div class="card">
    <img src="https://github.com/user-attachments/assets/4ea6fbd5-e917-400c-93f2-d29d5db2a9d9">
    <img src="https://github.com/user-attachments/assets/f724696e-1ce3-41fa-9c6c-5924c5ff40c6">
    <div class="card-body">
      <h3>Dia dos Namorados</h3>
      <p>Arte + Mockup</p>
    </div>
  </div>

  <div class="card">
    <img src="https://github.com/user-attachments/assets/95d5cc83-4dcc-4f7f-89a6-69961e62e5d3">
    <img src="https://github.com/user-attachments/assets/9fc6bdd9-ca87-44da-8131-f7b2e8170803">
    <div class="card-body">
      <h3>Cartão de Visita — Seguros</h3>
      <p>Identidade corporativa</p>
    </div>
  </div>

  <div class="card">
    <img src="https://github.com/user-attachments/assets/f054370c-6c42-44d4-8318-4b2f365993a5">
    <img src="https://github.com/user-attachments/assets/09d7538b-fb2a-45ca-9864-ddf3380abe62">
    <div class="card-body">
      <h3>Headers para Web</h3>
      <p>Desktop e Mobile</p>
    </div>
  </div>

</div>

<!-- PDFs -->
<h2>📘 Editorial</h2>
<div class="grid">

  <div class="card">
    <iframe src="arquivos/Manual-de-preparo-Bebidas-Geladas-Lat-Cafe.pdf"></iframe>
    <div class="card-body">
      <h3>Manual – Bebidas Geladas</h3>
      <a href="arquivos/Manual-de-preparo-Bebidas-Geladas-Lat-Cafe.pdf" target="_blank">Abrir PDF</a>
    </div>
  </div>

  <div class="card">
    <iframe src="arquivos/Manual-de-preparo-Bebidas-Quentes-Lat-Cafe.pdf"></iframe>
    <div class="card-body">
      <h3>Manual – Bebidas Quentes</h3>
      <a href="arquivos/Manual-de-preparo-Bebidas-Quentes-Lat-Cafe.pdf" target="_blank">Abrir PDF</a>
    </div>
  </div>

</div>

<!-- VÍDEOS -->
<h2>🎥 Vídeos</h2>
<div class="grid">

  <div class="card">
    <video controls muted>
      <source src="videos/WhatsApp-Video-2026-01-12-23-05-40.mp4" type="video/mp4">
    </video>
    <div class="card-body">
      <h3>Vídeo Promocional</h3>
      <p>Edição para redes sociais</p>
    </div>
  </div>

  <div class="card">
    <video controls muted>
      <source src="videos/WhatsApp-Video-2026-01-12-23-17-27.mp4" type="video/mp4">
    </video>
    <div class="card-body">
      <h3>Conteúdo Social</h3>
      <p>CapCut / Motion</p>
    </div>
  </div>

</div>

</main>

<footer>
  📱 (15) 99777-0666 • ✉️ wesley.stadler388@gmail.com<br>
  © 2026 Wesley Stadler
</footer>

</body>
</html>

