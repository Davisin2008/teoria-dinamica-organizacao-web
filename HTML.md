### **1. Análise da Estrutura Textual de Páginas Web (Individual)**

**Páginas selecionadas:**

1. [G1 - Artigo de notícia](https://g1.globo.com)
2. [MDN Web Docs - Documentação](https://developer.mozilla.org/pt-BR/)
3. [Blog pessoal - dev.to](https://dev.to)

**Ferramenta usada:** "Inspecionar elemento" no navegador.

**Elementos encontrados:**

* `<p>` – Parágrafos. Usados para blocos de texto corrido.
* `<h1>` até `<h6>` – Títulos e subtítulos hierárquicos.
* `<strong>` – Para destacar algo com ênfase forte (semântica de importância).
* `<em>` – Ênfase com entonação (semântica de ênfase).
* `<br>` – Quebra de linha dentro de parágrafos ou frases.
* `<hr>` – Linha horizontal para separar seções de conteúdo.

**Funções semânticas:**

* `<h1>` e `<h2>`: Indicam a hierarquia do conteúdo, melhorando a navegação, leitura e SEO.
  Exemplo: Usar `<h1>` no título principal do artigo e `<h2>` para seções.

* `<strong>` vs. CSS: `<strong>` informa ao navegador e leitores de tela que o conteúdo tem importância; aplicar apenas `font-weight: bold;` em CSS muda só a aparência.

---

### **2. Explorando a Organização com Listas (Individual)**

**Elementos de lista encontrados:**

* `<ul>` – Lista não ordenada (ex.: menu de navegação).
* `<ol>` – Lista ordenada (ex.: passo a passo de instalação).
* `<li>` – Cada item de lista.
* `<dl>` – Lista de definição (ex.: glossário).
* `<dt>` – Termo definido.
* `<dd>` – Definição do termo.

**Análise:**

* **`<ul>`**: Usada para listar itens sem ordem específica. Ex.: categorias de um blog.
* **`<ol>`**: Usada onde a ordem importa. Ex.: tutoriais e instruções.
* **`<dl>`**: Útil para apresentar termos e definições. Ex.: páginas de glossário ou FAQ técnico.

**Vantagens das listas:**

* Melhor organização visual.
* Mais acessíveis para leitores de tela.
* Facilitam a compreensão e leitura rápida.

---

### **3. A Expressão de Citações (Individual)**

**Elementos encontrados:**

* `<blockquote>` – Para citações em bloco. Ex.: trechos longos de falas ou textos de terceiros.
* `<q>` – Para citações curtas dentro do texto. Ex.: uma frase de alguém mencionada no parágrafo.

**Diferença semântica:**

* `<blockquote>`: Indica uma citação longa e destacada. Ganha indentação por padrão.
* `<q>`: Citação curta e embutida, geralmente com aspas.

**Análise de uso:**

Esses elementos ajudam a diferenciar o conteúdo autoral do citado. Exemplo: Em um artigo científico, o `<blockquote>` ajuda a mostrar que aquela parte é de outro autor, mantendo a ética e clareza.


