# Card-QR-COD-FRONTMENTOR

# Frontend Mentor - QR Code Component Solution

Esta é uma solução para o desafio do **[QR code component no Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iA_BxValidation)**. Os desafios do Frontend Mentor ajudam a aprimorar competências práticas de codificação através do desenvolvimento de projetos realistas.

---

## Índice

- [Visão Geral](#visão-geral)
  - [O Desafio](#o-desafio)
  - [Links](#links)
- [O Meu Processo](#o-meu-processo)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [O Que Aprendi](#o-que-aprendi)
- [Autor](#autor)

---

## Visão Geral

### O Desafio

O objetivo deste desafio é construir um componente de cartão de QR Code e aproximá-lo ao máximo do design proposto, garantindo a sua visualização correta em diferentes tamanhos de ecrã.

### Links

- **URL da Solução (GitHub):** [Ver Repositório](https://github.com/RafaelAraujoSantana/Card-QR-COD-FRONTMENTOR)
- **URL do Site Online (Vercel):** [https://card-qr-cod-frontmentor.vercel.app/](https://card-qr-cod-frontmentor.vercel.app/)

---

## O Meu Processo

### Tecnologias Utilizadas

- **HTML5** semântico
- **CSS3** (Propriedades customizadas / Variáveis CSS)
- **Flexbox** para alinhamento e centralização
- Design responsivo utilizando **Media Queries** e unidades relativas (`dvh`, `%`)
- Importação de tipografia externa via **Google Fonts** (`Outfit`)

### O Que Aprendi

Neste projeto do Frontend Mentor, foquei-me na organização do código CSS utilizando variáveis no `:root` para padronizar as cores HSL e a fonte do projeto:

```css
:root {
    --background-page: hsl(212, 45%, 89%);
    --background-card: hsl(0, 0%, 100%);
    --first-sentence: hsl(218, 44%, 22%);
    --second-sentence: hsl(216, 15%, 48%);
    --font-sentence: "Outfit", sans-serif;
}
