# crm-clientflow-v2
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CRM Clientflow</title>
  <link rel="stylesheet" href="style.css"> <!-- Referência ao arquivo de estilo -->
</head>
<body>
  <header>
    <h1>Bem-vindo ao CRM Clientflow</h1>
  </header>

  <main>
    <section>
      <h2>Serviços</h2>
      <p>Oferecemos soluções de CRM para o seu negócio.</p>
      <button onclick="mostrarMensagem()">Clique para saber mais</button>
      <p id="mensagem"></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 CRM Clientflow</p>
  </footer>

  <!-- Código JavaScript -->
  <script>
    function mostrarMensagem() {
      document.getElementById("mensagem").innerHTML = "Transforme seu atendimento com o CRM Clientflow!";
    }
  </script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4; /* Cor de fundo */
  margin: 0;
  padding: 0;
}

header {
  background-color: #0057b7;
  color: white;
  text-align: center;
  padding: 20px;
}

footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 10px;
}

button {
  background-color: #ffcc00;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  border: none;
}

button:hover {
  background-color: #ff9900;
}
