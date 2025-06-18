<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Loja de Muchade Fashion</title>
  <style>
    /* Reset básico */
    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fafafa;
      color: #222;
      line-height: 1.6;
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }
    header {
      text-align: center;
      padding: 30px 0 20px;
      border-bottom: 1px solid #ddd;
    }
    header h1 {
      font-weight: 700;
      font-size: 2.5rem;
      color: #111;
      letter-spacing: 2px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.1rem;
      color: #555;
    }
    .banner {
      margin: 40px 0;
      background: #e3e8f0;
      border-radius: 8px;
      padding: 30px;
      text-align: center;
      color: #374151;
      font-size: 1.3rem;
      font-weight: 600;
      box-shadow: 0 2px 6px rgb(0 0 0 / 0.1);
    }
    main {
      margin-top: 30px;
    }
    h2 {
      margin-bottom: 20px;
      font-size: 2rem;
      border-bottom: 2px solid #ddd;
      padding-bottom: 8px;
      color: #333;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fill,minmax(220px,1fr));
      gap: 20px;
    }
    .produto {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 1px 3px rgb(0 0 0 / 0.05);
      transition: box-shadow 0.3s ease;
    }
    .produto:hover {
      box-shadow: 0 4px 8px rgb(0 0 0 / 0.15);
    }
    .produto img {
      width: 100%;
      border-radius: 6px;
      margin-bottom: 12px;
      object-fit: cover;
      height: 200px;
    }
    .produto h3 {
      font-size: 1.2rem;
      color: #111;
      margin-bottom: 8px;
    }
    .produto p {
      font-size: 0.9rem;
      color: #666;
      margin-bottom: 12px;
      min-height: 48px;
    }
    .produto .preco {
      font-weight: 700;
      color: #111;
      font-size: 1.1rem;
    }
    footer {
      margin-top: 50px;
      text-align: center;
      color: #888;
      font-size: 0.9rem;
      border-top: 1px solid #ddd;
      padding: 20px 10px 10px;
    }
    a.contato-link {
      color: #374151;
      text-decoration: none;
      font-weight: 600;
    }
    a.contato-link:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<header>
  <h1>Loja de Muchade Fashion</h1>
  <p>Moda jovem para quem quer estilo, atitude e autenticidade</p>
</header>

<section class="banner">
  Vista-se como quiser. Brilhe como merece. ✨
</section>

<main>
  <section>
    <h2>Produtos em destaque</h2>
    <div class="produtos">
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Vestido+Feminino" alt="Vestido Feminino" />
        <h3>Vestido Floral</h3>
        <p>Leve e elegante, perfeito para o dia a dia ou eventos.</p>
        <div class="preco">2.500 MZN</div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Camiseta+Masculina" alt="Camiseta Masculina" />
        <h3>Camiseta Básica</h3>
        <p>Conforto e estilo para todas as ocasiões.</p>
        <div class="preco">1.200 MZN</div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Brincos" alt="Brincos" />
        <h3>Brincos Delicados</h3>
        <p>Toque final para qualquer look com charme e simplicidade.</p>
        <div class="preco">750 MZN</div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Rel%C3%B3gio" alt="Relógio" />
        <h3>Relógio Minimalista</h3>
        <p>Design clean que combina com tudo.</p>
        <div class="preco">3.000 MZN</div>
      </div>
    </div>
  </section>

  <section style="margin-top:40px;">
    <h2>Contato</h2>
    <p>Quer saber mais? Fale conosco pelo WhatsApp ou Instagram:</p>
    <p><a href="https://wa.me/258XXXXXXXXX" target="_blank" class="contato-link">WhatsApp</a> | <a href="https://instagram.com/seuusuario" target="_blank" class="contato-link">Instagram</a></p>
  </section>
</main>

<footer>
  &copy; 2025 Loja de Muchade Fashion - Todos os direitos reservados
</footer>

</body>
</html>
# Loja-muchade-
Loja muchade 
