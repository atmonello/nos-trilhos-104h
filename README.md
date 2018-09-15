# Nos Trilhos da Programação - LAB 104H
## André Monello

___

## Sábado

- Introdução de instrutores/ninjas
- Conhecimento da sala
  - Contato com programação e/ou desenvolvimento web
- Funcionamento da Web
  - Redes e endereços IP
    - Transparência da internet *contrária* de transparência fora
  - Servidores x Clientes
  - Protocolos
  - HTTP(S)
    - HTML - estrutura
    - CSS - estilo
    - JavaScript - interação
- Front End x Back End
  - Cliente x Servidor
  - Início pelo HTML 
  - Requisições quando referencia arquivos externos *eg* CSS, JS...
  - Exemplo: abrir home de algum site com a aba Network aberta no DevTools *Ideia - interagir com a sala para decidir o site*
  ___
### HTML
  - Linguagem de marcação por tags
    - Convenção de nomenclatura por *index.html*
    - Snippet do VS Code: `html:5`
  - Tag: elemento da página
  - `<nome-da-tag></nome-da-tag>`
  - Nesse momento usar o snippet para mostrar funcionamento do HTML
  - Com o arquivo HTML aberto, edita-lo com alguns exemplos de tags comuns para ilustrar, *eg*, `<div>`, `<button>`, `<h1>`, `<p>`, `<ul>`, `<ol>`, `<li>`, `<span>`
  - Citar outras tags comuns: `<a>, <script>, <html>, <head>, <body>, <img>`
  - Mencionar o [w3Schools](https://www.w3schools.com/) e [MDN](https://developer.mozilla.org/pt-BR/)
  - Indentação
  ```
  <html>
    <head>
      <title>Indentação bonitinha!</title>
    </head>
    <body>
      <div>
        <h1>Esse é o título da página</h1>
        <p>Aqui é o primeiro parágrafo.</p>
        <p>Aqui é o segundo parágrafo.</p>
      </div>
    </body>
  </html>

  <html>
  <head>
  <title>Indentação bonitinha!</title>
  </head>
  <body>
  <div>
  <h1>Esse é o título da página</h1>
  <p>Aqui é o primeiro parágrafo.</p>
  <p>Aqui é o segundo parágrafo.</p>
  </div>
  </body>
  </html>
  ```
  - *Self-closing tags* e tags que não são definidas pelo conteúdo
    - Exemplo: tags `<a>`, `<img>` e `<input>` 
    - `<a href="http://mastertech.tech">Clique para acessar a página da Mastertech!</a>`
    - `<img src="https://yt3.ggpht.com/a-/AJLlDp1GFeGIEh5saQLhGFC5l5fjAMuUbdDaJn29Fg=s900-mo-c-c0xffffffff-rj-k-no" alt="logo da mastertech">`
    - `<input type="text" placeholder="Digite algo aqui">`
  - Abrir [pudim](www.pudim.com.br) e mostrar as tags no DevTools
  ___

  ### CSS I
  - HTML apenas cria os elementos na página, CSS formata e posiciona
  - Estilização era feita diretamente nos elementos HTML, tornando-se muito complexo
  - Criar arquivo CSS na mesma pasta do `index.html`
  - Referenciar o arquivo dentro da tag `<head>` com uma tag `<link>`
    - `<link rel="stylesheet" href="styles.css">`
    - O arquivo pode estar em uma subpasta **dentro** da pasta do index, mas vamos deixar na mesma pasta nesse momento

    #### Estrutura do CSS

    - Arquivos CSS são organizados em *blocos*, definidos por *seletores*:
    ```
    seletor {
      propriedade-1: valor-1;
      propriedade-2: valor-2;
    }
    ```
    - O seletor define quais elementos HTML recebem as propriedades definidas naquele bloco.
    - As propriedades definem a estilização em si.
    - Mostrar exemplo
    - Seletores de tags x Seletores de classe x Seletores de id
    - Classe é um conjunto de elementos HTML que compartilha o mesmo estilo. Um elemento pode ter múltiplas classes.
    - Id identifica somente um elemento HTML e o elemento também só pode ter um id
    - Unidades de medida: px, %, vw, vh, rem
    - Mostrar exemplo
    - Box Model
      - Conteúdo
      - Padding
      - Border
      - Margin

  ### CSS II
  - Display
    - Inline
    - Block
    - None
    - *Flex
      - justify-content
        - space-around: distribui igualmente com metade dos espaços iguais dos lados
        - space-between: distribui pelo container todo
        - space-evenly: distribui pelo container com espaços dos lados
      - align-items
      - flex-direction
  - Position
    - Static
    - Relative
    - Absolute
    - Fixed
