# Projeto 14 - Simulador de Carregamento de Dados ⏳

**Objetivo**: Dominar o encadeamento de promessas e o uso de timers para simular processos reais.

## O Desafio
Você deve criar um sistema que simula o carregamento de um perfil de usuário e suas fotos.

1.  **Função `getPerfil()`**: Retorna uma Promise que resolve em 1.5s com o objeto `{ id: 1, nome: "Ana" }`.
2.  **Função `getFotos(id)`**: Recebe o ID e retorna uma Promise que resolve em 2s com um array de 3 URLs de fotos.
3.  **A Lógica**:
    - No JavaScript, chame `getPerfil()`.
    - Quando o perfil chegar, use o ID dele para chamar `getFotos(id)`.
    - Exiba no console (ou no DOM) o nome da usuária e a quantidade de fotos encontradas.
    - **Dica**: Tente fazer isso usando primeiro `.then()` encadeado e depois refatore para `async/await`.

## O que entregar?
- O arquivo `.js` com as funções e o fluxo de execução.
- Um print do terminal (ou console do navegador) mostrando os logs aparecendo nos tempos corretos.