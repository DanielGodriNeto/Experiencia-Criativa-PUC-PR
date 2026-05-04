# 06 · CSS: cores, fundo, fontes e texto

## Cores e fundo
| Propriedade | Função |
|---|---|
| `color` | cor do texto (`red`, `#ff0000`, `rgb(255,0,0)`) |
| `background-color` | cor de fundo (ou `transparent`) |
| `background-image` | `url(...)` ou `none` |
| `background-repeat` | `repeat`, `repeat-x`, `repeat-y`, `no-repeat` |

## Fontes
| Propriedade | Valores |
|---|---|
| `font-family` | nomes de fonte + família genérica (`serif`, `sans-serif`, `monospace`) |
| `font-style` | `normal`, `italic`, `oblique` |
| `font-weight` | `normal`, `bold`, 100–900 |
| `font-size` | `small`…`large`, `px`, `%`, `em` |

Sempre termine `font-family` com uma família genérica de reserva.

## Texto
| Propriedade | Função |
|---|---|
| `text-align` | `left`, `right`, `center`, `justify` |
| `text-indent` | recuo da primeira linha |
| `letter-spacing` / `word-spacing` | espaço entre letras/palavras |
| `text-transform` | `capitalize`, `uppercase`, `lowercase` |
| `white-space` | tratamento dos espaços em branco |

## Exemplo
```css
h1 { font-family: Georgia, serif; text-align: center; text-transform: uppercase; }
```
