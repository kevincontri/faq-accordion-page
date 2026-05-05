# FAQ Accordion

Solução para o desafio [FAQ accordion](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz) do Frontend Mentor.
- [Link](https://kevincontri.github.io/faq-accordion-page/) para visualização da página!

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Abrir e fechar as respostas das perguntas ao clicar nelas
- Ver o ícone de cada pergunta mudar entre `+` e `-` conforme o accordion é aberto ou fechado
- Ver os estados de hover em todos os elementos interativos da página
- Visualizar o layout adaptado para diferentes tamanhos de tela

### Screenshot - Versão Desktop:

<br>

<img width="1657" height="820" alt="image" src="https://github.com/user-attachments/assets/4e1417d7-35f1-4f4e-980a-23c0094c59a9" />

### Screenshot - Versão Mobile:

<br>

<img width="533" height="928" alt="image" src="https://github.com/user-attachments/assets/300a33a9-60c1-40e4-8549-5397024d2792" />

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
