# 10 · jQuery

Biblioteca de funções JavaScript que interage com o HTML. Lema: **"escrever menos, fazer mais"**.

## Recursos
- Seleção e manipulação de elementos HTML.
- Manipulação de CSS.
- Eventos HTML.
- Efeitos e animações.
- HTML DOM.
- Ajax.

## Como adicionar
A biblioteca é um arquivo `.js`; inclua-o antes do seu script:
```html
<script src="jquery.min.js"></script>
<script src="funcoes.js"></script>
```

## Comparação
JavaScript puro:
```js
document.getElementById("valor").value;
```
jQuery:
```js
$("#valor").val();
```

## Evento
```js
$("#botao").click(function () {
  alert($("#valor").val());
});
```

## Observação
Hoje o JavaScript moderno cobre grande parte do que o jQuery oferecia; ele ainda aparece muito em projetos existentes.
