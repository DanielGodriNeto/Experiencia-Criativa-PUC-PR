# 08 · JavaScript: introdução

**JavaScript** é uma linguagem interpretada criada para rodar no navegador (lado do **cliente**): interage com o usuário e altera a página sem precisar ir ao servidor a cada ação.

## Cliente × servidor
- **Cliente**: navegador do usuário (HTML, CSS, JS).
- **Servidor**: onde ficam arquivos e dados; responde às requisições.

## Como ligar JS a uma página
```html
<head>
  <script src="funcoes.js"></script>
</head>
```
O código fica em um arquivo `.js`.

## Exemplo
`index.html`
```html
<input type="text" id="valor" value="10">
```
`funcoes.js`
```js
const campo = document.getElementById("valor");
console.log(campo.value);
```
Os elementos que o JS manipula devem ter **`id`**.

## Exercício feito
Criar um HTML com `input text` (usando `value`), ligar um arquivo JS e mostrar o valor do campo.
