# kadoo-academy-demo-cpw

Demo interativa da Kadoo Academy na nova identidade visual, feita para apresentação em evento.

Página única em HTML/CSS/JS, sem build e sem dependências. Basta abrir `index.html` no navegador.

## Como abrir

| Link | O que faz |
|---|---|
| `index.html` | Navegação livre |
| `index.html?demo` | Roda a demo automática uma vez |
| `index.html?evento` | Modo evento: a demo automática roda e reinicia após 45 s sem uso |

Durante a demo automática, qualquer movimento do mouse, toque, rolagem ou tecla devolve o controle para quem está usando. A tecla **D** inicia a demo.

O Modo evento fica salvo no navegador. Para desligar, vá em Perfil → Modo evento.

## Estrutura

- `index.html`: a demo completa (telas, ícones e dados embutidos)
- `img/`: banners e capas dos editais em WebP
- `design-system/tokens.css`: tokens do design system (temas claro e escuro, tipografia, espaço, raio, movimento)
- `design-system/icones/`: 41 ícones SVG do design system
