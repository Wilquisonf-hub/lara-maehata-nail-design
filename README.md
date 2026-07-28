# Lara Maehata Nail Design — Website

Site institucional (one-page) do **Lara Maehata Nail Design** — nail design autoral em Elias Fausto (SP).

**Assinatura:** _Unhas que realçam sua essência._

## ✨ Sobre

Página única, responsiva e leve (HTML + CSS + um pouco de JS, sem framework e sem build).
Construída sobre o **Brand Asset Kit** oficial da marca:

- Tipografia: **Bodoni Moda** (títulos) + **Manrope** (corpo/interface) — via Google Fonts
- Cores: Ivory `#FBF8F2`, Champagne `#F1E4CF`, Espresso `#3A2B24`, Charcoal `#1C1917`, Gold `#B88A2A`
- Logos, favicons e imagem de compartilhamento (Open Graph) originais do kit

## 🚀 Publicar na Vercel

1. Acesse [vercel.com](https://vercel.com) e entre com o GitHub.
2. **Add New → Project** e importe o repositório `lara-maehata-nail-design`.
3. Framework Preset: **Other** (site estático). Não há build — a Vercel já serve o `index.html`.
4. Clique em **Deploy**. Em segundos você recebe uma URL `https://...vercel.app`.

> Depois é só ligar seu domínio próprio (ex.: `laramaehata.com.br`) em **Settings → Domains**, se quiser.

Para ver localmente, basta abrir o `index.html` no navegador.

## 📝 O que personalizar

| Onde | O quê |
|------|-------|
| Portfólio | Trocar as ilustrações por **fotos reais** dos seus trabalhos (veja o comentário no `index.html`). |
| Sobre | Trocar o monograma por uma **foto sua**. |
| Depoimentos | Substituir os textos de **exemplo** por depoimentos reais das clientes. |
| Contato | WhatsApp, Instagram e cidade já configurados. |

**Trocar uma ilustração por foto:** no `index.html`, troque
`<svg class="nail" ...>...</svg>` por `<img class="nail" src="assets/sua-foto.jpg" alt="...">`
(coloque a imagem dentro da pasta `assets/`).

## 📂 Estrutura

```
index.html          → o site inteiro (conteúdo + estilo + scripts)
assets/             → logos, ícones, padrões, sparkle e og.jpg
favicon.*, site.webmanifest, apple-touch-icon.png, android-chrome-*.png
```

## 📞 Contato

- WhatsApp: +55 19 99489-0873
- Instagram: [@laraaika_nails](https://www.instagram.com/laraaika_nails/)
- Elias Fausto — SP (atendimento com hora marcada)

---
Identidade visual: **Lara Maehata Nail Design — Brand Asset Kit**.
