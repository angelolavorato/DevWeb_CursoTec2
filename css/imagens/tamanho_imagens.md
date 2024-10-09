# Manipulando o tamanho de Imagens com CSS

Manipular o tamanho de uma imagem usando HTML e CSS é um conceito importante e bastante utilizado no desenvolvimento web. A seguir, vou mostrar como você pode fazer isso através de exemplos práticos.

### 1. **Manipulação de Tamanho com HTML**

Na tag `<img>`, você pode definir o tamanho da imagem utilizando os atributos `width` e `height`.

**Exemplo HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Manipulação de Tamanho da Imagem</title>
</head>
<body>
    <h1>Manipulação de Tamanho com HTML</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" width="300" height="200">
</body>
</html>
```

Nesse exemplo, a imagem será renderizada com 300 pixels de largura e 200 pixels de altura.

### 2. **Manipulação de Tamanho com CSS**

Você também pode controlar o tamanho da imagem usando CSS. Isso é mais flexível e permite que você altere o estilo sem modificar o HTML.

**Exemplo HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Manipulação de Tamanho com CSS</title>
</head>
<body>
    <h1>Manipulação de Tamanho com CSS</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-tamanho">
</body>
</html>
```

**Exemplo CSS (`styles.css`):**

```css
.imagem-tamanho {
    width: 50%;  /* A imagem ocupará 50% da largura do seu contêiner pai */
    height: auto; /* A altura será ajustada automaticamente para manter a proporção */
}
```

Neste exemplo, a imagem será redimensionada para ocupar 50% da largura do seu contêiner pai, e a altura será ajustada automaticamente para manter a proporção.

### 3. **Manipulação de Tamanho com CSS com Valores Específicos**

Você também pode definir tamanhos fixos em pixels ou porcentagens diretamente no CSS.

**Exemplo HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Tamanhos Específicos com CSS</title>
</head>
<body>
    <h1>Tamanhos Específicos com CSS</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-especifica">
</body>
</html>
```

**Exemplo CSS (`styles.css`):**

```css
.imagem-especifica {
    width: 400px; /* Largura fixa de 400 pixels */
    height: 300px; /* Altura fixa de 300 pixels */
}
```

### 4. **Usando Propriedades CSS para Ajustes**

Você também pode usar as propriedades `max-width` e `max-height` para garantir que a imagem não ultrapasse um determinado tamanho, enquanto mantém a proporção.

**Exemplo HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Max Width e Max Height</title>
</head>
<body>
    <h1>Max Width e Max Height</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-max">
</body>
</html>
```

**Exemplo CSS (`styles.css`):**

```css
.imagem-max {
    max-width: 100%; /* A imagem ocupará no máximo 100% da largura do seu contêiner pai */
    max-height: 400px; /* A altura não excederá 400 pixels */
    height: auto; /* A altura será ajustada automaticamente para manter a proporção */
}
```

### 5. **Exemplo Completo de Manipulação de Tamanho de Imagem**

Aqui está um exemplo completo que combina todos os métodos:

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Manipulação de Tamanho de Imagem</title>
</head>
<body>
    <h1>Manipulação de Tamanho de Imagem</h1>
    
    <h2>Com HTML</h2>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" width="300" height="200">

    <h2>Com CSS (50% do contêiner)</h2>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-tamanho">

    <h2>Com CSS (Tamanho Específico)</h2>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-especifica">

    <h2>Com CSS (Max Width e Max Height)</h2>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-max">
</body>
</html>
```

**CSS (`styles.css`):**

```css
.imagem-tamanho {
    width: 50%;  /* A imagem ocupará 50% da largura do seu contêiner pai */
    height: auto; /* A altura será ajustada automaticamente para manter a proporção */
}

.imagem-especifica {
    width: 400px; /* Largura fixa de 400 pixels */
    height: 300px; /* Altura fixa de 300 pixels */
}

.imagem-max {
    max-width: 100%; /* A imagem ocupará no máximo 100% da largura do seu contêiner pai */
    max-height: 400px; /* A altura não excederá 400 pixels */
    height: auto; /* A altura será ajustada automaticamente para manter a proporção */
}
```

### Conclusão

Esses exemplos demonstram diferentes maneiras de manipular o tamanho de imagens usando HTML e CSS. Você pode escolher o método que melhor se adapta às suas necessidades, dependendo de como deseja que a imagem seja exibida em seu site. Lembre-se de sempre considerar a responsividade para garantir que suas imagens fiquem boas em diferentes tamanhos de tela!
