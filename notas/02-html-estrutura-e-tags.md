# 02 · HTML: estrutura e tags

**HTML** (*HyperText Markup Language*) é a linguagem de marcação em que as páginas web são escritas e que o navegador interpreta. É de **marcação**, não de programação: descreve a estrutura do conteúdo.

## Tag
Estrutura com marca de início e de fim que diz ao navegador como mostrar o conteúdo:

```html
<p>Texto do parágrafo</p>   <!-- abre e fecha -->
<br>                         <!-- sem conteúdo -->
```

## Estrutura mínima
Salve como `.html` e abra no navegador:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Minha página</title>
  </head>
  <body>
    <h1>Olá, mundo</h1>
  </body>
</html>
```

- `<html>`: início e fim do documento.
- `<head>`: cabeçalho (título, metadados, links para CSS/JS).
- `<body>`: corpo, o que aparece na tela.

## Headings
`<h1>` a `<h6>`: títulos e subtítulos, do mais importante ao menos.

## Dica
Indente as tags aninhadas e feche sempre o que abriu; a maioria dos erros iniciais é tag aberta.
