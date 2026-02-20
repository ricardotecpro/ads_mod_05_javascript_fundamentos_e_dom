# Exercícios 12 - Requisições e APIs 🌐

## 🟢 Básicos (Fixação)

1.  **JSON**: O que significa JSON e por que ele é o formato favorito para APIs?
2.  **Async**: Para que serve a palavra-chave `await` dentro de uma função?

## 🟡 Intermediários (Aplicação)

3.  **Fetch**: Escreva o código básico de um `fetch` para a URL `https://api.github.com` e exiba o resultado no console.
4.  **Erros**: Por que é vital envolver um `fetch` dentro de um bloco `try/catch`?

## 🔴 Desafio

5.  **Buscador de Pokémons**:
    - Imagine que você quer buscar dados de um Pokémon na PokeAPI.
    - O endpoint é: `https://pokeapi.co/api/v2/pokemon/IDENTIFICADOR`.
    - Escreva uma função assíncrona que receba o nome de um Pokémon (ex: "pikachu").
    - Faça o fetch e exiba no console a altura (`height`) e o peso (`weight`) desse Pokémon.
    - **Dica**: Use Template Strings para montar a URL dinamicamente.