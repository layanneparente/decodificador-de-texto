<div align='center' id='top'>
<img src='./.github/projeto_decoder.gif' alt='app_name' />

&#xa0;

</div>

<h1 align='center'>Decoder</h1>

<p align='center'>

<img alt='Principal linguagem do projeto' src='https://img.shields.io/github/languages/top/fransilva0/decodificador-de-texto?color=56BEB8'>

<img alt='Quantidade de linguagens utilizadas' src='https://img.shields.io/github/languages/count/fransilva0/decodificador-de-texto?color=56BEB8'>

<img alt='Tamanho do repositório' src='https://img.shields.io/github/repo-size/fransilva0/decodificador-de-texto?color=56BEB8'>

<!-- <img alt='Github issues' src='https://img.shields.io/github/issues/{{github}}/{{repository}}?color=56BEB8' /> -->

<!-- <img alt='Github forks' src='https://img.shields.io/github/forks/{{github}}/{{repository}}?color=56BEB8' /> -->

<!-- <img alt='Github stars' src='https://img.shields.io/github/stars/{{github}}/{{repository}}?color=56BEB8' /> -->
</p>

<p align='center'>
<a href='#dart-sobre'>Sobre</a> &#xa0; | &#xa0;
<a href='#sparkles-funcionalidades'>Funcionalidades</a> &#xa0; | &#xa0;
<a href='https://github.com/layanneparente' target='_blank'>Autor</a>
</p>

<br>

## :dart: Sobre ##

<p>
  O projeto é um desafio do Programa ONE, Turma 7, da Oracle + Alura, onde a missão seria construir uma aplicação que codifica-se e decodifica-se um texto.
  Inicialmente foram construídos os elementos do HTMl estabilizados no CSS de forma a ficarem responsivos no mobile, obtendo um front-end para a tela móvel. Após isso, utilizando o media query, foi transfornado a tela responsiva para as demais resolusões. Além disso, para telas grandes existe um ícone em SVG na área de output que só pode ser visto nessa tela, algo apresentado no figma do desafio.
</p>
<p>
  Funcionalidades do projeto: a primeira, por meio de uma função, captura o texto do input, cria um ArrayList com cada caractere numa posição. Depois disso, é substituido as letras da mensagem por outras de acordo com a
  criptografia de desafio e envia o novo texto para o local de output.
</p>
<p>
  A próxima funcionalidade é a função de desencriptar o texto do usuário. Nesse ponto optou-se por pegar o texto do input e utilizar o replace() para percorer a string e modificar o texto passando o resultado para o output. Além disso, as cores dos elementos da tela foram modificadas e adicionadas animações simples em CSS, que não foram planejadas no desafio.
</p>
<p>
  Em relação as animações, adicionei uma animação onde o ícone e o título do Header percorre uma linha da ponta direita para a esquerda ao iniciar a página. Já nos botões de Encriptar e Desencriptar adicionei uma animação que ao colocar o mouse por cima do mesmo, uma faixa de cor mais escura percorre o botão da esquerda para a direita preenchendo o mesmo com a nova cor. Ambas as animações foram realizadas apenas para treinamento inicial desse conteúdo.
</p>
<p>
  Além do desafio principal, ocorreu a sugestão de uma implementação extra no projeto, o botão de copiar o resultado para a área de transeferência, porém não consegui resolve-lo usando o que foi proposto, decidindo, no momento, entregar o desafio apenas com as implementações obrigatórias deixando novas implementações e funcionalidades para algum momento futuro, após a conclusão do programa ONE.
</p>

## :sparkles: Funcionalidades ##

:heavy_check_mark: Criptografar texto;<br />
:heavy_check_mark: Desciptografar texto;<br />

<a href='#top'>Voltar para o topo</a>
