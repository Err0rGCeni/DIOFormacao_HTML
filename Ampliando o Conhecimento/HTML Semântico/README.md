# Entendendo HTRML Semântico

> Semântica: Disciplina da linguística que se ocupa da significação das palavras e expressões linguísticas, bem como das relações e sentido que estas estabelecem entre si.

HTML4:

    <body>
        <div>...</div>
        <div>...</div>
        <div>...</div>
    </body>

HTML5:

    <body>
        <header>...</header>
        <main>...</main>
        <footer>...</footer>
    </body>

[w3](https://www.w3.org/TR/2014/NOTE-html5-diff-20141209/#language)

- Novos elementos:
  - `<main>` (recomendável um por página): Define o conteúdo principal, aquele relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação.
  - `<header>`: Representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um **logo**, **seções de cabeçalho**, **formulário de pesquisa**, e outros.
  - `<footer>`: Representa um rodapé para o seu conteúdo de seção mais próximo ou parente mais próximo. Normalmente um rodapé contém **informações sobre o autor** da seção de dados, **direitos autorais** ou **links para documentos** relacionados.
  - `<aside>`: Representa uma seção de uma página que consiste de conteúdo que é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo. Essas seções são, muitas vezes, representadas como barras laterais. Elas muitas vezes contem **explicações laterais**, como a definição de um **glossário**; **conteúdo vagamente relacionado**, como **avisos**; a **biografia do autor**; ou, em aplicações web, **informações de perfil** ou **links de blogs relacionados**.
  - `<section>`: Representa uma **seção genérica** contida em um documento HTML, **geralmente com um título**, quando não existir um elemento semântico mais específico para representá-lo.
  - `<nav>`: Representa uma **seção** de uma página que **aponta para outras páginas** ou para outras **áreas** da página, ou seja, uma seção com **links de navegação**.
  - `<article>`:  Representa uma **composição independente** em um documento, página, aplicação, ou site, ou que é destinado a ser distribuido de forma independente ou reutilizável, por exemplo, em sindicação. Este poderia ser o **post** de um fórum, um **artigo** de revista ou jornal, um post de um blog, um **comentário** enviado por um usuário, um **gadget ou widget interativos**, ou qualquer outra forma de conteúdo independente.
  - `<blockquote>`: Indica que o texto incluído é uma longa citação.
    - _citie_: Fonte da citação.
  - `<q>`: Indica que o texto dentro da tag é uma pequena citação. Este elemento destina-se a citações curtas que não requerem marcações de parágrafo.
  - `<figure>`: Representa conteúdo autocontido, potencialmente com uma legenda opcional. A figura, sua legenda e seu conteúdo são referenciados como uma única unidade.
    - `<figcaption>`: Legenda da figura.
  - `<picture>`:Usado para especificar múltiplos elementos `<source>` para um elemento específico `<img>` contido nele. O navegador irá escolher a imagem mais adequada.
- Depreciados:
  - `<basefont>`, `<big>`, `<center>`, `<font>`, `<strike>`, `<tt>`, `<frame>`, `<frameset>` ...
- Acessibilidade:
  - Accessible Rich Internet Applications (**ARIA**): Definem as formas de tornar o conteúdo e as aplicações mais acessíveis às pessoas com deficiência.
- Web Scraping: Aplicações usadas para descobrir e examinar sites automaticamente.
  - GoogleBot.
- Search Engine Optimization (**SEO**): Processo de fazer com que um site fique mais visível nos resultados da procura, também denominado **melhoramento na classificação da busca**.
  - Utiilzar títulos sucintos que condizem com o conteúdo da página (`<title>`);
  - Adicionar objetivas e condizentes (`<meta>`);
  - Conhecer o Schema.org;
  