# BOLAO-DA-COPA
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Bolão da Copa 2026</title>
  <style>
    body {
      font-family: Arial;
      background: #0b3d2e;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .card {
      background: #145c43;
      padding: 20px;
      margin: 20px auto;
      max-width: 500px;
      border-radius: 12px;
    }
    input, button {
      padding: 10px;
      margin: 5px;
      width: 90%;
      border-radius: 8px;
      border: none;
    }
    button {
      background: gold;
      font-weight: bold;
      cursor: pointer;
    }
  </style>
</head>

<body>

<h1>⚽ Bolão da Copa 2026</h1>
<p>Palpite: R$ 2,00 por aposta</p>

<div class="card">
  <h3>Faça seu palpite</h3>
  <input type="text" id="nome" placeholder="Seu nome">
  <input type="text" id="jogo" placeholder="Ex: Brasil 2x1 Argentina">
  <button onclick="enviar()">Enviar Palpite</button>
</div>

<div class="card">
  <h3>PIX para pagamento</h3>
  <p><b>Chave PIX:</b> f2439c12-9dc6-43e9-950c-5c34ca93793d</p>
  <p>Valor: R$ 2,00</p>
</div>

<script>
function enviar() {
  const nome = document.getElementById("nome").value;
  const jogo = document.getElementById("jogo").value;

  if(!nome || !jogo){
    alert("Preencha tudo!");
    return;
  }

  alert("Palpite enviado! Boa sorte, " + nome);
}
</script>

</body>
</html>
