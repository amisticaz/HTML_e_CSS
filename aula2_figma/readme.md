# Estrutura Básica de um Documento HTML e CSS

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
</head>
<body>
    <header></header>
    <main></main>
    <footer></footer>
</body>
</html>


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
</head>
<body>
    <header></header>
    <main></main>
    <footer></footer>
</body>


Tags Explicadas

<!DOCTYPE html>
Informa ao navegador que o documento é HTML5. Sem ela, pode ativar o Modo Quirks (renderização antiga).

<html lang="pt-br">
Tag raiz do documento.
O atributo lang="pt-br" define o idioma principal como português do Brasil (ajuda em SEO e acessibilidade).

<head>
Contém metadados sobre o documento, como título, codificação de caracteres e instruções para navegadores.

<meta charset="UTF-8">
Define a codificação como UTF-8 → suporta acentos e caracteres especiais.

<meta http-equiv="X-UA-Compatible" content="IE=edge">
Garante compatibilidade com a versão mais recente do Internet Explorer/Edge.

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Ajusta a largura da página à tela do dispositivo (design responsivo).

<title>
Define o título exibido na aba do navegador.

<body>
Contém todo o conteúdo visível da página.

<header>
Representa o cabeçalho → geralmente contém logo, título e navegação.

<main>
Define o conteúdo principal da página. Deve ser único.

<footer>
Define o rodapé → informações de contato, direitos autorais, links extras.

<h1> até <h6>
Títulos e subtítulos.

<h1> → título principal (só 1 por página).

<h2> até <h6> → subtítulos.

<p>
Define parágrafos de texto.

<a href="...">
Cria links de navegação.

Pode apontar para páginas externas ou seções internas (id).

Exemplo:

<a href="https://github.com/amisticaz" target="_blank">GitHub</a>

<figure> e <img>

<figure>: Container semântico para imagens.

<img>: Insere imagem.

src: caminho da imagem.

alt: texto alternativo (essencial para acessibilidade).

Exemplo:

<figure>
  <img src="./imagem.png" alt="Foto da Kethelen de Azevedo no Instituto Caldeira" width="300">
</figure>

<button>
Cria botões interativos. Pode ser usado em formulários ou com JavaScript.
Diferente do <a>, que serve para navegação.

Dicas: 

Acessibilidade
Usa alt descritivo em imagens e links mais claros:

<a href="https://linkedin.com/in/kethelendeazevedo" target="_blank">Visite meu LinkedIn</a>

 aprendemos a destacar o texto utilizando a tag <strong>, porém existe outra tag que também é muito utilizada para isso que é a tag <span>, diferente da strong a span não deixa em negrito por padrão, mas é uma ótima forma de marcar trechos do texto em HTML.

HTML:

<h1>Formação de <span>Front-end</span></h1>



# Documentação HTML e CSS
```html e css
CSS : 
cores: colors: https://coolors.co/ 
https://developer.mozilla.org/pt-BR/docs/Web/CSS/color_value
introdução ao css:
https://www.w3schools.com/css/css_intro.asp
html: 
https://www.w3schools.com/html/html_intro.asp
