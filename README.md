<div align="center">

<img src="assets/svg/logo.svg" width="110" height="110" alt="Logo Clipboard"/>

# Clipboard

**Landing Page desenvolvida a partir do desafio do Frontend Mentor**

*Prática de arquitetura Sass, design tokens e layout responsivo com AXIS*

[![Finalidade Estudo](https://img.shields.io/badge/finalidade-estudo-e8e4de?style=flat-square&labelColor=orange&color=1c1b2e)](https://github.com/lucas16716/axis)&nbsp;
[![Licença](https://img.shields.io/badge/licença-MIT-e8e4de?style=flat-square&labelColor=ef4444&color=1c1b2e)](./LICENSE)&nbsp;
[![Status](https://img.shields.io/badge/status-concluído-e8e4de?style=flat-square&labelColor=10b981&color=1c1b2e)](https://lucas16716.github.io/lp-clipboard/)&nbsp;
[![Feito com AXIS](https://img.shields.io/badge/desenvolvido%20com-AXIS-e8e4de?style=flat-square&labelColor=3437e6&color=1c1b2e)](https://github.com/lucas16716/axis)


</div>

<p align="center">
  <a href="#projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#o-que-pratiquei">O que pratiquei</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#estrutura">Estrutura</a>
</p>

<h2 id="projeto">PROJETO</h2>

Solução para o desafio [Clipboard Landing Page](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9) do Frontend Mentor, desenvolvida como exercício prático de arquitetura Sass.

O objetivo não foi apenas replicar o layout — foi aplicar o [AXIS](https://github.com/lucas16716/axis), minha própria arquitetura Sass, em um projeto real, consolidando a disciplina de tokens de design, sistema de componentes e responsividade desktop-first.

🌐 [Acesse o projeto](https://lucas16716.github.io/lp-clipboard/)

<h2 id="o-que-pratiquei">O QUE PRATIQUEI</h2>

- 🏗️ **Arquitetura AXIS:** aplicação das cinco camadas (abstracts, base, layout, components, sections) em um projeto do zero
- 🎨 **Design tokens semânticos:** cores, tipografia, espaçamento e motion definidos por partial
- 📐 **Tipografia fluida:** escala Major Third (1,25) com `clamp()`, sem media queries para texto
- 📱 **Responsividade desktop-first:** `@include respond()` em todas as sections
- ♿ **Acessibilidade:** `aria-labelledby`, `aria-hidden`, `sr-only`, `prefers-reduced-motion`, `focus-visible`
- 🔍 **SEO e social:** Open Graph, Twitter Card e URL canônica configurados
- ⚡ **Otimização de produção:** PurgeCSS + CSS minificado via Live Sass Compiler (~73% de redução)

<h2 id="tecnologias">TECNOLOGIAS</h2>

| Tecnologia | Uso |
|---|---|
| HTML5 | Código semântico e acessível com meta tags de SEO e Open Graph |
| Sass (SCSS) | Arquitetura AXIS |
| CSS | Compilado e minificado via Live Sass Compiler |

<h2 id="estrutura">ESTRUTURA</h2>

```
lp-clipboard/
├── assets/
│   ├── favicon/             → favicon.png e apple-touch-icon.png
│   ├── fonts/               → ClashDisplay-Variable.ttf
│   ├── media/img/           → Backgrounds do hero e imagens de conteúdo
│   └── svg/                 → Logo e ícones
├── dist/
│   └── main.min.css         → CSS minificado e purgado (produção)
├── src/
│   ├── css/
│   │   └── main.css         → CSS compilado (desenvolvimento)
│   └── sass/
│       ├── abstracts/       → Tokens, funções e mixins (AXIS)
│       ├── base/            → Reset, tipografia, global e utilitários (AXIS)
│       ├── layout/          → Container e flex (AXIS)
│       ├── components/      → Button (AXIS)
│       ├── sections/        → header, features, access, supercharge,
│       │                      partners, cta, footer
│       └── main.scss        → Ponto de entrada único
└── index.html
```

<h2>LICENÇA</h2>

O código deste projeto está licenciado sob a licença MIT — veja o arquivo [LICENSE](./LICENSE).  
O design original pertence ao [Frontend Mentor](https://www.frontendmentor.io) e está sujeito aos [termos de uso](https://www.frontendmentor.io/terms) da plataforma.

<h2>AUTOR</h2>

Desenvolvido por [Lucas Couto](https://linkedin.com/in/lucas-coutoti).  
Veja meu trabalho em [Lucas Code](https://bio.site/lucascode).