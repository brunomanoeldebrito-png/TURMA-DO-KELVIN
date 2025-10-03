<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Livro da Turma do Kelvin</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: #fdf6e3;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    nav {
      background: #333;
      color: white;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav button {
      background: #4CAF50;
      border: none;
      color: white;
      padding: 10px 20px;
      margin: 5px;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s;
    }
    nav button:hover {
      background: #45a049;
    }
    main {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .chapter {
      display: none;
    }
    .chapter.active {
      display: block;
    }
    footer {
      text-align: center;
      padding: 10px;
      background: #eee;
      margin-top: 20px;
      border-top: 1px solid #ccc;
    }
  </style>
</head>
<body>

<header>
  <h1>Livro da Turma do Kelvin</h1>
  <p>Uma aventura incrível no Parque do Arco-Íris!</p>
</header>

<nav>
  <button onclick="showChapter(1)">Capítulo 1</button>
  <button onclick="showChapter(2)">Capítulo 2</button>
  <button onclick="showChapter(3)">Capítulo 3</button>
  <!-- Você pode adicionar mais capítulos aqui -->
</nav>

<main>
  <div id="chapter1" class="chapter active">
    <h2>Capítulo 1: O Mapa Misterioso</h2>
    <p>Era uma manhã ensolarada, perfeita para aventuras. Kelvin acordou cedo e correu até o quintal, onde sua turma já estava reunida. Lia, Leo, Mia, Zack, Sofia e Tom esperavam ansiosos.</p>
    <p>— Bom dia, pessoal! Hoje vamos fazer algo incrível! — disse Kelvin, segurando um papel antigo e amarelado.<br>
       — O que é isso? — perguntou Mia, inclinando-se para olhar.<br>
       — É um mapa do tesouro! — respondeu Kelvin, com os olhos brilhando.</p>
    <p>Todos se animaram imediatamente. Eles já tinham explorado o Parque do Arco-Íris algumas vezes, mas nunca encontraram nada tão misterioso.</p>
    <p>— Então, para onde vamos primeiro? — perguntou Leo, saltando de um pé para o outro.<br>
       — Sigam-me! — disse Kelvin, apontando para uma trilha que parecia levar a uma clareira escondida entre as árvores.</p>
    <p>Enquanto caminhavam, Zack começou a brincar:<br>
       — Aposto que o tesouro vai estar cheio de doces!<br>
       — Ou de moedas de chocolate! — riu Mia.</p>
    <p>No meio do caminho, algo chamou atenção de Sofia.<br>
       — Olhem! — disse ela, apontando para um arbusto que se movia.<br>
       Todos pararam. Um coelho branco e fofinho apareceu, carregando uma pequena chave pendurada no pescoço.<br>
       — Parece que temos uma pista! — exclamou Tom, tentando pegar a chave.</p>
    <p>Mas o coelho era rápido. Saltou para dentro do arbusto e desapareceu.<br>
       — Não se preocupem, pessoal — disse Lia, examinando a chave cuidadosamente. — Ela deve abrir algo importante.</p>
    <p>Seguindo a trilha, eles chegaram a uma grande árvore com um tronco oco. No interior, havia uma caixa de madeira com um cadeado colorido. O cadeado tinha símbolos estranhos: círculos verdes, azuis e vermelhos.</p>
    <p>— Parece um enigma! — disse Sofia, observando atentamente.<br>
       — Eu posso tentar! — disse Lia, analisando os símbolos. — Precisamos colocar as cores na ordem certa.</p>
    <p>Depois de várias tentativas e algumas risadas, Mia finalmente acertou a combinação. A caixa se abriu com um estalo. Dentro, havia uma pista: um pergaminho com instruções para seguir até o Rio Encantado.</p>
    <p>— Uau! Isso é só o começo da aventura! — disse Kelvin, animado.<br>
       — Então vamos lá! — gritou Leo, correndo na frente.</p>
    <p>Enquanto caminhavam, cada um da turma começou a planejar:</p>
    <ul>
      <li>Kelvin: liderar o grupo e manter todos motivados.</li>
      <li>Mia: observar detalhes e anotar pistas.</li>
      <li>Leo: cuidar do grupo e tornar a aventura divertida.</li>
      <li>Lia: resolver enigmas e desafios inteligentes.</li>
      <li>Zack: animar a turma e ajudar em tarefas criativas.</li>
      <li>Sofia: pensar com calma e encontrar soluções.</li>
      <li>Tom: explorar caminhos e descobrir segredos escondidos.</li>
    </ul>
    <p>E assim, a Turma do Kelvin começou a maior aventura de suas vidas, sem imaginar que o Rio Encantado guardava desafios que testariam coragem, amizade e criatividade como nunca antes.</p>
  </div>

  <div id="chapter2" class="chapter">
    <h2>Capítulo 2:Em breve... </h2>
    <p>Em breve......</p>
  </div>

  

<footer>
  <p>© 2025 Turma do Kelvin. Todos os direitos reservados.</p>
</footer>

<h3> Autor:Bruno Manoel de brito<\h3>

  <script>
  function showChapter(num) {
    const chapters = document.querySelectorAll('.chapter');
    chapters.forEach(c => c.classList.remove('active'));
    document.getElementById('chapter' + num).classList.add('active');
  }
</script>

</body>
</html># TURMA-DO-KELVIN
