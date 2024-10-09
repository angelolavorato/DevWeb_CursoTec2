# TRABALHADO COM IMAGENS EM CSS

### 1. Inserção de Imagens com HTML

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Inserção de Imagens</title>
</head>
<body>
    <h1>Exemplo de Imagem</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" width="300" height="200">
</body>
</html>
```

### 2. Responsividade de Imagens

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Responsividade de Imagens</title>
</head>
<body>
    <h1>Imagem Responsiva</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-responsiva">
</body>
</html>
```

**CSS (`styles.css`):**

```css
.imagem-responsiva {
    max-width: 100%;
    height: auto;
}
```

### 3. Estilização de Imagens com CSS

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Estilização de Imagens</title>
</head>
<body>
    <h1>Estilização de Imagens</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-estilizada">
</body>
</html>
```

**CSS (`styles.css`):**

```css
.imagem-estilizada {
    border: 5px solid black;
    box-shadow: 10px 10px 5px grey;
    border-radius: 15px;
}
```

### 4. Imagens como Fundos

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Imagens como Fundos</title>
</head>
<body>
    <h1>Imagem de Fundo</h1>
    <div class="fundo-imagem">
        Texto sobre a imagem de fundo
    </div>
</body>
</html>
```

**CSS (`styles.css`):**

```css
.fundo-imagem {
    background-image: url('caminho-da-imagem.jpg');
    background-size: cover;
    background-position: center;
    width: 100%;
    height: 300px;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
}
```

### 5. Sprites de Imagem

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Sprites de Imagem</title>
</head>
<body>
    <h1>Sprite de Imagem</h1>
    <div class="sprite"></div>
</body>
</html>
```

**CSS (`styles.css`):**

```css
.sprite {
    width: 50px; /* Largura do ícone */
    height: 50px; /* Altura do ícone */
    background-image: url('caminho-do-sprite.png');
    background-position: -50px 0; /* Posição do ícone no sprite */
    background-size: 200px 50px; /* Tamanho total do sprite */
}
```

### 6. SVG (Scalable Vector Graphics)

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>SVG</title>
</head>
<body>
    <h1>Imagem SVG</h1>
    <svg width="100" height="100" class="svg-exemplo">
        <circle cx="50" cy="50" r="40" fill="blue" />
    </svg>
</body>
</html>
```

**CSS (`styles.css`):**

```css
.svg-exemplo {
    border: 2px solid black; /* Borda ao redor do SVG */
}
```

### 7. Manipulação de Imagens com Filtros CSS

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Filtros CSS</title>
</head>
<body>
    <h1>Filtros CSS</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" class="imagem-filtro">
</body>
</html>
```

**CSS (`styles.css`):**

```css
.imagem-filtro {
    filter: grayscale(100%); /* Converte a imagem para tons de cinza */
}
```

### 8. Lazy Loading de Imagens

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Lazy Loading</title>
</head>
<body>
    <h1>Lazy Loading de Imagens</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem" loading="lazy">
</body>
</html>
```

### 9. Imagens Decorativas vs. Imagens Informativas

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Imagens Decorativas e Informativas</title>
</head>
<body>
    <h1>Exemplo de Imagens Decorativas e Informativas</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição da imagem informativa">
    <img src="caminho-da-imagem-decorativa.jpg" alt="" class="decorativa">
</body>
</html>
```

**CSS (`styles.css`):**

```css
.decorativa {
    width: 100px; /* Largura para a imagem decorativa */
    height: auto;
}
```

### 10. Acessibilidade e SEO

**HTML (`index.html`):**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Acessibilidade e SEO</title>
</head>
<body>
    <h1>Acessibilidade e SEO</h1>
    <img src="caminho-da-imagem.jpg" alt="Descrição detalhada da imagem para SEO e acessibilidade">
</body>
</html>
```
