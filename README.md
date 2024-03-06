### Olá, Sou José Muller =)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Typing Effect</title>
<style>
  /* Estilo para o texto */
  .green-text {
    color: green; /* Cor do texto verde */
    overflow: hidden; /* Esconder o overflow do texto */
    border-right: .15em solid green; /* Adiciona um cursor piscante */
    white-space: nowrap; /* Impede quebras de linha */
    margin: 0 auto; /* Centraliza o texto */
    letter-spacing: .15em; /* Espaçamento entre letras */
    animation: typing 3s steps(30, end), blink-caret .75s step-end infinite;
  }

  /* Animação de digitação */
  @keyframes typing {
    from {
      width: 0
    }
    to {
      width: 100%
    }
  }

  /* Animação do cursor piscante */
  @keyframes blink-caret {
    from, to {
      border-color: transparent
    }
    50% {
      border-color: green;
    }
  }
</style>
</head>
<body>
  <!-- Elemento com classe "green-text" para aplicar o efeito de digitação -->
  <p class="green-text">Sou cientista de dados</p>
</body>
</html>



