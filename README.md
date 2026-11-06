# 🚀 Desafio 01: Minha Primeira Landing Page com HTML e CSS

Este é o meu projeto do **primeiro desafio da Trilha de CSS da DIO**. A proposta era construir uma Landing Page do zero, colocando em prática os fundamentos do CSS, as propriedades básicas de estilização e as unidades de medida relativas e absolutas que vi ao longo da trilha.

> 🎉 **Parabéns à Michele Ambrosio**, criadora do desafio original, pela proposta tão bem pensada para quem está começando! Veja os créditos no final.

---

## 🎯 Como o desafio funcionava

1. Fiz um **fork** do repositório do desafio e comecei a mexer no projeto.
2. A pasta principal já trazia as **imagens** e um `index.html` com a **estrutura pronta**. Faltava toda a parte de estilização.
3. Também era minha responsabilidade **ligar o HTML às folhas de estilo**. Sem isso, nada do CSS apareceria na página.
4. Para me guiar, usei o **protótipo no Figma** que o desafio disponibilizava.



---

## ✅ O que eu fiz

- **Conectei o HTML ao CSS** com a tag `<link>` dentro do `<head>`.
- **Criei um `reset.css`** para tirar as margens e os espaçamentos padrão do navegador e importei ele no `style.css`.
- **Estilizei todas as seções** da página:
  - o banner;
  - a seção de módulos;
  - a faixa "Transforme o mundo com a gente";
  - a seção de desafios profissionais;
  - o rodapé.
- **Apliquei texto em gradiente** no título.
- **Usei unidades relativas e absolutas**, conforme cada situação.
- **Deixei a página responsiva** com media queries para tablets e celulares.
- **Adicionei detalhes de interação**: efeito de hover nos botões e nos cards dos módulos, e uma animação de entrada no banner.

---

## 🔍 Os conceitos, explicados de forma simples

### Ligando o HTML ao CSS
O `index.html` só vira uma página bonita se avisarmos ao navegador onde estão os arquivos de estilo. Isso é feito com a tag `<link>` no `<head>`. Se ela estiver com o caminho errado, o CSS simplesmente não aparece.

### O `reset.css`
Cada navegador vem com margens e espaçamentos próprios. O reset **zera tudo isso** para a página ficar igual em qualquer lugar, e o `style.css` começa a partir de uma base limpa.

### Texto em gradiente
O efeito de cores no título usa `background-clip: text`: o gradiente fica no fundo do elemento e o CSS "recorta" esse fundo no formato das letras. Usei também `-webkit-background-clip: text`, que é necessário para funcionar em alguns navegadores.

### Unidades de medida

| Unidade | Tipo | Como funciona |
|---|---|---|
| `px` | Absoluta | Tamanho fixo, que não muda com a tela. |
| `rem` | Relativa | Baseada no tamanho da fonte raiz da página. |
| `%` | Relativa | Baseada no tamanho do elemento pai. |
| `vh` | Relativa | Cada 1vh equivale a 1% da altura da tela. |
| `clamp()` | Relativa | Define um tamanho que se ajusta, mas sempre entre um mínimo e um máximo. |

### Responsividade com media queries
As media queries permitem dizer: "a partir deste tamanho de tela, mude o layout". Com elas, a página se adapta a **tablets** e **celulares**.

### Interação e animação
- **Hover**: quando o mouse passa por cima dos botões e dos cards dos módulos, eles reagem visualmente.
- **Animação de entrada**: o banner aparece com um movimento suave quando a página carrega.

---

## 🛠️ Tecnologias

| Tecnologia | Para que serve neste projeto |
|---|---|
| **HTML5** | Estrutura da página (já vinha pronta no desafio). |
| **CSS3** | Todo o visual: cores, layout, responsividade e animações. |

Sem biblioteca e sem framework: só HTML e CSS. 💪

---

## 📁 Estrutura do projeto

```
├── index.html
├── README.md
└── assets
    ├── css
    │   ├── reset.css          # zera os estilos padrão do navegador
    │   └── style.css          # estilo da página
    └── images
        ├── banner.png
        ├── dio-logo.png
        ├── logo.png
        ├── professional-challenges.png
        └── woman-code.png
```

---

## ▶️ Como ver o projeto

1. Clone este repositório ou baixe os arquivos.
2. Abra o `index.html` no navegador.

> 💡 **Dica:** se o CSS não aparecer, confira se o caminho da tag `<link>` no `index.html` está igual ao da estrutura acima.

---

## 📚 O que aprendi

Foi a **primeira vez** que montei uma página inteira só com HTML e CSS. Aprendi principalmente a:

- organizar o CSS em arquivos;
- ligar o estilo ao HTML;
- trabalhar com gradientes em textos;
- escolher a unidade de medida certa;
- deixar o layout se adaptar a telas diferentes.

---

## 🙌 Créditos

Este desafio foi criado pela **Michele Ambrosio**, para a **Trilha de CSS da [DIO](https://www.dio.me/)**.

Muito obrigado pela proposta e pelo material de apoio, incluindo o protótipo no Figma! 👏

---

## 👨‍💻 Autor

 por **Vinícius Cruz dos Santos**

[![GitHub](https://img.shields.io/badge/GitHub-Viniciuscruzdossantos-181717?logo=github)](https://github.com/Viniciuscruzdossantos)
