# Site Portfolio — Ronaldo Reiser

Portfólio pessoal em página única, feito só com **HTML + CSS + JS puro** (sem build, sem dependências).

## Como rodar

Abra `portfolio.html` direto no navegador, ou sirva a pasta com qualquer servidor estático:

```bash
npx serve .
# ou
python -m http.server
```

## Estrutura

- `portfolio.html` — o site inteiro (marcação, estilos e scripts num único arquivo)
- `posters/` — imagens dos pôsteres da seção de pastas
- `ref 1.png`, `posters.png` — referências visuais usadas no design
- `Dreamer TM.otf` — fonte do projeto

## O que tem na página

- Tela de carregamento com asterisco girando
- Hero com tipografia Arial, pares de palavras que trocam cor/itálico no hover
- Seção bento (introdução, foto, bio e link pro Behance)
- Pastas de posters em estilo arquivo: abas em alturas aleatórias, sobreposição, sombra, expande no hover e abre o pôster inteiro no clique
- Chat animado no fim da página (mensagens surgem "digitando" conforme você rola)
- Seletor de idioma **PT | EN**
- Cursor personalizado com `mix-blend-mode: difference`
- Layout responsivo (desktop, tablet e mobile)
