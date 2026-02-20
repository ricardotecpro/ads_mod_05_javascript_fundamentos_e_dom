# Projeto 12 - App de Previsão do Tempo 🌤️

**Objetivo**: Consumir uma API real e exibir os dados dinamicamente no DOM.

## O Desafio
Você deve criar um mini app que busca o clima de uma cidade.

1.  Crie um input de texto para o nome da cidade e um botão de busca.
2.  No JavaScript, ao clicar no botão, utilize a **Fetch API** para buscar dados de clima (você pode usar a API gratuita `OpenWeatherMap` ou o serviço `HG Brasil Weather`).
3.  **Requisitos**:
    - Enquanto a requisição acontece, mostre o texto "Buscando..." na tela.
    - Quando os dados chegarem, exiba: Temperatura Atual, Descrição (ex: Ensolarado) e a Humidade.
    - Se a cidade não existir, exiba um alerta: "Cidade não encontrada!".

## O que entregar?
- O arquivo `.js` com a lógica do `fetch`.
- O arquivo `.html` com a estrutura e estilos básicos.
- Um print da tela mostrando o resultado da busca para uma cidade real (ex: "São Paulo").