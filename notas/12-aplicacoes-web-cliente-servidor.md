# 12 · Como uma página web funciona

Resumo que junta HTML, CSS e JavaScript.

## Os três papéis
| Tecnologia | Papel | Analogia |
|---|---|---|
| HTML | estrutura e conteúdo | esqueleto |
| CSS | aparência | roupa |
| JavaScript | comportamento | músculos |

## Fluxo
1. O usuário digita um endereço ou clica num link.
2. O navegador (**cliente**) faz uma requisição ao **servidor**.
3. O servidor devolve HTML (e links para CSS, JS e imagens).
4. O navegador monta a página e executa o JavaScript.
5. Ações do usuário disparam JS, que altera a página ou pede mais dados (Ajax).

## Organização de um projeto simples
```
projeto/
├── index.html
├── estilo.css
└── funcoes.js
```

## Boas práticas
- Não misturar conteúdo, estilo e script no mesmo arquivo.
- Dar `id` ou `class` significativos aos elementos.
- Testar no console do navegador (F12).
- Comentar o código e manter nomes claros (indicador ID2.2 do plano).
