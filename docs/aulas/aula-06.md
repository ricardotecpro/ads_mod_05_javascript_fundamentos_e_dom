# Aula 06 - Objetos e Arrays 📦

!!! tip "Objetivo"
    **Objetivo**: Aprender a estruturar dados complexos utilizando objetos (pares chave-valor) e armazenar coleções de informações de forma organizada em arrays (listas).

---

## 1. O que são Objetos? 🧩

Um **Objeto** é um conjunto de propriedades que descreve um item da vida real. Imagine um carro: ele tem cor, modelo, ano e marca. No JavaScript, representamos isso usando chaves `{}`.

```javascript
const usuario = {
  nome: "Ricardo",
  idade: 30,
  estaAtivo: true,
  interesses: ["JS", "Web", "DOM"]
};

// Acessando propriedades
console.log(usuario.nome); // "Ricardo"
```

---

## 2. O que são Arrays (Listas)? 📚

Um **Array** é uma lista ordenada de valores. Eles são delimitados por colchetes `[]` e cada item possui um índice (posição) começando do **zero**.

```javascript
const frutas = ["Maçã", "Banana", "Uva"];

console.log(frutas[0]); // "Maçã"
console.log(frutas.length); // 3 (quantidade de itens)
```

### Métodos Comuns de Arrays:
- **`push()`**: Adiciona um item ao final da lista.
- **`pop()`**: Remove o último item da lista.
- **`forEach()`**: Percorre cada item da lista (iteração).

---

## 3. Manipulação de Coleções 📊

Veja como os dados são organizados e acessados:

```mermaid
graph TD
    A[Array de Objetos] --> B[Objeto 0: {id: 1, nome: 'A'}]
    A --> C[Objeto 1: {id: 2, nome: 'B'}]
    A --> D[Objeto 2: {id: 3, nome: 'C'}]
    B --> B1[Acessar: array[0].nome]
    B1 --> B2[Resultado: 'A']
```

---

## 4. Prática no Terminal 💻

```termynal
$ // Criando e modificando um array
$ let cores = ["Vermelho", "Verde"];
$ cores.push("Azul");
$ console.log(cores);
> ["Vermelho", "Verde", "Azul"]
$ // Trabalhando com objetos
$ const prod = { preco: 50 };
$ prod.nome = "Camiseta";
$ console.log(prod);
> { preco: 50, nome: "Camiseta" }
```

> [!NOTE]
> Arrays e Objetos são a base da troca de dados na web. Quase todo dado que vem de uma API chega no formato de um array de objetos.

---

## 5. Mini Projeto: Catálogo de Produtos 🏆

Crie um pequeno sistema de estoque.
- Crie um array chamado `estoque` que contenha 3 objetos (cada um com `nome` e `quantidade`).
- Adicione um novo produto ao array usando `.push()`.
- Use um laço `for` ou `.forEach()` para exibir o nome de todos os produtos do estoque no console.

---

## 6. Exercícios de Fixação 📝

### Básicos
1. Como você acessaria o valor "Banana" do array `const lista = ["Maçã", "Banana", "Uva"]`?
2. Crie um objeto chamado `livro` com as propriedades `titulo`, `autor` e `paginas`.

### Intermediários
3. Crie um array de números e use um laço para exibir apenas os números que são maiores que 10.
4. Explique, com um exemplo, para que serve o método `.push()` em um array.

### Desafio
5. **Busca em Lista**:
   Crie um array de objetos chamado `usuarios`, onde cada objeto tem `nome` e `email`.
   Escreva uma função que receba um nome e procure se esse usuário existe no array. Se existir, exiba o e-mail dele. Se não, exiba "Usuário não encontrado".

---

**Próxima Aula**: Vamos aprender a organizar arquivos com [Módulos JS](./aula-07.md)! 🧩
