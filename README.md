# 🐾 Café Miau

Um projeto front-end desenvolvido com o objetivo principal de estudar e aplicar os conceitos estruturais de **CSS Flexbox** e **CSS Grid Layout**. O site simula a _landing page_ de um adorável café temático de gatos, oferecendo uma interface limpa e organizada.

## Tecnologias Utilizadas

- **HTML5:** Estruturação do conteúdo da página.
- **CSS3:** Estilização e layout, com foco intensivo em:
  - **Flexbox:** Utilizado no menu de navegação para garantir espaçamento dinâmico, alinhamento e quebra de linha (`flex-wrap`). Também aplicado no botão "Ver Mais" e no alinhamento de conteúdos internos.
  - **CSS Grid:** Utilizado como espinha dorsal do layout principal (`grid-template-columns: 1fr 1fr;`) para dividir áreas de texto, imagem e a lista de vantagens.

## 📋 Estrutura e Aprendizados

O projeto serviu como laboratório para testar o comportamento de caixas e alinhamentos:

- **Navegação Flexível:** O menu (`.flex`) ajusta os links automaticamente utilizando `gap` e `justify-content: center`.
- **Grid Aninhado:** A seção de itens de vantagens (`.vantagensItens`) utiliza um grid interno (`grid-template-columns: auto 1fr;`) para alinhar perfeitamente os títulos e os parágrafos lado a lado.

## 💻 Como executar o projeto

1. Faça o clone deste repositório em sua máquina local:
   git clone https://github.com/Brunog21/FlexBox-Grid
