# Site Portfolio — Ronaldo Reiser

Portfólio pessoal em página única, feito só com **HTML + CSS + JS puro** (sem build, sem dependências).

**No ar:** https://reiserzx.github.io/portfolio/

## Como rodar

Abra `index.html` direto no navegador, ou sirva a pasta com qualquer servidor estático:

```bash
npx serve .
# ou
python -m http.server
```

## Estrutura

- `index.html` — o site inteiro (marcação, estilos e scripts num único arquivo)
- `assets/` — mídia geral do site: `foto.png` (foto do bento) e `fonts/` (fontes extras)
- `projects/` — mídia de cada projeto:
  - `posters/` — pôsteres da seção de pastas
  - `sofazinho/` — fotos do carrossel, símbolo do sofá (`sofazinho.svg`) e fontes Redaction (`fonts/`)
  - `uqbar/` — logo e fotos do carrossel
- `refs/` — imagens de referência usadas no design

## O que tem na página

- Tela de carregamento com asterisco girando
- Hero com tipografia Arial, pares de palavras que trocam cor/itálico no hover
- Seção bento (introdução, foto, bio e link pro Behance)
- Pastas de posters em estilo arquivo: abas em alturas aleatórias, sobreposição, sombra, expande no hover e abre o pôster inteiro no clique
- Seção **Sofazinho Club**: logo com fontes Redaction (pesos misturados), símbolo do sofá em SVG que alterna rosa ↔ claro com efeito de pop, tags, descrição e carrossel infinito de fotos
- Seção **Uqbar**: logo entre parênteses que alternam azul claro ↔ rosa, tags, descrição e carrossel infinito de fotos
- Carrosséis com movimento automático que **pausam no hover e podem ser arrastados** pro lado (mouse e toque)
- Chat animado no fim da página (mensagens surgem "digitando" conforme você rola)
- Seletor de idioma **PT | EN**
- Cursor personalizado com `mix-blend-mode: difference`
- Layout responsivo (desktop, tablet e mobile)
