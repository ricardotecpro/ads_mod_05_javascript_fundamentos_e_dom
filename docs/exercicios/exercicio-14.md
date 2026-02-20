# Exercícios 14 - Promessas e Event Loop 🕒

## 🟢 Básicos (Fixação)

1.  **Estados**: Cite os 3 estados de uma Promise e descreva o que cada um significa.
2.  **Sintaxe**: Como você capturaria um erro de uma Promise usando a sintaxe de `.then()` e `.catch()`?

## 🟡 Intermediários (Aplicação)

3.  **Event Loop**: Explique por que, se rodarmos um `setTimeout` com tempo 0, ele ainda assim executa DEPOIS do código síncrono.
4.  **Promise.all**: Para que serve o método `Promise.all`? Dê um exemplo de uso real em um site.

## 🔴 Desafio

5.  **Simulador de Login Assíncrono**:
    - Crie uma função `autenticar(user, pass)` que retorne uma Promise.
    - Simule um atraso de 2 segundos usando `setTimeout`.
    - Se `user === "admin"` e `pass === "123"`, a Promise deve ser **resolvida** com "Acesso Permitido".
    - Caso contrário, deve ser **rejeitada** com "Dados Inválidos".
    - Consuma essa função usando `async/await` e exiba o resultado no console (sucesso ou erro).