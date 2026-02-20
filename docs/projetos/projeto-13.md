# Projeto 13 - Validador de CEP com Tratamento de Erro 🛡️

**Objetivo**: Implementar uma busca assíncrona com estados de carregamento e captura de falhas.

## O Desafio
Crie um buscador de endereços via CEP utilizando a API do ViaCEP (`https://viacep.com.br/ws/CEP_AQUI/json/`).

1.  **Interface**: Um input para o CEP e um botão "Cofirmar".
2.  **Lógica**:
    - Ao clicar, exiba "Buscando..." na tela.
    - Se o CEP não for encontrado ou estiver no formato errado, mostre uma mensagem de erro clara em vermelho (ex: "CEP inválido ou não encontrado").
    - Se o CEP for encontrado, mostre a Rua, Bairro e Cidade.
3.  **Segurança**: Use `try/catch` para capturar erros de rede e a propriedade `.ok` para validar a resposta.

## O que avaliar?
- Exibição correta da mensagem de "Carregando".
- Tratamento de erro para CEPs inexistentes.
- Código limpo usando `async/await`.