# TripWay

Website fictício de uma agência de turismo especializada em viagens e experiências de aventura.

## Integrantes

- Rafael Silva de Jesus - RM574559
- Carlos Eduardo Alves Oliveira - RM575518
- Nicolas David Magalhaes - RM576054

## Descrição

Projeto desenvolvido para a disciplina de Front-End do curso de Análise e Desenvolvimento de Sistemas (ADS) da FIAP, com o objetivo de criar um site multipágina para uma empresa fictícia de viagens.

## Evolução do Projeto

No Checkpoint 1, o foco foi a estrutura HTML, páginas, navegação, formulário e colaboração com GitHub.

No Checkpoint 2, o projeto foi evoluído com CSS, identidade visual, layout com Flexbox e responsividade:

- Arquivo CSS externo (`css/style.css`) aplicado em todas as páginas
- Remoção dos estilos inline do CP1
- Reset básico com `box-sizing: border-box`
- Variáveis CSS no `:root` (cores, espaçamentos, sombras, transições)
- Header com menu horizontal em Flexbox e destaque da página atual (`.nav-link.active`)
- Hero na Home com texto, imagem e botão para os destinos
- Cards estilizados para destinos e pacotes, com `:hover` e `transition`
- Formulário reorganizado (labels, inputs com espaçamento, botão estilizado)
- Medidas relativas (`rem`, `%`, `vh`)
- Imagens renomeadas conforme a estrutura do projeto (`banner`, `praia`, `montanha`, `cidade`)
- Seção de serviços na página de Pacotes
- Responsividade com `@media` (1024px e 768px): desktop (cards lado a lado), tablet (duas colunas) e celular (uma coluna, menu adaptado, sem rolagem horizontal)

## Tecnologias Utilizadas

- HTML5
- CSS3
- Git
- GitHub
- Visual Studio Code

## Páginas

- Home
- Destinos
- Pacotes
- Contato

## Estrutura do projeto

```text
tripway/
├── index.html
├── pages/
│   ├── destinos.html
│   ├── pacotes.html
│   └── contato.html
├── css/
│   └── style.css
├── images/
│   ├── banner.jpg
│   ├── praia.jpg
│   ├── montanha.jpg
│   └── cidade.jpg
└── README.md
```
