# HTML IFRS

Repositório criado para acompanhar meus estudos de **HTML5**, reunindo exemplos, exercícios e experimentos práticos desenvolvidos durante o aprendizado de desenvolvimento web.

O projeto tem como objetivo registrar minha evolução no aprendizado de HTML, começando pelos conceitos fundamentais e avançando para elementos semânticos, formatação de textos, listas, links, imagens e imagens responsivas.

---

## 📚 Sobre o projeto

Este repositório funciona como um **laboratório de estudos de HTML5**.

Cada arquivo contém um exemplo específico de algum recurso da linguagem, permitindo estudar os conceitos de forma isolada e consultar os exemplos posteriormente.

Os principais conteúdos estudados são:

* Estrutura básica de documentos HTML5;
* Parágrafos;
* Títulos;
* Quebras de linha;
* Separadores;
* Formatação e semântica de textos;
* Abreviaturas;
* Links;
* Listas ordenadas;
* Listas não ordenadas;
* Listas de descrição;
* Imagens;
* Imagens responsivas;
* Tags estruturais e semânticas do HTML5;
* Atributos HTML.

---

## 🗂️ Estrutura do projeto

```text
html-ifrs/
├── README.md
├── abreviaturas.html
├── formatacaoDeTexto.html
├── links.html
├── listasDeDescricao.html
├── listasNaoOrdenadas.html
├── listasOrdenadas.html
├── paragrafo.html
├── quebraDeLinha.html
├── separador.html
├── tags-estruturais.html
├── titulos.html
│
├── estudoSobreImagens/
│   ├── imagem001.html
│   ├── imagem002.html
│   └── img/
│       ├── img.jpg
│       ├── img-grande.jpg
│       ├── img-medio.jpg
│       └── img-pequeno.jpg
│
└── meu-projeto-html/
    └── index.html
```

---

## 📖 Conteúdos estudados

### 🧱 Estrutura básica do HTML

O arquivo [`meu-projeto-html/index.html`](meu-projeto-html/index.html) apresenta uma página HTML simples utilizando a estrutura básica de um documento HTML5.

Entre os elementos utilizados estão:

* `<!DOCTYPE html>`
* `<html>`
* `<head>`
* `<meta>`
* `<title>`
* `<body>`
* `<h1>`
* `<p>`

---

### 📝 Parágrafos

O arquivo [`paragrafo.html`](paragrafo.html) apresenta o uso do elemento `<p>` para criação de parágrafos.

Exemplo:

```html
<p>Primeiro Parágrafo</p>
<p>Segundo Parágrafo</p>
<p>Terceiro Parágrafo</p>
```

---

### 🔤 Títulos

O arquivo [`titulos.html`](titulos.html) apresenta os seis níveis de títulos disponíveis no HTML:

```html
<h1>Título 1</h1>
<h2>Título 2</h2>
<h3>Título 3</h3>
<h4>Título 4</h4>
<h5>Título 5</h5>
<h6>Título 6</h6>
```

Os elementos vão de `<h1>` até `<h6>`, permitindo estabelecer uma hierarquia de títulos no documento.

---

### ↩️ Quebra de linha

O arquivo [`quebraDeLinha.html`](quebraDeLinha.html) apresenta o elemento `<br>`, utilizado para inserir uma quebra de linha dentro do conteúdo.

```html
<p>
    Primeiro conteúdo <br>
    Segundo conteúdo
</p>
```

---

### ➖ Separadores

O arquivo [`separador.html`](separador.html) apresenta o elemento `<hr>`, utilizado para representar uma mudança temática ou separação entre conteúdos.

```html
<p>Este é um parágrafo</p>

<hr>

<p>Este é outro parágrafo</p>
```

---

## ✍️ Formatação de texto

O arquivo [`formatacaoDeTexto.html`](formatacaoDeTexto.html) reúne exemplos de diferentes elementos relacionados à formatação e semântica de textos.

Entre eles:

| Elemento   | Utilização                                              |
| ---------- | ------------------------------------------------------- |
| `<mark>`   | Destacar um trecho de texto                             |
| `<strong>` | Indicar importância                                     |
| `<em>`     | Dar ênfase ao conteúdo                                  |
| `<u>`      | Sublinhado                                              |
| `<s>`      | Representar conteúdo que não é mais válido ou relevante |
| `<sup>`    | Texto sobrescrito                                       |
| `<sub>`    | Texto subscrito                                         |

Exemplo:

```html
<strong>Texto importante</strong>

<em>Texto enfatizado</em>

<mark>Texto destacado</mark>

2<sup>3</sup>

H<sub>2</sub>O
```

> **Observação:** elementos como `<u>` não devem ser utilizados simplesmente para definir aparência visual quando o objetivo puder ser alcançado com CSS.

---

## 🔤 Abreviaturas

O arquivo [`abreviaturas.html`](abreviaturas.html) apresenta o elemento `<abbr>`, utilizado para representar abreviações ou acrônimos.

```html
<abbr title="Hypertext Markup Language">HTML</abbr>
```

