<!DOCTYPE html>
<html>
<head>
  <title>Página de Captura</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 20px;
    }

    h1 {
      color: #333;
      text-align: center;
    }

    form {
      max-width: 400px;
      margin: 0 auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    input[type="text"],
    input[type="email"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 4px;
      font-size: 14px;
    }

    button[type="submit"],
    button#desbloquearBonus {
      width: 100%;
      padding: 10px;
      background-color: #0078D7;
      color: #fff;
      border: none;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
    }

    button[type="submit"]:hover,
    button#desbloquearBonus:hover {
      background-color: #005A9E;
    }

    #bonus {
      max-width: 400px;
      margin: 20px auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    #bonus h2 {
      color: #333;
      text-align: center;
    }

    #bonus p {
      color: #777;
      font-size: 14px;
    }

    #bonus input[type="text"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 4px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <h1>Cadastre-se no nosso curso!</h1>
  <form id="cadastroForm">
    <input type="text" id="nome" placeholder="Nome" required><br>
    <input type="email" id="email" placeholder="Email" required><br>
    <button type="submit">Cadastrar</button>
  </form>

  <div id="bonus" style="display: none;">
    <h2>Bônus desbloqueado!</h2>
    <p>Envie o link de indicação para 5 amigos para receber o bônus incrível.</p>
    <input type="text" id="indicacao" placeholder="Digite o link de indicação" required><br>
    <button id="desbloquearBonus">Desbloquear Bônus</button>
  </div>

  <script>
    // O JavaScript permanece o mesmo
  </script>
</body>
</html>

