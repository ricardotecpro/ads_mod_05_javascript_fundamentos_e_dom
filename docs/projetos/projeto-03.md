# Projeto 03 - Verificador de Elegibilidade ⚡

**Objetivo**: Criar um sistema lógico que valida se uma pessoa pode votar e se o voto é obrigatório ou facultativo.

## O Desafio
Com base na idade de uma pessoa, seu script deve exibir uma das quatro mensagens:
1.  "Não pode votar" (Idade < 16)
2.  "Voto Facultativo" (Idade entre 16 e 17 OU acima de 70)
3.  "Voto Obrigatório" (Idade entre 18 e 70)
4.  "Idade Inválida" (Valores negativos ou não numéricos)

**Instruções:**
- Use `const idade = 25;` (ou qualquer valor para testar).
- Utilize operadores lógicos como `&&` e `||`.
- Formate a saída de forma amigável no console.

## O que entregar?
- O arquivo `.js` com a lógica completa.
- Um pequeno relatório (ou comentário no código) explicando qual operador lógico você usou para a condição de "Voto Facultativo" e por quê.