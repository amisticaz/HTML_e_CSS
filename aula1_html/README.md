# Estrutura Básica de um Documento HTML

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

O que cada parte faz:

<!DOCTYPE html> → Declara que este documento é um documento HTML5.

<html> → Elemento raiz de uma página HTML.

<head> → Contém meta informações sobre a página HTML.

<title> → Especifica um título para a página (aparece na aba ou barra do navegador).

<body> → Define o corpo do documento. É o contêiner para todo o conteúdo visível: títulos, parágrafos, imagens, links, tabelas, listas, etc.

<h1>, <h2> → Tags de cabeçalho. <h1> é o título mais importante, <h2> é um subtítulo.

<p> → Define um parágrafo de texto.

<meta charset="UTF-8"> → Define a codificação de caracteres UTF-8 (garante acentuação e caracteres especiais).

<img> → Insere uma imagem. Usa o atributo src para o caminho e alt para um texto alternativo (acessibilidade).

<ul> → Cria uma lista não ordenada (com marcadores).

<ol> → Cria uma lista ordenada (com números).

<li> → Define um item dentro de uma lista (<ul> ou <ol>). 

Diferença entre <ul>, <ol> e <li>

<ul> (unordered list): Cria uma lista não ordenada. A ordem dos itens não importa, geralmente aparecem com marcadores (● ■ etc).

<ol> (ordered list): Cria uma lista ordenada. A ordem importa, e os itens aparecem numerados ou com letras.

<li> (list item): Define um item dentro de uma lista (ordenada ou não).

Resumo:
<ul> e <ol> definem o tipo da lista, enquanto <li> define cada item dentro dela.

O que é um elemento HTML?

Um elemento HTML é definido por:

Tag inicial

Conteúdo

Tag final

Exemplo:

<tagname>O conteúdo vai aqui...</tagname>

👉 O elemento HTML é tudo, desde a tag inicial até a tag final.

Exemplo prático:

<h1>Meu Primeiro Título</h1>
<p>Meu primeiro parágrafo.</p>

Sobre o Modo Quirks

O Modo Quirks pode ser ativado quando a declaração <!DOCTYPE html> não está presente no código.

Esse modo faz o navegador renderizar a página como se fosse um documento antigo, quebrando padrões do HTML5.

Para evitar problemas:
Sempre inclua no início do documento:

<!DOCTYPE html>


Assim o navegador vai renderizar a página seguindo os padrões mais recentes do HTML5.


