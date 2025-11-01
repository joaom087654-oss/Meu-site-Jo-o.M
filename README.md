<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cartão de Perfil</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      width: 300px;
      text-align: center;
      padding: 20px;
    }

    .card img {
      width: 100px;
      border-radius: 50%;
      margin-bottom: 15px;
    }

    .card h2 {
      margin: 10px 0;
      font-size: 22px;
    }

    .card p {
      color: #555;
      font-size: 14px;
    }

    .card button {
      margin-top: 15px;
      background: #007bff;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 20px;
      cursor: pointer;
    }

    .card button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://i.pravatar.cc/100" alt="Foto de Perfil" />
    <h2>João Silva</h2>
    <p>Desenvolvedor Front-End</p>
    <button>Seguir</button>
  </div>
</body>
</html>
