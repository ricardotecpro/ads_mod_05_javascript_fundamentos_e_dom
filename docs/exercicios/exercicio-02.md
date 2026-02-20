# Exercícios 02 - Variáveis e Tipos 📊

## 🟢 Básicos (Fixação)

1.  **Diferenciação**: Explique por que preferimos usar `const` ao invés de `let` na maioria das vezes. Existe algum risco em usar apenas `let`?
2.  **Identificação**: Diga qual é o tipo de dado (string, number, boolean, etc.) de cada valor abaixo:
    - `"123"`
    - `123`
    - `true`
    - `undefined`

## 🟡 Intermediários (Aplicação)

3.  **Cálculo**: Crie um script que receba o preço de um produto e a porcentagem de desconto. Calcule o valor final e exiba no console. Use nomes de variáveis claros.
4.  **Tipagem Curiosa**: O que acontece se você somar um booleano com um número (ex: `true + 5`)? Realize o teste no console e tente explicar o porquê do resultado.

## 🔴 Desafio

5.  **Conversor de Unidades**:
    Crie um script que converta uma temperatura de Celsius para Fahrenheit.
    - Fórmula: `F = (C * 9/5) + 32`
    - Declare a temperatura em Celsius como uma `const`.
    - Exiba o resultado final formatado como: "A temperatura de [C]°C equivale a [F]°F".

5.  **Cenário de Falha Crítica**:
    O serviço de "Notificação" (envio de e-mail e SMS) está fora do ar.
    *   Se o seu sistema for **síncrono**, o usuário conseguirá finalizar uma compra? 
    *   Como a abordagem **assíncrona** com filas resolveria esse problema, garantindo que o e-mail seja enviado quando o serviço voltar?
    *   Cite um exemplo de serviço que **precisa** ser síncrono (não pode esperar).
