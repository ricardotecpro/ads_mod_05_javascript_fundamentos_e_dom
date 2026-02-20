# Exercícios 07 - Módulos JS 🧩

## 🟢 Básicos (Fixação)

1.  **Exportação**: Como você exportaria uma constante chamada `PI = 3.14` de um arquivo para ser usada em outro?
2.  **Importação**: Escreva a linha de código necessária para importar uma função `somar` do arquivo `calculadora.js` localizado na mesma pasta.

## 🟡 Intermediários (Aplicação)

3.  **Namespace**: Por que é melhor importar apenas o que você precisa `import { somar } ...` em vez de carregar um arquivo gigante inteiro?
4.  **Default vs Named**: Explique a diferença entre `export default` e `export const`. Quantos `export default` podemos ter em um único arquivo?

## 🔴 Desafio

5.  **Refatoração Modular**:
    - Imagine que você tem um arquivo `utils.js` com funções de formatação de data e de moeda.
    - Export those functions.
    - Crie um arquivo `index.js` que importe essas duas funções e as utilize para exibir no console uma data e um preço (ex: "Data: 20/05/2024 - Preço: R$ 50,00").
    - **Dica**: Use o tipo `module` para testar (mesmo que seja apenas lógica).