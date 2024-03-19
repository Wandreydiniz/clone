<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Redirecionamento de Página</title>
</head>
<body>
 
<button id="redirecionar">Ir para outra página</button>

<script>
// Seleciona o botão
var botao = document.getElementById('redirecionar');

// Adiciona um evento de clique ao botão
botao.addEventListener('click', function() {
    // Redireciona para a página desejada
    window.location.href = 'index.html';
});
</script>

</body>
</html>
