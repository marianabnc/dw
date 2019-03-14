# Roteiro das Aulas

[\# 01 - Apresentação da Disciplina (15/03/2019, SEX)](#-01---apresentação-da-disciplina-15032019-sex)<br>
[\# 02 - Estrutura com HTML (22/03/2019, SEX)](#-02---estrutura-com-html-22032019-sex)<br>
[\# 03 - Estilo com CSS (29/03/2019, SEX)](#-03---estilo-com-css-29032019-sex)<br>
[\# 04 - Criando e reutilizando CSS (05/04/2019, SEX)](#-04---criando-e-reutilizando-css05042019-sex8)<br>
[\# 05 - Criando Dashboard Admin (12/04/2019, SEX)](#-05---criando-dashboard-admin-12042019-sex)<br>
[\# 06 - Avalição de HTML e CSS & Introdução ao Javascript ECMA (26/04/2019, SEX)](#-06---avalição-de-html-e-css--introdução-ao-javascript-ecma-26042019-sex)<br>
[\# 07 - Introdução ao Javascript Web (03/05/2019, SEX)](#-07---introdução-ao-javascript-web-03052019-sex)<br>
[\# 08 - Geração Dinâmica com JS (10/05/2019, SEX)](#-08---geração-dinâmica-com-js-10052019-sex)<br>
[\# 09 - Consumindo JSON e Geração Dinâmica com JS (17/05/2019, SEX)](#-09---consumindo-json-e-geração-dinâmica-com-js-17052019-sex)<br>
[\# 10 - Pacotes JS (24/05/2019, SEX)](#-10---pacotes-js-24052019-sex)<br>
[\# 11 - Avalição de Javascript e Propostas de Projeto (31/05/2019, SEX)](#-11---avalição-de-javascript-e-propostas-de-projeto-31052019-sex)<br>
[\# 12 - Acompanhamento do Projeto (07/06/2019, SEX)](#-12---acompanhamento-do-projeto-07062019-sex)<br>
[\# 13 - Servidor LAMP e Projeto Final (Front-end) (14/06/2019, SEX)](#-13---servidor-lamp-e-projeto-final-front-end-14062019-sex)<br>
[\# 14 - Fundamentos de PHP (28/06/2019, SEX)](#-14---fundamentos-de-php-28062019-sex)<br>
[\# 15 - APIs em PHP (09/08/2019, SEX)](#-15---apis-em-php-09082019-sex)<br>
[\# 16 - PHP Web (16/08/2019, SEX)](#-16---php-web-16082019-sex)<br>
[\# 17 - MySQL (17/08/2019, SÁB)](#-17---mysql-17082019-sáb)<br>
[\# 18 - PHP PDO (23/08/2019, SEX)](#-18---php-pdo-23082019-sex)<br>
[\# 19 - Acompanhamento do Projeto (30/08/2019, SEX)](#-19---acompanhamento-do-projeto-30082019-sex)<br>
[\# 20 - Avaliação de PHP e Projeto Final (Back-end) (31/08/2019, SÁB)](#-20---avaliação-de-php-e-projeto-final-back-end-31082019-sáb)<br>

## \# 01 - Apresentação da Disciplina (15/03/2019, SEX)
---

**Conteúdo:**
- Apresentação da disciplina:
  - Objetivo, conteúdo, avaliação, comunicação, bibliografia e ferramentas
  - [O que você vai aprender em DW?](http://slides.com/luizcarlos/o-que-vou-aprender-em-dw#/)
  - Conteúdo
    - Fundamento e finalidade do frontend (HTML, CSS, JS) e backend (PHP, MySQL)
    - Exibindo a [arquitetura da Web](https://www.youtube.com/watch?v=guvsH5OFizE) ([Tripé: URL, HTTP, HTML](https://ifpb.github.io/web-guide/slides/web.pdf))
    - [Fundamentos de uma Linguagem de Marcação](https://ifpb.github.io/html-guide/markup/)

**Reflexão:**
* O que você vai aprender em LM?
* Qual o nome e utilidade das tecnologias você irá aprendar nesta disciplina?
* Explique como é possível transferir documentos antes e depois da Web.
* Qual é o tripé da Web? 
* Qual é a diferença entre um conteúdo estático e dinâmico?
* É possível formatar um documento (título, negrito, itálico, etc) usando apenas uma arquivo de texto? Caso afirmativo, dê exemplos de como seria isto?
* Explique porque as linguagens de marcação exigem programas específicos.
* A legibilidade de uma linguagem de marcação tem alguma relação com o tamanho do documento?

**Exercício:**
* Analise o [site da discplina](https://ifpb.github.io/dw/) e se inscreva no channel `#dw-20192` do [slack do ifpb](https://ifpb.slack.com).
* Configure seu computador com essas [ferramentas](TOOLS.md).
* Descreva o que acontece ao acessar uma página da Web, como a do [IFPB](http://www.ifpb.edu.br)
* Pesquise sobre a evolução da Web.
* Descreva o que é uma Linguagem de Marcação.
* Veja e se inspire nos [projetos](https://ifpb.github.io/projects/) já realizados nesta disciplina.

## \# 02 - Estrutura com HTML (22/03/2019, SEX)
---

**Conteúdo:**
- [HTML](https://ifpb.github.io/html-guide/html/) 
  - [Sintase](https://ifpb.github.io/html-guide/html/syntax/): Tags, Atributos, Entidades, Comentários
  - [Elementos de Cabeçalho](https://ifpb.github.io/html-guide/html/head-elements/)
  - [Elementos textuais](https://ifpb.github.io/html-guide/html/text-elements/): [list](https://ifpb.github.io/html-guide/html/list/), [hyperlink](https://ifpb.github.io/html-guide/html/hyperlink/), [image](https://ifpb.github.io/html-guide/html/image-multimedia/), [table](https://ifpb.github.io/html-guide/html/table/)
- Editando HTML com [Visutal Studio Code (vscode)](http://code.visualstudio.com) e visualizando com o [Google Chrome](https://www.google.com/chrome/)
- [Referências dos Elementos no MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/)

**Reflexão:**

* Qual é a sintaxe básica do HTML?
* Qual é a estrutura mínima recomendada para uma página HTML?
* Como criar listas, hiperlinks, listas, tabelas e imagens?

**Exercício:**
* Reconstrua a [Primeira Página da Web](https://ifpb.github.io/html-exercises/html/first-web-page/)
* [Inspecione uma página na Web](https://ifpb.github.io/html-exercises/html/inspect-page/)
* Estruture o manual do [comando PING](https://ifpb.github.io/html-exercises/html/man-ping/) em HTML ([Fonte](https://linux.die.net/man/8/ping))
* Escolha algum manual do [GNU Manuals Online](https://www.gnu.org/manual/manual.html) ou do [Debian](https://www.debian.org/doc/) para tentar reproduzi-lo parcialmente.

## \# 03 - Estilo com CSS (29/03/2019, SEX)
---

**Conteúdo:**
- [CSS](https://ifpb.github.io/css-guide/css/)
  - [Configuração do CSS](https://ifpb.github.io/css-guide/css/stylesheets/)
  - [Inspecionando estilos dos Elementos](https://developers.google.com/web/tools/chrome-devtools/inspect-styles/): Analisando e editando estilos
  - Sintaxe
    - [Propriedades](https://ifpb.github.io/css-guide/css/property/)
    - [Seletores](https://ifpb.github.io/css-guide/css/selector/)
    - [Funções](https://ifpb.github.io/css-guide/css/function/)
    - [At-rules](https://ifpb.github.io/css-guide/css/at-rule/)
    - [Media query](https://ifpb.github.io/css-guide/css/media-query/)
  - [Herança no CSS](https://ifpb.github.io/css-guide/css/inheritance/)
  - Estilos para [Tipografia](https://ifpb.github.io/css-guide/css/typography/), [Hyperlink](https://ifpb.github.io/css-guide/css/hyperlink/)

**Reflexão:**
* Como aplicar estilo no HTML?
* Quais são os elementos sintáticos do CSS?
* Qual é o benefício da Herança no CSS?
* É possível ver os estilos de um elemento sem ver diretamente o código fonte?
* Quais estilos podemos aplicar em um texto?

**Exercício:**
* [Criando seu primeiro estilo](https://ifpb.github.io/css-exercises/css/hello-world-css/)
* [Selecionando elementos no HTML](https://ifpb.github.io/css-exercises/css/selector-css/)
* [Curriculum Vitae com Estilo](https://ifpb.github.io/css-exercises/css/curriculum-style-text/)
* Estilize o mamual do comando Ping em CSS:
  * [Proposta](https://ifpb.github.io/css-exercises/css/man-ping/) de [Miguel Cabral](https://github.com/BelarminoM)

## \# 04 - Criando e reutilizando CSS (05/04/2019, SEX)
---

**Conteúdo:**
- [CSS](https://ifpb.github.io/css-guide/css/)
  - [Box Model](https://ifpb.github.io/css-guide/css/box-model/)
  - [Background](https://ifpb.github.io/css-guide/css/background/)
- Uso de bibliotecas no CSS
  - [Web Fontes](https://ifpb.github.io/css-guide/css/web-font/)
  - [Ícones](https://ifpb.github.io/css-guide/css/icon/)
- [Bootstrap](https://ifpb.github.io/css-guide/packages/bootstrap/)

**Reflexão:**

* O que é um elemento de bloco e de linha?
* Que configurações de tamanho podemos aplicar em um elemento de bloco?
* Como utilizamos fontes do Google Fonts?
* Como utilizamos ícones?
* Que estilos podemos aplicar em uma tabela?
* Como reutilizar estilos de terceiros?
* Quais são os prós e contras de utilizar o Bootstrap?
* Como habilitamos o Bootstrap no HTML e CSS?
* Com o Bootstrap é possível normalizar o estilo do seu HTML?
* É possível definir alguma layout usando Bootstrap?
* Qual é a diferença entre `Content` e `Components` no Bootstrap?


**Exercício:**
* Analise o Box Model desses [títulos](https://ifpb.github.io/css-guide/css/box-model/headers-box-model/)
* Crie essa [página](https://ifpb.github.io/css-exercises/css/text-simple/code-response/) usando os recursos CSS da aula de hoje.
* [Criando Dashboard Admin](https://ifpb.github.io/css-exercises/packages/bootstrap/dashboard-admin/)
  * [Proposta do Ample Admin](https://ifpb.github.io/css-exercises/packages/bootstrap/dashboard-admin/response/ample-admin-walisson) de [Walisson Silva](https://github.com/walissonsilva)

## \# 05 - Criando Dashboard Admin (12/04/2019, SEX)
---

**Conteúdo:**
- [HTML](https://ifpb.github.io/html-guide/html/) 
- [CSS](https://ifpb.github.io/css-guide/css/)

**Reflexão:**
- O que foi visto de HTML e CSS até o momento?

**Exercício:**
* Simulado de HTML e CSS:
  * [Dashboard Monitor](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/dashboard-monitor/)
  * [Host Monitor](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/host-monitor/)
  * [eZ Server Monitor](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/ez-server-monitor/)
    * [Proposta](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/ez-server-monitor/code-response/walisson/) de [Walisson Silva](https://github.com/walissonsilva)
  * [Pingdom Monitor](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/pingdom-monitor/)

**Projeto:**

> Especificação do [Projeto Final](../exams/projeto.md)

## \# 06 - Avalição de HTML e CSS & Introdução ao Javascript ECMA (26/04/2019, SEX)
---

**Avaliação:**
> [Avaliação de HTML e CSS](../exams/prova-html-css.md)

**Conteúdo:**
- [Executando Javascript](https://ifpb.github.io/javascript-exercises/ecma/running-javascript.html): prompot do Node.js
- Editando Javascript com [Visutal Studio Code (vscode)](http://code.visualstudio.com) e executando com o [Node.js](https://nodejs.org/en/)
- [Javascript EcmaScript](https://ifpb.github.io/javascript-guide/ecma/)
  - [Variável](https://ifpb.github.io/javascript-guide/ecma/variable/)
  - [Tipos](https://ifpb.github.io/javascript-guide/ecma/)
  - [Expressões e operadores](https://ifpb.github.io/javascript-guide/ecma/expression-and-operator/)
  - [Estrutura de Decisão e Repetição](https://ifpb.github.io/javascript-guide/ecma/statements-and-declarations/)
  - [Funções](https://ifpb.github.io/javascript-guide/ecma/function/)

**Reflexão:**
* Como executamos código Javascript? Que ferramentas podemos usar para programar em Javascript?
* Como declaramos variáveis no Javascript?
* Quais são os tipos primitivos e objetos do Javascript?
* Quais são os operadores do Javascript? Como podemos montar expressões?
* Como saber se um operador é unário, binário ou ternário?
* Quais são as estruturas de decisão e repetição do Javascript?
* O que acontece quando passamos uma quantidade de argumentos diferente do total de parâmetros?
* O que são parâmetros default dentro das funções no Javascript?

**Exercício:**
* Crie um script para:
  * Através de `const x = 8` definir `x+2` (10)
  * Através de `const x = 8` definir `x²` (64)
  * Através de `const x = 8` definir `∛x` (2)
  * Através de `const x = 8` definir `3x²+12x-4` (284)
  * Através de `const x = 8` definir `x+3 > √x` (true)
  * Calcular o [IMC](https://ifpb.github.io/javascript-exercises/ecma/basic/bmi/) usando `if` e `switch`
  * Exibir a séria de [00 até 99](https://ifpb.github.io/javascript-exercises/ecma/basic/numbers/) de dez em dez.
  * [Somar](https://ifpb.github.io/javascript-exercises/ecma/function/sum/)
  * [Calcular a área do círculo](https://ifpb.github.io/javascript-exercises/ecma/function/area-of-circle/)
  * [Calcular operações aritméticas básicas](https://ifpb.github.io/javascript-exercises/ecma/function/calc/)
* Veja outros [exercícios](https://ifpb.github.io/javascript-exercises/ecma/) com JS.

## \# 07 - Introdução ao Javascript Web (03/05/2019, SEX)
---

**Conteúdo:**
- Formulário
  - [Estrutura](https://ifpb.github.io/html-guide/html/form/)
  - [Bootstrap > Form](https://getbootstrap.com/docs/4.1/components/forms/)
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [Running Javascript in Browser](https://ifpb.github.io/javascript-guide/w3c/running-javascript-browser/)
  - [Window](https://ifpb.github.io/javascript-guide/w3c/window/window.html)
  - [DOM](https://ifpb.github.io/javascript-guide/w3c/dom/) 
    - [Node (DOM tree)](https://ifpb.github.io/javascript-guide/w3c/dom/node.html)
    - [Document](https://ifpb.github.io/javascript-guide/w3c/dom/document.html): `querySelector()`
    - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `innerHTML`, `setAttribute()`
    - [HTML Element](https://ifpb.github.io/javascript-guide/w3c/dom/html-element.html): `style`
    - [HTML Input Element](https://ifpb.github.io/javascript-guide/w3c/dom/html-input-element.html): `checked`, `value`
  - [DOM Event](https://ifpb.github.io/javascript-guide/w3c/dom-event/): `onclick`

**Reflexão:**
* Para que serve os formulários e como estruturamos um?
* Como integramos Javascript com HTML no Navegador?
* É possível acessar recusos do Navegador com o Javascript? Por exemplo, é possivel acessar os botões de navegação de histórico? Ou a URL da barra de endereço?
* Qual a importância da árvore DOM para o Javascript?
* Um Elemento no HTML pode ser analisado como sendo mais de um objeto no DOM? Mostre algum exemplo.
* Como acessamos um elemento do HTML via `document` no Javascript?
* Como acessamos ou alteramos o conteúdo dos elementos `<div>`, `<input type="text">` e `<input type="radio">` (selecionado)?
* Como alteramos o estilo de um elemento no Javascript?
* No exercício do IMC gráfico, explique como alteramos a cor do resultdo do IMC conforme o resultado, por exemplo, vermelho para obeso e assim por diante.
* Como atribuímos um evento em um botão no Javascript?

**Exercício:**
* Crie uma interface Web para:
  * Este [formulário](https://ifpb.github.io/html-guide/html/form/#simple-form) usando a estilização do Bootstrap ([form](https://ifpb.github.io/css-guide/packages/bootstrap/form/) e [form-row](https://ifpb.github.io/css-guide/packages/bootstrap/form-row/)).
  * Calcular o:
    * [IMC](https://ifpb.github.io/javascript-exercises/w3c/bmi-simple/).
    * [IMC com Estilo](https://ifpb.github.io/javascript-exercises/w3c/bmi-css/)
    * [IMC com Validação](https://ifpb.github.io/javascript-exercises/w3c/bmi-validator/)

## \# 08 - Geração Dinâmica com JS (10/05/2019, SEX)
---

**Conteúdo:**
- [Javascript EcmaScript](https://ifpb.github.io/javascript-guide/ecma/)
  - [Funções Anônimas](https://ifpb.github.io/javascript-guide/ecma/function/#function-expression--anonymous-function)
  - Array ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/array/syntax.html), [objeto](https://ifpb.github.io/javascript-guide/ecma/array/object.html))
  - String ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/string/syntax.html), [objeto](https://ifpb.github.io/javascript-guide/ecma/string/object.html))
  - JSON ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/json/syntax.html), [manipulação](https://ifpb.github.io/javascript-guide/ecma/object/syntax.html#changing-object), [iterando](https://ifpb.github.io/javascript-guide/ecma/object/syntax.html#object-interaction))
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `insertAdjacentHTML()`
  - [HTML Element](https://ifpb.github.io/javascript-guide/w3c/dom/html-element.html): `focus()`
  - [DOM Event](https://ifpb.github.io/javascript-guide/w3c/dom-event/)
    - [EventTarget](https://ifpb.github.io/javascript-guide/w3c/dom-event/event-target.html): `addEventListener()`
    - [GlobalEventHandlers](https://ifpb.github.io/javascript-guide/w3c/dom-event/global-event-handlers.html): `onclick`
  
**Reflexão:**
* No Javascript, como manipulamos (criar, alterar, iterar, ações) String, Array e JSON?
* Como estruturamos dados compostos em Javascript?
* O que são funções anônimas?
* Como adicionamos eventos a um elemento específico?
* No exercício do IMC com evento, explique como adicionamos eventos:
  * Na tecla 'Enter' para exibir o resultado do IMC;
  * Na tecla 'Escape' para limpar os valores digitados nos `<input>`, e focar no primeiro `<input>`.
* Como inserimos um novo parágrafo no final da `<div>` a seguir sem recriar seus elementos internos?

```html
<div>
  <p>Lorem ipsum dolor</p>
  <p>Dolor ipsum lorem</p>
</div>
```

**Exercício:**
* Crie um script para:
  * [Array Operation](https://ifpb.github.io/javascript-exercises/ecma/array/array-operations/)
  * [Array Util](https://ifpb.github.io/javascript-exercises/ecma/array/array-util/)
  * [List Generator](https://ifpb.github.io/javascript-exercises/ecma/string/list-generator/)
* Crie uma representação desse dado no JS:

| Host | Address | Mask |
|-|-|-|
| PC 1	| 192.168.0.1 |	255.255.255.0 |
| Server	| 10.0.0.1 |	255.255.255.0 |

* Crie uma interface Web para:
  * Calcular o [IMC com Evento](https://ifpb.github.io/javascript-exercises/w3c/bmi-event/)
  * [Calculadora](https://ifpb.github.io/javascript-exercises/w3c/calculator/)
  * [Gerador de list](https://ifpb.github.io/javascript-exercises/w3c/list-generator/)
  * Tabela de IPs ([Read](https://ifpb.github.io/javascript-exercises/w3c/iptable-read/), [Create](https://ifpb.github.io/javascript-exercises/w3c/iptable-create/), [Create Uniq](https://ifpb.github.io/javascript-exercises/w3c/iptable-create-uniq/))

## \# 09 - Consumindo JSON e Geração Dinâmica com JS (17/05/2019, SEX)
---

**Conteúdo:**
- [Web API](https://ifpb.github.io/javascript-guide/ecma/json/syntax.html#web-api)
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [Fetch API](https://ifpb.github.io/javascript-guide/w3c/fetch-api/) ([AJAX](https://ifpb.github.io/javascript-guide/w3c/xmlhttprequest/#asynchronous-javaScript-and-xml-ajax))
  - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `remove()`
  - [Node](https://ifpb.github.io/javascript-guide/w3c/dom/node.html): `parentNode`

**Reflexão:**
* Por que as Web API geralmente respondem com JSON?
* O que o Fetch API permite fazer?
* Como exibimos apenas a cidade do IP `8.8.8.8` usando a API do [ipinfo.io](https://ipinfo.io/developers)? Use essa rota `https://ipinfo.io/8.8.8.8/json` e o [Fetch API](https://ifpb.github.io/javascript-guide/w3c/fetch-api/).
* Como removemos um elemento no HTML via Javascript?

**Exercício:**
* [Gentelella App Versions](https://ifpb.github.io/javascript-exercises/w3c/gentelella-app-versions/)
* [Gentelella Top Tiles](https://ifpb.github.io/javascript-exercises/w3c/gentelella-top-tiles)
* [IP Info 1](https://ifpb.github.io/javascript-exercises/w3c/ipinfo-table-api/)
* [IP Info 2](https://ifpb.github.io/javascript-exercises/w3c/ipinfo-api/)
* [Tabela de IPs (CRUD)](https://ifpb.github.io/javascript-exercises/w3c/iptable/)

## \# 10 - Pacotes JS (24/05/2019, SEX)
---

**Conteúdo:**
* [Javascript Ecma](https://ifpb.github.io/javascript-guide/ecma/)
* [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
* [Javascript Packages](https://ifpb.github.io/javascript-guide/packages/)

**Reflexão:**
* Como montamos gráficos usando Javascript?

**Exercício:**
* [Javascript Ecma](https://ifpb.github.io/javascript-exercises/ecma/)
* [Javascript W3C](https://ifpb.github.io/javascript-exercises/w3c/)
* [Javascript Packages](https://ifpb.github.io/javascript-exercises/packages/)
  * [Ample Admin Charts](https://ifpb.github.io/javascript-exercises/packages/charts/ample-admin-charts/)
* [Javascript Challenges](https://ifpb.github.io/javascript-exercises/challenges/)
  * [Dashborad Monitor](https://ifpb.github.io/javascript-exercises/challenges/w3c/dashboard-monitor/)
  * [eZ Server Monitor](https://ifpb.github.io/javascript-exercises/challenges/w3c/ez-server-monitor/)
  * [Host Monitor](https://ifpb.github.io/javascript-exercises/challenges/w3c/host-monitor/)
  * [Pingdom Monitor](https://ifpb.github.io/javascript-exercises/challenges/w3c/pingdom-monitor/)

## \# 11 - Avalição de Javascript e Propostas de Projeto (31/05/2019, SEX)
---

**Avaliação:**

> Todos os detalhes da avaliação estão disponíveis nesta [página](../exams/prova-js.md)

**Projeto:**

> Apresentação das propostas de [projetos](../exams/projeto.md).

## \# 12 - Acompanhamento do Projeto (07/06/2019, SEX)
---

> [Projeto Final](../exams/projeto.md)

## \# 13 - Servidor LAMP e Projeto Final (Front-end) (14/06/2019, SEX)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [Lamp Server](https://ifpb.github.io/php-guide/lamp/)

**Reflexão:**
* Como configurar um ambiente backend com PHP e MySQL?

**Projeto:**

> Apresentação do Front-end dos [projetos](../exams/projeto.md).

## \# 14 - Fundamentos de PHP (28/06/2019, SEX)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Core](https://ifpb.github.io/php-guide/core/)
    - [Values and Types](https://ifpb.github.io/php-guide/core/values-and-types/)
    - [Variable](https://ifpb.github.io/php-guide/core/variable/)
    - [Expression and Operator](https://ifpb.github.io/php-guide/core/expression-and-operator/)
    - [Statements](https://ifpb.github.io/php-guide/core/statements/)
    - [Function](https://ifpb.github.io/php-guide/core/function/)
  - [PHP Stdlib](https://ifpb.github.io/php-guide/stdlib/)
    - Process Control Extensions
      - [Program execution](https://ifpb.github.io/php-guide/stdlib/program-execution/)

**Reflexão:**
* Como executamos código PHP?
* Quais são os tipos da linguagem PHP?
* Como declaramos variáveis no PHP?
* Quais são os operadores do PHP, e como elaboramos expressões?
* Quais são as estruturas de decisão e repetição do PHP?
* Como criamos uma função em PHP?
* O que acontece quando passamos uma quantidade de argumentos diferente do total de parâmetros?
* Como executamos comandos via PHP?
* Qual a finalidade do script [`ping.php`](https://ifpb.github.io/php-guide/stdlib/program-execution/#ping)?

**Exercício:**
* Crie um script para:
  * Através de `x = 10` definir `x+2`
  * Através de `x = 10` definir `x²`
  * Através de `x = 10` definir `3x²+12x-4`
  * Através de `x = 10` definir `x+3 > √x`
  * Calcular o [IMC](https://ifpb.github.io/php-exercises/core/basic/bmi/)
  * Gerar algumas [séries numéricas](https://ifpb.github.io/php-exercises/core/basic/numbers/)
  * Calcular a [soma de números](https://ifpb.github.io/php-exercises/core/function/sum/)
  * Calcular a [área do círculo](https://ifpb.github.io/php-exercises/core/function/area-of-circle/)
  * Calcular as [operações aritméticas básicas](https://ifpb.github.io/php-exercises/core/function/calc/)
* Como executar o comando `ls` por meio do PHP?

## \# 15 - APIs em PHP (09/08/2019, SEX)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Stdlib](https://ifpb.github.io/php-guide/stdlib/)
    - File System Related Extensions 
      - [Filesystem](https://ifpb.github.io/php-guide/stdlib/filesystem/)
    - Other Basic Extensions
      - [JSON](https://ifpb.github.io/php-guide/stdlib/json/)
    - Other Services
      - [SSH2 — Secure Shell2](https://ifpb.github.io/php-guide/stdlib/ssh2/)
    - Process Control Extensions 
      - [Program execution](https://ifpb.github.io/php-guide/stdlib/program-execution/)
    - Text Processing
      - [PCRE — Regular Expressions (Perl-Compatible)](https://ifpb.github.io/php-guide/stdlib/pcre/)
      - [Strings](https://ifpb.github.io/php-guide/stdlib/strings/)
  - [PHP Web](https://ifpb.github.io/php-guide/web/)
    - [HTTP Methods](https://ifpb.github.io/php-guide/web/http/)
    - [Web API](https://ifpb.github.io/php-guide/web/web-api/)

**Reflexão:**
* Como contruir uma página dinâmica no Front-end e no Back-end?
* Quais são as diferença entre o `$_POST` e `$_GET`?
* Como obter dados no PHP?
* Como executamos chamadas de sistema em PHP com e sem privilégio?
* Como editamos um arquivo de configuração por meio do PHP?
* Como formatar dados no PHP para retornar JSON?

**Exercício:**
* Crie uma API para listar arquivos de um `path` no formato JSON.
* Crie uma API dos serviços de um SO no qual é possível realizar as seguintes as ações `start` e `stop`. Dica, use o comando `service`.
* Crie o esquema da API do seu projeto baseado nos templates existentes em [Web API](https://ifpb.github.io/php-guide/web/web-api/).


## \# 16 - PHP Web (16/08/2019, SEX)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Web](https://ifpb.github.io/php-guide/web/)
    - [HTTP Methods](https://ifpb.github.io/php-guide/web/http/)
    - [Dynamic pages](https://ifpb.github.io/php-guide/web/dynamic-pages/)
    - [Session](https://ifpb.github.io/php-guide/web/session/)
    - [Web App](https://ifpb.github.io/php-guide/web/web-app/)
      - [PS App](https://ifpb.github.io/php-guide/web/web-app/ps/)
      - [Host Monitor Simple](https://ifpb.github.io/php-guide/web/web-app/monitor-host-simple/)

**Reflexão:**
- Como o PHP consegue tratar requisições HTTP GET e POST?
- O que munda no processamento de PHP quando a renderização de conteúdo é feito no lado Cliente e Servidor?
- Para que serve as sessões no PHP?
- Como criar um autenticação via sessão no PHP?
- Como consumir APIs para gerar interfaces Web dinâmicas?

**Exercício:**
- [EZ Server Monitor](https://ifpb.github.io/php-exercises/challenges/ez-server-monitor/)
- [Host Monitor](https://ifpb.github.io/php-exercises/challenges/host-monitor/)

## \# 17 - MySQL (17/08/2019, SÁB)
---

**Conteúdo:**
- [MySQL Guide](https://ifpb.github.io/mysql-guide/)
  - [Admin](https://ifpb.github.io/mysql-guide/admin/)
  - [SQL](https://ifpb.github.io/mysql-guide/sql/)

**Reflexão:**
- O que é e para que serve um banco de dados?
- Qual é a arquitetura básica de um serviço de banco em MySQL?
- Qual é a finalidade da linguagem SQL?
- Como criamos um banco, tabela e dados no MySQL?
- Como fazer CRUD em uma Tabela?
- O que é integridade de entidade e referencial?
- Quais são as [restrições](https://www.w3schools.com/sql/sql_constraints.asp) em um banco de dados relacional?

**Exercício:**
- Crie um banco de dados para seu projeto.

## \# 18 - PHP PDO (23/08/2019, SEX)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Stdlib](https://ifpb.github.io/php-guide/stdlib/)
    - [PDO - PHP Data Objects](https://ifpb.github.io/php-guide/stdlib/pdo/)
      - [CRUD](https://ifpb.github.io/php-guide/stdlib/pdo/#pdo-crud)
      - [Model](https://ifpb.github.io/php-guide/stdlib/pdo/#pdo-model)
        - [Host Simple Model](https://ifpb.github.io/php-guide/stdlib/pdo/codes/host-simple/)
        - [Host Address Model (1:1)](https://ifpb.github.io/php-guide/stdlib/pdo/codes/host-address/)
        - [Host Interfaces Model (1:n)](https://ifpb.github.io/php-guide/stdlib/pdo/codes/host-interface/)
        - [Host DNS Server Model (n:m)](https://ifpb.github.io/php-guide/stdlib/pdo/codes/host-dns/)
        - [Ping Model](https://ifpb.github.io/php-guide/stdlib/pdo/codes/ping/)
- Host Simple (DB)
  - [Model](https://ifpb.github.io/php-guide/stdlib/pdo/codes/host-simple/)
  - [API](https://ifpb.github.io/php-guide/web/web-api/codes/db/host/)
  - [App](https://ifpb.github.io/php-guide/web/web-app/host-simple-db/)

**Reflexão:**
- Como o PHP consegue manipular um banco de dados MySQL?
- Como usar o PDO para realizar um CRUD em uma Tabela?
- Como criar um modelo, API e interface Web de uma fonte de dados?

**Exercício:**
- Faça com que algum serviço da API do seu projeto seja persistido em banco.

## \# 19 - Acompanhamento do Projeto (30/08/2019, SEX)
---

> [Projeto Final](../exams/projeto.md)

## \# 20 - Avaliação de PHP e Projeto Final (Back-end) (31/08/2019, SÁB)
---

> Entrega do [Projeto Final](../exams/projeto.md) e da avaliação de [PHP](../exams/prova-php.md).

### E agora?

- Front-end
  - [CSS current work & how to participate](https://www.w3.org/Style/CSS/current-work)
  - [CSS-Tricks](https://css-tricks.com)
  - [Codrops \| Useful resources and inspiration for creative minds](https://tympanus.net/codrops/)
  - [CSSDB - A curated collection of great CSS, Sass, LESS and Stylus libraries](http://cssdb.co)
  - [best of js](https://bestofjs.org)
  - Github Topic: [HTML](https://github.com/topics/html), [CSS](https://github.com/topics/css), [JS](https://github.com/topics/javascript)
  - Curated list of awesome: [JS](https://github.com/sorrycc/awesome-javascript), [CSS](https://github.com/awesome-css-group/awesome-css), [HTML](https://github.com/diegocard/awesome-html5)
- Back-end
  - News: [Home](http://php.net), [PHP Weekly](http://www.phpweekly.com)
  - [Manuel PHP](http://php.net/manual/en/index.php)
  - [PHP Fig](https://www.php-fig.org)
  - Packages: [Composer](https://getcomposer.org), [Packagist](https://packagist.org)
  - Curated list of awesome: [PHP](https://github.com/ziadoz/awesome-php)
  - [Laravel](https://laravel.com)
- MySQL
  - [MySQL - SQL Statement Syntax](https://dev.mysql.com/doc/refman/5.7/en/sql-syntax.html)
  - Curated list of awesome: [DB](https://github.com/numetriclabz/awesome-db), [MySQL](http://shlomi-noach.github.io/awesome-mysql/)
