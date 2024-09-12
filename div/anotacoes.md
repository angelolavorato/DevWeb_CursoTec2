## UTILIZANDO A TAG DIV

A tag `<div>` é uma das mais importantes e amplamente utilizadas em HTML. Sua principal função é servir como um contêiner genérico para agrupar outros elementos HTML, permitindo organizar o layout da página e aplicar estilos e scripts de forma mais eficiente.

### Função Principal da `<div>`

A `<div>` é um contêiner de bloco, ou seja, ocupa a largura total disponível e força uma quebra de linha antes e depois dela. Ela não tem estilo próprio, mas é essencial para estruturar e separar seções da página, especialmente quando combinada com CSS e JavaScript.

### Por que Usar `<div>`?

- **Agrupar Elementos**: A `<div>` agrupa elementos HTML que pertencem à mesma seção ou categoria de conteúdo.
- **Estilização**: Facilita a aplicação de estilos CSS a partes específicas da página.
- **Estrutura de Layout**: Usada em layouts complexos (como grid ou flexbox) para organizar visualmente o conteúdo da página.
- **Script**: Ajuda a organizar elementos que serão manipulados via JavaScript, tornando a página mais dinâmica.

### Exemplo de Uso de `<div>`

1. **Agrupamento de Elementos**
   Um uso comum da `<div>` é agrupar elementos relacionados em um bloco lógico.

   ```html
   <div>
     <h2>Título da Seção</h2>
     <p>Este é um parágrafo que pertence à mesma seção.</p>
     <p>Outro parágrafo na mesma seção.</p>
   </div>
   ```

2. **Aplicação de CSS**
   A `<div>` é frequentemente usada com classes ou IDs para aplicar estilos CSS. Isso permite modificar o visual e o layout de blocos inteiros de conteúdo.

   ```html
   <div class="container">
     <h2>Seção Estilizada</h2>
     <p>Conteúdo com estilização aplicada.</p>
   </div>
   ```

   E o CSS:

   ```css
   .container {
     border: 1px solid #000;
     padding: 20px;
     background-color: #f0f0f0;
   }
   ```

3. **Layouts em Flexbox ou Grid**
   A `<div>` é frequentemente usada como contêiner para criar layouts flexíveis com Flexbox ou Grid.

   **Exemplo com Flexbox**:

   ```html
   <div class="flex-container">
     <div class="item">Item 1</div>
     <div class="item">Item 2</div>
     <div class="item">Item 3</div>
   </div>
   ```

   E o CSS:

   ```css
   .flex-container {
     display: flex;
     justify-content: space-around;
   }

   .item {
     background-color: lightblue;
     padding: 10px;
     margin: 5px;
     border: 1px solid #000;
   }
   ```

4. **Divisões da Página**
   Para criar diferentes seções em uma página, como cabeçalhos, rodapés e áreas de conteúdo, a `<div>` é amplamente usada.

   ```html
   <div id="header">Cabeçalho da Página</div>
   <div id="content">Conteúdo Principal da Página</div>
   <div id="footer">Rodapé da Página</div>
   ```

   Com o CSS:

   ```css
   #header,
   #footer {
     background-color: #ccc;
     padding: 20px;
     text-align: center;
   }

   #content {
     margin: 20px;
   }
   ```

5. **Manipulação com JavaScript**
   A `<div>` também pode ser usada para elementos que serão manipulados com JavaScript, como exibir ou ocultar conteúdo dinamicamente.

   ```html
   <div id="info" style="display:none;">Esta é uma informação oculta.</div>
   <button onclick="mostrarInfo()">Mostrar Informações</button>

   <script>
     function mostrarInfo() {
       document.getElementById('info').style.display = 'block'
     }
   </script>
   ```

### Quando Evitar o Uso da `<div>`

Embora seja muito útil, o uso excessivo de `<div>`s sem necessidade, conhecido como **divitis**, pode tornar o código HTML desorganizado e mais difícil de entender. Utilize outras tags semânticas como `<header>`, `<footer>`, `<article>`, e `<section>`, quando aplicáveis.

### Conclusão

A tag `<div>` é essencial para estruturar o conteúdo de uma página HTML, mas deve ser usada com moderação e sabedoria. Ela ajuda a criar layouts complexos, agrupar elementos e organizar a aplicação de estilos e scripts.

Se você quiser explorar ainda mais, sugiro praticar com CSS e JavaScript para ver como a `<div>` pode ser usada para criar layouts e efeitos dinâmicos.

### EXERCÍCIOS

Aqui estão 5 exercícios práticos focados no uso da tag `<div>` em HTML:

### 1. Crie uma Estrutura Básica de Página com Divisões

- Crie uma página simples usando apenas `<div>`, dividindo-a em três seções:
  - Cabeçalho (header)
  - Conteúdo principal (main content)
  - Rodapé (footer)

### 2. Agrupe Textos em Seções Usando Divs

- Crie uma página onde você agrupa diferentes seções de texto utilizando `<div>`. As seções devem incluir:
  - Uma área para um título (h1)
  - Uma área para um subtítulo (h2)
  - Dois parágrafos de texto dentro de uma única `<div>`.

### 3. Crie uma Galeria de Imagens com Divs

- Crie uma galeria simples de três imagens. Cada imagem deve estar dentro de sua própria `<div>`, e cada `<div>` deve conter uma legenda em texto logo abaixo da imagem.

### 4. Crie um Layout de Três Colunas

- Use apenas `<div>` para criar um layout de três colunas. Cada coluna deve conter:
  - Um título
  - Um parágrafo
  - Uma lista simples (ul ou ol)

### 5. Divida a Página em Seções de Conteúdo e Sidebar

- Crie um layout onde a página tenha duas seções principais:
  - Uma área de conteúdo maior à esquerda
  - Uma barra lateral à direita
