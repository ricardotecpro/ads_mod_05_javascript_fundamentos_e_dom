# Aula 10 - Estilos e Classes no DOM 🎨

!!! tip "Objetivo"
    **Objetivo**: Aprender a manipular o visual dos elementos da página em tempo real, utilizando a propriedade `style` para alterações diretas e o objeto `classList` para gerenciar classes CSS dinamicamente.

---

## 1. Alterando Estilos Diretamente (`.style`) 🖌️

O JavaScript permite alterar qualquer propriedade CSS de um elemento através da propriedade `.style`. 

> [!IMPORTANT]
> No JavaScript, propriedades CSS com hífen (como `background-color`) tornam-se **camelCase** (`backgroundColor`).

```javascript
const box = document.querySelector('.caixa');

box.style.backgroundColor = "gold";
box.style.width = "200px";
box.style.border = "2px solid black";
```

---

## 2. Manipulando Classes (`classList`) 🏷️

Embora o `.style` seja útil, a melhor prática é definir os estilos no CSS e usar o JavaScript apenas para **adicionar** ou **remover** classes. O objeto `classList` facilita muito esse processo.

### Métodos Principais:
- **`add('classe')`**: Adiciona uma classe ao elemento.
- **`remove('classe')`**: Remove uma classe do elemento.
- **`toggle('classe')`**: Alterna a classe (se existir, remove; se não, adiciona).
- **`contains('classe')`**: Verifica se o elemento possui a classe.

```javascript
const cartao = document.querySelector('#meu-cartao');

// Alterna entre modo claro e escuro
cartao.classList.toggle('dark-mode');
```

---

## 3. Fluxo de Mudança Visual 📊

```mermaid
graph TD
    A[Ação do Usuário] --> B{Decisão Lógica}
    B -- Opção A --> C[classList.add('sucesso')]
    B -- Opção B --> D[classList.add('erro')]
    C --> E[CSS aplica cor Verde]
    D --> F[CSS aplica cor Vermelha]
    E --> G[Visual alterado no Navegador]
    F --> G
```

---

## 4. Prática no Terminal (Simulação) 💻

```termynal
$ // Verificando as classes de um botão
$ const btn = document.querySelector('button');
$ btn.classList.add('ativo');
$ console.log(btn.className);
> "btn-primario ativo"
$ // Mudando estilo inline
$ btn.style.display = "none";
> "O botão sumiu!"
```

> [!TIP]
> Prefira sempre o uso de `classList.toggle()` para elementos interativos como menus laterais, modais e botões de "curtir".

---

## 5. Mini Projeto: Modo Noturno (Dark Mode) 🏆

Crie um botão que altera o visual de toda a página.
1.  No CSS, crie uma classe `.dark-mode` que mude a cor do `body` para preto e o texto para branco.
2.  No JavaScript, selecione o `body` e o botão.
3.  Adicione um evento de clique ao botão que executa `document.body.classList.toggle('dark-mode')`.

---

## 6. Exercícios de Fixação 📝

### Básicos
1. Como se escreve a propriedade CSS `font-size` no JavaScript?
2. Qual a principal vantagem de usar `classList` em vez de alterar o `.style` diretamente?

### Intermediários
3. Como você removeria a classe `invisivel` de um elemento quando ele fosse clicado?
4. Escreva o código para verificar se um elemento possui a classe `selecionado`.

### Desafio
5. **Destaque Dinâmico**:
   - Imagine uma lista de itens.
   - Crie um código que, ao clicar em qualquer item da lista, adicione a classe `.destaque` a ele.
   - **Extra**: Garanta que apenas UM item da lista tenha a classe destaque por vez (remova dos outros antes de adicionar ao novo).

---

**Próxima Aula**: Vamos aprender a trabalhar com grandes volumes de dados com [Templates e Listas Dinâmicas](./aula-11.md)! 📜
