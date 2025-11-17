# Primeiro-projeto
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Perfil</title>

  <style>
    /* Seletor por tag */
    body {
      background-color: #f4f4f4;
      font-family: Arial, sans-serif;
    }

    /* Seletor por ID */
    #titulo {
      color: darkblue;
      text-align: center;
    }

    /* Seletor por classe */
    .destaque {
      color: #e67e22;
      font-weight: bold;
    }

    /* Seletor agrupado */
    h2, p {
      margin-left: 20px;
    }

    /* Seletor descendente */
    div ul li {
      color: #555;
    }
  </style>
</head>

<body>
  <h1 id="titulo">Meu Perfil</h1>

  <h2>Sobre Mim</h2>
  <p>Meu nome é <span class="destaque">Girley Elianderson</span> e gosto de tecnologia.</p>

  <h2>Meus Hobbies</h2>
  <div>
    <ul>
      <li>Praticar taekwoondo</li>
      <li>Programar</li>
      <li>Assistir animes</li>
    </ul>
  </div>
</body>
</html>
