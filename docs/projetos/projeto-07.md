# Projeto 07 - Biblioteca Modular de Mensagens 🧩

**Objetivo**: Praticar a criação e o consumo de módulos ES6 em um pequeno projeto organizado.

## O Desafio
Você deve criar um mini sistema de logs (mensagens) dividido em módulos.

1.  **Arquivo `logger.js`**:
    - Deve exportar uma variável `prefixo = "[LOG]"`.
    - Deve exportar uma função `logInfo(msg)` que exiba no console: `prefixo + " INFO: " + msg`.
    - Deve exportar default uma função `logErro(msg)` que exiba no console: `prefixo + " ERRO: " + msg`.

2.  **Arquivo `app.js`**:
    - Importe as funções do módulo `logger.js`.
    - Chame a função de informação passando "Sistema iniciado...".
    - Chame a função de erro passando "Falha na conexão!".

## O que entregar?
- Os arquivos `logger.js` e `app.js`.
- Um print do terminal mostrando as mensagens formatadas saindo no console após a execução.