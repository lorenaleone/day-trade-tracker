# Trading Tracker Pro

> Landing page do produto **Trading Tracker Pro** — planilha de controle para day traders brasileiros.

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-00E676?style=flat-square&logo=github)](https://lorenaleone.github.io/day-trade-tracker/)

---

## 🔗 Página ao vivo

**[https://lorenaleone.github.io/day-trade-tracker/](https://lorenaleone.github.io/day-trade-tracker/)**

---

## Sobre o produto

O Trading Tracker Pro é uma planilha (Excel / Google Sheets) que transforma registros de operação em inteligência de trading:

- **Win Rate, Profit Factor, Payoff e Expectância** calculados automaticamente
- **Alerta anti-tilt** — aviso visual após sequência de perdas ou drawdown definido
- **Rastreio emocional** — correlacione estado mental com resultados
- **Abas por estratégia** — scalp, day trade e swing separados e comparáveis
- **Dashboard visual** — gráfico de equity, calendário de resultados e evolução semanal
- Funciona offline (Excel) e em nuvem (Google Sheets)

**Preço:** R$67 — pagamento único, acesso vitalício, atualizações inclusas.

---

## Stack

| Tecnologia | Uso |
|---|---|
| HTML5 + CSS3 | Estrutura e estilo da landing page |
| [Lucide Icons](https://lucide.dev) | Ícones via CDN |
| [Swiper.js](https://swiperjs.com) | Carrossel de depoimentos |
| [GSAP + ScrollTrigger](https://gsap.com) | Animações e contadores |
| [Google Fonts](https://fonts.google.com) | Space Grotesk + JetBrains Mono |

Sem frameworks, sem dependências locais — funciona 100% estático no GitHub Pages.

---

## Deploy

Hospedado via **GitHub Pages** a partir da branch `main`, pasta raiz.

Para atualizar a página:

```bash
git add index.html
git commit -m "update: <descrição da mudança>"
git push origin main
```

O GitHub Pages publica automaticamente em ~1 minuto.

---

## Como personalizar

### Trocar o link de checkout (Stripe)

Em `index.html`, localize o comentário e substitua `#checkout` pelo seu link do Stripe:

```html
<!-- Substitua o href abaixo pelo seu link de checkout do Stripe -->
<a href="https://buy.stripe.com/SEU_LINK_AQUI" class="cta" ...>
```

### Trocar o e-mail de contato

```html
<a href="mailto:suporte@tradingtrackerpro.com.br">Contato</a>
```

### Trocar os links de Termos e Privacidade

```html
<a href="/termos">Termos</a>
<a href="/privacidade">Privacidade</a>
```

---

## Licença

© 2026 Trading Tracker Pro. Todos os direitos reservados.
