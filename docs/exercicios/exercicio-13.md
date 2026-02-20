# Exercícios 13 - Tratamento de Erros e Async 🛡️

## 🟢 Básicos (Fixação)

1.  **Try/Catch**: Qual bloco de código é responsável por capturar o erro? O que acontece com o programa se o erro for capturado?
2.  **Finally**: Em que situações o bloco `finally` é executado?

## 🟡 Intermediários (Aplicação)

3.  **Checagem Manual**: O `fetch` caiu em um erro 404 (Não encontrado). Como você checa isso no código para lançar um erro manual?
4.  **UX**: Por que não é recomendado mostrar o erro técnico (ex: "Stack Trace") direto para o usuário final? O que devemos mostrar em vez disso?

## 🔴 Desafio

5.  **Buscador Resiliente**:
    - Escreva um código que tenta buscar dados de um usuário no GitHub.
    - Antes de começar o fetch, mude o texto de uma `div` de status para "Carregando...".
    - Se o fetch falhar, mude o status para a cor vermelha e escreva: "Erro: Verifique sua conexão".
    - No final de tudo (sucesso ou erro), exiba no console: "Tentativa de busca encerrada".
    - **Dica**: Use o bloco `finally` para o log final.