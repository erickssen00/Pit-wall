# 🏎️ PIT WALL — GP de São Paulo

Landing page temática inspirada na Fórmula 1 para o Grande Prêmio de São Paulo (Interlagos). O projeto apresenta informações da pista, grid de pilotos, tabela de classificação e um formulário interativo para reserva de ingressos.

## 📋 Sobre o Projeto

Esta página foi desenvolvida como um projeto de estudo focado em estruturação semântica e estilização moderna sem o uso de frameworks externos. O layout simula uma central de eventos de automobilismo (*Pit Wall*), trazendo identidade visual esportiva com modo escuro (*dark mode*), paleta de cores personalizada por equipe e design responsivo para dispositivos móveis.

### Funcionalidades e Seções
* **Hero Section:** Apresentação do evento com dados técnicos do circuito (voltas, extensão e curvas) e recorte diagonal estilizado.
* **Grid de Pilotos:** Cards individuais para os pilotos com cores temáticas de suas respectivas escuderias (Ferrari, McLaren, Mercedes e Audi).
* **Classificação:** Tabela de pontuação com destaque para o líder e campos visuais de filtro por nome ou equipe.
* **Ingressos:** Tabela de preços por setor (Arquibancada A, Setor da Reta e Box VIP) acompanhada de formulário completo para reserva, envio de foto da torcida e recado para os pilotos.

---

## 🛠️ Tecnologias Utilizadas

* **HTML:** Estruturação semântica utilizando tags como `<header>`, `<nav>`, `<section>`, `<article>`, `<main>` e `<footer>`.
* **CSS:** Estilização avançada com:
  * **CSS Variables (`:root`):** Gerenciamento centralizado de cores e fontes.
  * **Flexbox & CSS Grid:** Construção de layouts alinhados, responsivos e grades de formulários/cards.
  * **Clip-path & Gradientes:** Efeitos visuais geométricos no banner principal e simulação da zebra (*kerb*) da pista.
  * **Media Queries:** Adaptação do layout para telas menores (tablets e smartphones).
* **Google Fonts:** Tipografia **Titillium Web** para reforçar a estética de velocidade e automobilismo.

---

## 📁 Estrutura de Arquivos

```text
├── index.html   # Estrutura principal da página
├── style.css    # Folha de estilos e regras de responsividade
└── img/         # Pasta de imagens (ex: pilotos.jpg usada no banner)
