# Claude Chat — Free via Puter.js

Chat con Claude Opus 4.6, Sonnet 4.6, y más modelos de Anthropic **gratis** via [Puter.js](https://developer.puter.com/). Sin API key, sin tarjeta de crédito.

## Límites reales (Puter.js Free)

Cada cuenta gratuita de Puter tiene un balance de **$0.25 USD**. En pruebas esto rindió aproximadamente:

| Modelo | Output tokens | Input tokens |
|---|---|---|
| Claude Sonnet 4.6 | ~15,400 | ~4,500 |


Eso equivale a **1-2 conversaciones largas** con Sonnet, o más si usas **Haiku 4.5** (mucho más barato). Puedes crear cuentas adicionales de Puter para obtener más créditos.

## Features

- **Múltiples modelos**: Claude Opus 4.6, Sonnet 4.6, Sonnet 4.5, Haiku 4.5
- **Chat con contexto**: Mantiene la conversación completa
- **Código con syntax highlighting** + botón de copiar
- **Markdown** renderizado
- **System prompt** configurable
- **Exportar** conversaciones como .md
- **Streaming** de respuestas en tiempo real

## Demo

👉 [Abrir Chat](https://ruii-code.github.io/claude-chat/)

## Uso local

Simplemente abre `index.html` en un servidor HTTP:

```bash
npx serve .
```

## Powered by

- [Puter.js](https://js.puter.com/v2/) — Free cloud OS API
- [Marked.js](https://marked.js.org/) — Markdown parser
- [Highlight.js](https://highlightjs.org/) — Syntax highlighting
