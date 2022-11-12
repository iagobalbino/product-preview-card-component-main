# Frontend Mentor - Product preview card component solution

Esta é a solução para o [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Conteúdo

- [Overview](#overview)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que aprendi](#o-que-aprendi)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)

## Overview

### O desafio

Os usuários devem ser capazes de:

- Ver o layout ideal dependendo do tamanho da tela do dispositivo
- Ver o hover e o focus nos elementos interativos

### Screenshot

![](./screenshot.jpg)

### Links

- URL da solução: [Add solution URL here](https://your-solution-url.com)
- Meu Site: [https://iagobalbino.com.br/](https://iagobalbino.com.br/)

## Meu processo

### Construído com

- HTML5 semântico
- CSS
- Flexbox

### O que aprendi

Neste pequeno projeto revi novamente conceitos básicos do desenvolvimento front-end, como conceito de classe no HTML e no CSS, e dos media-queries para redimesionamento do layout.

```html
        <div class="prices">
          <p class="main-price">$149.99</p>
          <p class="old-price">$169.99</p>
        </div>
```
```css
.prices {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}

.main-price,
.old-price {
  display: inline;
}
```

### Recursos úteis

- [Guia Origamid Flex Box](https://origamid.com/projetos/flexbox-guia-completo/) - Me ajudou a lembrar a sintaxe e as funcionalidades do flex box

## Autor

- Website - [Iago Balbino](https://iagobalbino.com.br/)
- Frontend Mentor - [@iagobalbino](https://www.frontendmentor.io/profile/iagobalbino)