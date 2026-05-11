# 07 · CSS: modelo de caixa

Todo elemento HTML é uma caixa composta, de dentro para fora, por:

```
┌──────────── margin ────────────┐
│  ┌──────── border ─────────┐   │
│  │  ┌───── padding ─────┐  │   │
│  │  │     conteúdo      │  │   │
│  │  └───────────────────┘  │   │
│  └─────────────────────────┘   │
└────────────────────────────────┘
```

| Parte | Função |
|---|---|
| conteúdo | texto, imagem etc. (`width`, `height`) |
| `padding` | espaço entre conteúdo e borda |
| `border` | linha em volta |
| `margin` | espaço entre a caixa e as vizinhas |

## Atalhos
`margin: 10px 20px;` = 10px em cima/baixo, 20px nos lados.
`margin: 5px 10px 15px 20px;` = topo, direita, baixo, esquerda (sentido horário).

## Largura total
Por padrão: `width + padding + border`. Com `box-sizing: border-box;` a largura inclui padding e borda, o que facilita o cálculo de layouts.

## Dica
No navegador, F12 → aba Elements mostra o diagrama da caixa de cada elemento.
