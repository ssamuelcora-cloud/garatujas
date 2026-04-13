# HTML

## O que é HTML - HyperText Markup Language (Linguagem de Marcação de Hipertexto)
HTML não é uma linguagem de programação, e sim uma linguagem de marcação. Ele é usado para organizar o conteúdo de uma página web. Muita gente acha que ele cuida da aparência, mas na verdade sua função é estruturar as informações para que qualquer pessoa consiga entender, inclusive usuários com deficiência. Por isso, um HTML bem feito melhora a acessibilidade e a experiência do usuário. Ele é formado por tags como `<h1>`, `<p>` e `<a>`, além de atributos como `class`, `id` e `src`.

## IMPORTANTE
O HTML organiza o conteúdo da página. Apesar de existirem tags como `<b>` e `<i>`, o mais recomendado hoje é usar `<strong>` e `<em>`, pois elas têm significado. `<strong>` indica importância e `<em>` indica ênfase, ajudando na acessibilidade. Já `<b>` e `<i>` são apenas visuais.

## Tags
As tags funcionam como “etiquetas” que identificam cada parte do conteúdo, deixando tudo mais organizado e fácil de entender. Por exemplo, `<p>` define um parágrafo e `<title>` define o título da página.

## Cores, fontes e etc.
É possível aplicar estilos diretamente nas tags, como `<p style="color: red;">` para mudar a cor ou `<p class="texto">` para usar classes. Para negrito, o mais correto é usar `<strong>`, como em `<p><strong>Texto em negrito</strong></p>`. Mesmo assim, o ideal é evitar muitos estilos direto no HTML.

## Utilizar stylesheet é uma boa prática?
Sim, é uma ótima prática. Em vez de colocar estilos em cada tag, você pode usar um arquivo CSS separado. Isso deixa o código mais organizado e fácil de modificar depois. Para isso, usa-se `<link rel="stylesheet" href="style.css">`.

## Estrutura básica de um documento HTML
Todo HTML começa com `<!DOCTYPE html>`. Depois vem a estrutura com `<html>`, `<head>` e `<body>`. O `<head>` guarda informações que não aparecem na tela, enquanto o `<body>` contém o conteúdo visível.

## Atributos HTML
Os atributos adicionam informações extras às tags e seguem o formato nome="valor". Exemplos comuns são `href`, `src` e `alt`. Um exemplo simples é `<a href="https://www.google.com">Visite o Google</a>`.

# CSS - Cascading Style Sheets

## O que é CSS
CSS é a linguagem responsável pela aparência da página. Enquanto o HTML organiza o conteúdo, o CSS define como ele será exibido. Com ele, você pode controlar cores, fontes, tamanhos, espaçamentos e layout.

## Como o CSS funciona
O CSS funciona com seletores e declarações. Os seletores escolhem os elementos, e as declarações definem o estilo.

## Exemplo básico com stylesheet
Você pode usar um arquivo externo para aplicar estilos. No HTML, escreve `<p>Texto de exemplo</p>`, e no CSS define `p { color: green; }`. Assim, o texto fica verde e o código continua organizado.
