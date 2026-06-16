<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Blog Tech</title>

  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      background-color: #ffe4ec;
      color: #4a4a4a;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #ff69b4, #ffb6c1);
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      max-width: 800px;
      margin: 20px auto;
      padding: 0 15px;
    }

    article {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(255, 105, 180, 0.2);
      border: 2px solid #ffb6c1;
    }

    article h2 {
      margin-top: 0;
      color: #ff1493;
    }

    .autor {
      font-size: 0.9rem;
      color: #888;
    }

    .cat {
      font-size: 2.5rem;
      text-align: center;
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      background: #ff69b4;
      color: white;
    }
  </style>
</head>

<body>

  <header>
    <h1>Meu Blog Tech</h1>
    <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>

    <nav>
      <a href="#">Início</a>
      <a href="#">Posts</a>
      <a href="#">Sobre</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <main>
    <article>
      <div class="cat">🐱</div>

      <h2>Meu primeiro post</h2>
      <p class="autor">Por: Giovana Augustavicius</p>

      <p>
        Boas-vindas ao meu novo blog!Aqui vou compartilhar dicas de programação e curiosidades da área de
        tecnologia.
      </p>
    </article>
  </main>

  <footer>
    <p>&copy; 2026 Meu Blog Tech - Todos os direitos reservados</p>
  </footer>

</body>
</html>
