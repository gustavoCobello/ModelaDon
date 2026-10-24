<!--
  IMAGEM: LOGO / BANNER PRINCIPAL
  Sugestão: docs/img/banner.png (1280x400). Para usar, troque este comentário por:
  <p align="center"><img src="docs/img/banner.png" alt="Modela.Don" width="100%"></p>
-->

<h1 align="center">Modela<span>.</span>Don</h1>

<p align="center"><b>Loja virtual de impressões 3D com visualizador 3D, checkout rápido e painel administrativo com autenticação em duas etapas.</b></p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-18-6D28D9?style=flat-square">
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-CSS-6D28D9?style=flat-square">
  <img alt="Three.js" src="https://img.shields.io/badge/Three.js-3D-6D28D9?style=flat-square">
  <img alt="Vercel" src="https://img.shields.io/badge/Deploy-Vercel-18181B?style=flat-square">
  <img alt="Status" src="https://img.shields.io/badge/status-demonstrativo-4C1D95?style=flat-square">
</p>

<!--
  IMAGEM: GIF/PRINT DA LOJA EM AÇÃO (mobile + desktop lado a lado)
  Sugestão: docs/img/hero.png ou docs/img/demo.gif (1200x700)
-->

---

## Sobre

A **Modela.Don** é uma loja pensada para pequenos negócios de impressão 3D: vitrine mobile-first, carrinho com frete simulado, favoritos, visualização 3D dos produtos em várias cores de filamento e um painel administrativo (apenas na versão privada). Roda 100% no navegador, sem servidor próprio.

> Este repositório é **demonstrativo**: traz só a vitrine pública, com produtos de exemplo.

## Telas

<!--
  IMAGENS DAS TELAS (use uma tabela de 3 colunas quando adicionar):
  | Vitrine | Detalhes do produto | Visualizador 3D |
  | docs/img/home.png | docs/img/produto.png | docs/img/viewer-3d.png |
  Outras ideias: carrinho (docs/img/carrinho.png), painel admin (docs/img/admin.png),
  login com autenticador (docs/img/login.png), preloader (docs/img/preloader.png).
-->

*(capturas de tela em breve)*

## Funcionalidades

- **Vitrine mobile-first** com busca, categorias, favoritos e navegação inferior flutuante
- **Visualizador 3D** (STL e OBJ): gira, dá zoom e troca a cor do filamento em tempo real
- **Carrinho em gaveta** com frete simulado por UF e frete grátis acima de R$ 199
- **Checkout simulado** com validação de CPF e endereço, pedidos salvos no navegador
- **Painel administrativo** (produtos, pedidos, fotos, modelos 3D e login com autenticador): disponível apenas na versão privada de produção
- **Movimento fluido** em todas as transições, com respeito a *prefers-reduced-motion*

## Versão demonstrativa

Aqui está a **vitrine pública** da loja (produtos de exemplo, carrinho, favoritos, checkout simulado e visualizador 3D). O painel administrativo, a publicação de catálogo e o sistema de autenticação **não fazem parte deste repositório** e rodam apenas na versão privada de produção.

## Como rodar

Não há build: abra o `index.html` no navegador ou sirva a pasta com qualquer servidor estático (por exemplo, `npx serve`).

## Roadmap

- [ ] Seleção de cor do filamento no pedido
- [ ] Página de detalhe com galeria de fotos
- [ ] Integração real de pagamento e cálculo de frete
- [ ] Backend dedicado quando o volume crescer

<!--
  IMAGEM: RODAPÉ / ASSINATURA (opcional)
  Sugestão: docs/img/footer.png (1280x120)
-->

<p align="center"><sub>Feito camada por camada · Modela.Don</sub></p>
