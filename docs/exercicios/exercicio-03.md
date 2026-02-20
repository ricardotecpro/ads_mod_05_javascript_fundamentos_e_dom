# Exercícios 03 - Condições 🧠

## 🟢 Básicos (Fixação)

1.  **Lógica**: Refaça o código abaixo utilizando `if` e `else` para que ele verifique se um número é positivo, negativo ou zero:
    ```javascript
    let num = 10;
    // Seu código aqui
    ```
2.  **Operadores**: O que a expressão `(10 > 5 && 3 < 2)` retorna? E a expressão `(10 > 5 || 3 < 2)`? Explique o porquê.

## 🟡 Intermediários (Aplicação)

3.  **Sistema de Notas**: Crie um script que receba a nota de um aluno (0 a 10).
    - Se a nota for maior ou igual a 7: "Aprovado"
    - Se a nota for entre 5 e 6.9: "Recuperação"
    - Se a nota for menor que 5: "Reprovado"
4.  **Par ou Ímpar**: Crie uma lógica que receba um número e exiba "O número X é par" ou "O número X é ímpar" no console. *Dica: Use o operador de resto (`%`).*

## 🔴 Desafio

5.  **Simulador de Caixa Eletrônico**:
    Crie um script que simule um saque.
    - Declare uma variável `saldo` e uma `valorSaque`.
    - Se o `valorSaque` for menor ou igual ao `saldo`, exiba "Saque realizado! Novo saldo: [valor]".
    - Se o `valorSaque` for maior que o `saldo`, exiba "Saldo insuficiente".
    - **Extra**: Adicione uma condição para não permitir valores de saque negativos.
