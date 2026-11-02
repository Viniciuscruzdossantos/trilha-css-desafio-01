Desafio 01: Minha primeira Landing Page com HTML e CSS

Este é o meu projeto do primeiro desafio da Trilha de CSS da DIO. A proposta era construir uma Landing Page do zero, colocando em prática os fundamentos do CSS, as propriedades básicas de estilização e as unidades de medida relativas e absolutas que vi ao longo da trilha.

O desafio original foi criado pela Michele Ambrosio. Você pode ver o resultado final de referência aqui.

Como o desafio funcionava

Eu fiz um fork do repositório e comecei a mexer no projeto. A pasta principal já trazia as imagens e um index.html com a estrutura pronta, e faltava toda a parte de estilização. Também era minha responsabilidade ligar o HTML às folhas de estilo, senão nada do CSS apareceria na página.

Para me guiar, usei o protótipo no Figma que o desafio disponibilizava.

O que eu fiz
Conectei o HTML ao CSS com a tag <link rel="stylesheet"> no <head>.
Criei um reset.css para tirar as margens e os espaçamentos padrão do navegador e importei ele no style.css.
Estilizei o banner, a seção de módulos, a faixa "Transforme o mundo com a gente", a seção de desafios profissionais e o rodapé.
Apliquei o texto em gradiente no título com background-clip: text e também -webkit-background-clip: text, que é necessário para funcionar em alguns navegadores.
Usei unidades relativas (rem, %, vh, clamp()) e absolutas (px) conforme cada situação.
Deixei a página responsiva com media queries para tablets e celulares.
Adicionei detalhes de interação, como o efeito de hover nos botões e nos cards dos módulos e uma animação de entrada no banner.
Estrutura do projeto
├── index.html
├── README.md
└── assets/
    ├── css/
    │   ├── reset.css
    │   └── style.css
    └── images/
        ├── banner.png
        ├── dio-logo.png
        ├── logo.png
        ├── professional-challenges.png
        └── woman-code.png
Como ver o projeto
Clone este repositório ou baixe os arquivos.
Abra o index.html no navegador.

Se o CSS não aparecer, confira se o caminho do <link> no index.html está igual ao da estrutura acima.

Tecnologias
HTML5
CSS3
O que aprendi

Foi a primeira vez que montei uma página inteira só com HTML e CSS, sem biblioteca nem framework. Aprendi principalmente a organizar o CSS em arquivos, a ligar o estilo ao HTML, a trabalhar com gradientes em textos, a escolher a unidade de medida certa e a deixar o layout se adaptar a telas diferentes.

Autor

Feito por Vinícius Cruz dos Santos,