Ao passar o cursor sobre a abreviatura, o navegador pode apresentar o conteúdo definido no atributo `title`.

---

## 🔗 Links

O arquivo [`links.html`](links.html) apresenta o elemento `<a>`, utilizado para criar hyperlinks.

Também é demonstrado o uso de uma imagem dentro de um link:

```html
<a href="https://portal.ifrn.edu.br/" title="Clique aqui">
    <img src="..." alt="link da imagem">
</a>
```

Esse recurso permite transformar uma imagem em um elemento clicável.

---

## 📋 Listas

O projeto contém exemplos dos principais tipos de listas disponíveis no HTML.

### Lista ordenada

O arquivo [`listasOrdenadas.html`](listasOrdenadas.html) apresenta o elemento `<ol>`:

```html
<ol reversed>
    <li>Primeiro item</li>
    <li>Segundo item</li>
    <li>Terceiro item</li>
</ol>
```

Também é utilizado o atributo `reversed`, que faz a numeração da lista ser apresentada em ordem decrescente.

---

### Lista não ordenada

O arquivo [`listasNaoOrdenadas.html`](listasNaoOrdenadas.html) apresenta o elemento `<ul>`:

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

Cada item é representado pelo elemento `<li>`.

---

### Lista de descrição

O arquivo [`listasDeDescricao.html`](listasDeDescricao.html) apresenta os elementos:

* `<dl>` — lista de descrição;
* `<dt>` — termo;
* `<dd>` — descrição.

Exemplo:

```html
<dl>
    <dt>Título 1</dt>
    <dd>Descrição do título 1</dd>

    <dt>Título 2</dt>
    <dd>Descrição do título 2</dd>
</dl>
```

---

# 🖼️ Estudos sobre imagens

A pasta [`estudoSobreImagens/`](estudoSobreImagens/) reúne exemplos relacionados à utilização de imagens em HTML.

```text
estudoSobreImagens/
├── imagem001.html
├── imagem002.html
└── img/
    ├── img.jpg
    ├── img-grande.jpg
    ├── img-medio.jpg
    └── img-pequeno.jpg
```

---

## 🖼️ Elemento `<img>`

O arquivo [`imagem001.html`](estudoSobreImagens/imagem001.html) apresenta a utilização do elemento `<img>`.

```html
<img
    src="img/img.jpg"
    alt="Ambulância com fundo preto"
    title="Título da imagem"
>
```

Também são apresentados atributos importantes como:

* `src` — caminho da imagem;
* `alt` — texto alternativo;
* `title` — informação adicional;
* `style` — exemplo de estilização diretamente no elemento.

---

## 📱 Imagens responsivas

O arquivo [`imagem002.html`](estudoSobreImagens/imagem002.html) apresenta o elemento `<picture>` juntamente com `<source>`.

```html
<picture>
    <source
        media="(min-width: 800px)"
        srcset="img/img-grande.jpg"
    >

    <source
        media="(min-width: 450px)"
        srcset="img/img-medio.jpg"
    >

    <img
        src="img/img-pequeno.jpg"
        alt="Descrição da imagem"
    >
</picture>
```

Esse recurso permite disponibilizar diferentes arquivos de imagem de acordo com as características do dispositivo ou da tela.

O projeto possui versões da imagem em diferentes tamanhos:

* `img-pequeno.jpg`
* `img-medio.jpg`
* `img-grande.jpg`
* `img.jpg`

---

# 🧩 Tags estruturais e semânticas

O arquivo [`tags-estruturais.html`](tags-estruturais.html) apresenta alguns dos principais elementos semânticos do HTML5.

```html
<header>
    <h1>Cabeçalho</h1>
</header>

<nav>
    Menu
</nav>

<main>

    <section>
        <article>
            Conteúdo do site
        </article>

        <article>
            Mais conteúdo do site
        </article>
    </section>

    <aside>
        Conteúdo relacionado
    </aside>

</main>

<footer>
    Rodapé
</footer>
```

Os principais elementos estudados são:

| Elemento    | Função                           |
| ----------- | -------------------------------- |
| `<header>`  | Cabeçalho de uma página ou seção |
| `<nav>`     | Área de navegação                |
| `<main>`    | Conteúdo principal               |
| `<section>` | Seção temática                   |
| `<article>` | Conteúdo independente            |
| `<aside>`   | Conteúdo relacionado             |
| `<footer>`  | Rodapé                           |

O objetivo é compreender como o HTML5 permite estruturar uma página de maneira mais semântica e organizada.

---

# 🛠️ Tecnologias

Este projeto utiliza principalmente:

* **HTML5**
---

# 👨‍💻 Autor

**José Jacsan**

* GitHub: [@JoseJacsanCode](https://github.com/JoseJacsanCode)

---

## ⭐ Objetivo do projeto

Este projeto possui finalidade **educacional** e representa uma parte da minha jornada de aprendizado em desenvolvimento web.

A ideia é utilizar o repositório não apenas para armazenar códigos, mas também para registrar minha evolução e construir uma base sólida antes de avançar para **CSS, JavaScript e outras tecnologias do desenvolvimento web**.
