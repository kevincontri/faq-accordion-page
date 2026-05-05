# FAQ Accordion

Solução para o desafio [FAQ accordion](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz) do Frontend Mentor.

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Abrir e fechar as respostas das perguntas ao clicar nelas
- Ver o ícone de cada pergunta mudar entre `+` e `-` conforme o accordion é aberto ou fechado
- Ver os estados de hover em todos os elementos interativos da página
- Visualizar o layout adaptado para diferentes tamanhos de tela

### Screenshot

![Preview do projeto](./preview.jpg)

## Minha solução

### Tecnologias utilizadas

- HTML5 semântico
- CSS3 (variáveis CSS, Flexbox, media queries, transições)
- JavaScript puro (DOM manipulation)
- Fonte [Work Sans](https://fonts.google.com/specimen/Work+Sans) via Google Fonts

### Como funciona

O accordion é implementado com JavaScript puro, sem dependências externas. Ao clicar em uma pergunta, a classe `active` é alternada no botão e a altura máxima do elemento de resposta é ajustada dinamicamente via `scrollHeight`, permitindo uma transição CSS suave de abertura e fechamento.

## Autor

- GitHub — [@kevincontri](https://github.com/kevincontri)
- Frontend Mentor — [@kevincontri](https://www.frontendmentor.io/profile/kevincontri)

## Agradecimentos

Desafio proposto pela [Frontend Mentor](https://www.frontendmentor.io).
