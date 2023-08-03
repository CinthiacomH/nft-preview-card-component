# Frontend Mentor - solução de componente de cartão de visualização NFT

Esta é uma solução para o [desafio do componente do cartão de visualização NFT no Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas. 

## Índice

- [Visão geral](#visão geral)
  - [O desafio](#o-desafio)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído com)
  - [O que aprendi](#o-que-aprendi)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Ver o layout ideal dependendo do tamanho da tela do dispositivo
- Ver os estados de foco para elementos interativos

### Links

- Viisualize no seu navegador: [https://lnkd.in/dxd7E9Xx](https://lnkd.in/dxd7E9Xx)
- Acesse o repositório: [https://github.com/CinthiacomH/nft-preview-card-component](https://github.com/CinthiacomH/nft-preview-card-component)

## Meu processo

### Construído com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- CSS Grid

### O que eu aprendi

Com esse desafio, aprendi a adicionar o active em uma imagem

```css
.nft-card .image-link::before{
    content: '';
    background-color: cyan;
    width: 100%;
    height: 100%;
    position: absolute;
    opacity: 0;
    transition: 0.3s ease-in-out;
}

.nft-card .image-link::after{
    content: '';
    background: url(../images/icon-view.svg) no-repeat center;
    position: absolute;
    width: 100%;
    height: 100%;
    opacity: 0;
    transition: 0.3s ease-in-out;
}
```

## Autor

- Linkedin - [cinthia-com-h](https://www.linkedin.com/in/cinthia-com-h/)
- Frontend Mentor - [@CinthiacomH](https://www.frontendmentor.io/profile/CinthiacomH)


## Agradecimentos

A conclusão desse projeto foi possível devido ao acompanhamento das aulas dos professores da @devemdobro.