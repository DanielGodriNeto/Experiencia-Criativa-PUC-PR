# 04 · HTML: tabelas

## Tags
| Tag | Significado |
|---|---|
| `<table>` | a tabela |
| `<tr>` | *table row*, uma linha |
| `<td>` | *table data*, uma célula |
| `<th>` | célula de cabeçalho |

Uma célula pode conter texto, imagem, lista, formulário e até outra tabela.

## Exemplo 3×3
```html
<table border="1">
  <tr><td>A</td><td>B</td><td>C</td></tr>
  <tr><td>D</td><td>E</td><td>F</td></tr>
  <tr><td>G</td><td>H</td><td>I</td></tr>
</table>
```

## Mesclar células
- `colspan="2"`: a célula ocupa 2 colunas.
- `rowspan="2"`: ocupa 2 linhas.

## Cuidado
Use tabela para **dados tabulares**. Para posicionar elementos na página, use CSS.
