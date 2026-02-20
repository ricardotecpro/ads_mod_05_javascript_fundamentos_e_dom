# Projeto 11 - Feed de Notícias Dinâmico 📜

**Objetivo**: Praticar a geração de conteúdo HTML a partir de um array de objetos.

## O Desafio
Você deve criar um simulador de feed de notícias.

1.  Crie um array `noticias` com pelo menos 3 objetos. Cada objeto deve ter: `titulo`, `resumo` e `autor`.
2.  Crie um container `<section id="feed"></section>` no HTML.
3.  No JavaScript, crie uma função `renderizarFeed()` que:
    - Limpe o conteúdo atual da section `#feed`.
    - Percorra o array de notícias.
    - Gere um "article" para cada notícia usando Template Strings.
    - O título deve ser um `<h3>`, o resumo um `<p>` e o autor um `<span>` em itálico.
4.  Adicione um botão "Adicionar Notícia" que, quando clicado, insira uma nova notícia fixa no array e chame a função `renderizarFeed()` novamente para atualizar a tela.

## O que entregar?
- O código HTML e JS.
- Um print da tela mostrando o feed com as notícias iniciais e após o clique no botão de adicionar.