# 05 · CSS: introdução

**CSS** (*Cascading Style Sheets*) separa a **apresentação** (cores, fontes, espaçamento) do **conteúdo** (HTML). Menus em cascata, cabeçalhos e rodapés de sites são feitos com CSS.

## Versões
CSS1 (1996), CSS2 (1998), CSS2.1, CSS3 (cantos arredondados, sombras, mais opções de fundo).

## Sintaxe
```css
seletor {
  propriedade: valor;
}
```

## Como incluir
1. **Inline**: `<p style="color:red">`
2. **Interno**: `<style>` dentro do `<head>`
3. **Externo** (preferível): `<link rel="stylesheet" href="estilo.css">`

## Seletores básicos
| Seletor | Escolhe |
|---|---|
| `p` | todas as tags `<p>` |
| `.classe` | elementos com `class="classe"` |
| `#id` | o elemento com aquele `id` |

## Comentários
`/* assim */`

## Exemplo: botão
```css
button {
  background-color: #1a5fb4;
  color: white;
  border-radius: 6px;
  padding: 8px 16px;
}
```
