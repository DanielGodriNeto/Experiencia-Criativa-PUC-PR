# 09 · JavaScript: depuração no console

## Como ver erros
1. Abra o `index.html` no Chrome.
2. Botão direito → **Inspecionar** (ou F12).
3. Aba **Console**.
4. Recarregue (F5) e leia a mensagem de erro.
5. Corrija e repita.

## Erro típico: script antes do elemento
```
Uncaught TypeError: Cannot read properties of null
```
O `funcoes.js` estava no `<head>` e rodou **antes** de o `<input id="valor">` existir, então `getElementById` devolveu `null`.

## Como consertar
- Colocar o `<script>` no **final do `<body>`**; ou
- Usar `defer`: `<script src="funcoes.js" defer></script>`; ou
- Executar o código dentro de um evento de carga (`DOMContentLoaded`).

## Ferramentas úteis
- `console.log(x)` para inspecionar valores.
- A aba Sources para pausar a execução (breakpoints).
- Ler a **linha** indicada no erro: costuma apontar direto para o problema.
