# Exercícios 11 - Templates e Listas Dinâmicas 📜

## 🟢 Básicos (Fixação)

1.  **Sintaxe**: Como você injetaria a variável `usuario = "Ana"` dentro da frase "Bem-vinda, Ana!" usando Template Strings?
2.  **Criação**: Qual o comando para criar um novo elemento `<div>` na memória?

## 🟡 Intermediários (Aplicação)

3.  **Loop**: Dado o array `cores = ["azul", "verde", "amarelo"]`, use um `forEach` para exibir cada cor no console dentro de uma frase: "A cor atual é ...".
4.  **Inserção**: Como você adicionaria um parágrafo que você acabou de criar dentro de um `div` que possui o ID `container`?

## 🔴 Desafio

5.  **Lista de Compras Dinâmica**:
    - Crie um array de objetos `itens = [{nome: "Leite", preco: 5.50}, {nome: "Pão", preco: 2.10}]`.
    - Escreva o código que percorra este array e crie, para cada item, uma linha formatada assim: `<li>Leite - R$ 5.50</li>`.
    - Adicione todas essas linhas a uma `<ul>` no seu HTML.
    - **Dica**: Use o método `.toFixed(2)` para formatar os preços com duas casas decimais.