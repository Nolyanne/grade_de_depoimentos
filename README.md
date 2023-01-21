# grade_de_depoimentos

## Visão geral

### O desafio

Esta página é um desafio do FrontEnd Mentor.

Os usuários devem ser capazes de:

- Ver o layout ideal para o site, dependendo do tamanho da tela do dispositivo

### Captura de tela

![](./grade_de_depoimentos.jpg)


### Links

- URL da solução: [Abrir página do projeto](https://regal-cat-2206bd.netlify.app)

## Meu processo

### Construído com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- Grade CSS

### O que eu aprendi

O que me desafiou a implementar esta página foi a possibilidade de um novo aprendizado: o CSS grid. Também foi uma forma de treinar meu olho para trazer uma solução o mais próximo possível do design.


Para ver como você pode adicionar trechos de código, veja abaixo:


```css
.container{

    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    column-gap: 20px;
    row-gap: 20px;
    align-content: center;
    font-size: 13px;
    font-family: 'Barlow Semi Condensed';
    margin-left: 10%;    
    margin-right: 10%;
    margin-top: 5%;
}

.dep1{
    background-color: hsl(263, 55%, 52%);
    border-radius: 10px;
    grid-column-start: 1;
    grid-column-end: 3;
    grid-column: 1/3;


}

.dep3{
    background-color: hsl(0, 0%, 100%);  
    border-radius: 10px;   
    grid-area: 1 / 4 / span 2 / span 4;
}
```




### Desenvolvimento contínuo

Desejo continuar evoluindo meus conhecimentos em HTML e CSS, até que me sinta totalmente confortável com esses recursos. Também desejo refinar e aperfeiçoar projetos anteriores.


### Recursos úteis

- [Netlify](https://www.netlify.com) - Isso me ajudou para executar meu projeto. 
- [CSS-TRICKS](https://css-tricks.com/snippets/css/complete-guide-grid/) - Este é um site incrível que me ajudou a entender CSS Grid. Recomendo a todos que ainda estão aprendendo esse conceito.


## Autor

- Frontend Mentor - [@Nolyanne](https://www.frontendmentor.io/profile/Nolyanne)



## Agradecimentos

Agradeço ao colega Fabrício Dourado, da comunidade CODE, pelo feedback em meu projeto anterior e por abrir meu horizonte sobre CSS. E também ao Felipe Cunha por me ajudar nos alinhamentos em CSS.
