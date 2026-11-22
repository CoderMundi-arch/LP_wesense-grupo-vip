# Wesense Perfumes | Black Friday (Grupo VIP)

Landing page da campanha Black Friday da Wesense Perfumes. Objetivo único: levar o visitante ao Grupo VIP no WhatsApp.

## Datas da campanha

Black Wesense: de 24 a 28 de novembro de 2026 (terça a sábado). A data aparece no selo do topo e acima do título da seção final.

## Estrutura

```
wesense-black-antecipada/
├── index.html                      # página completa (site estático)
├── images/
│   ├── wesense-hero-valentino-donna.webp
│   ├── wesense-colecao-valentino.webp
│   ├── wesense-1-million.webp
│   ├── wesense-ch-men.webp
│   └── logo-wesense-marca-dagua.webp
└── nuvemshop/
    └── pagina-institucional.html   # trecho para colar no editor HTML da Nuvemshop
```

## Rodar localmente

Abra o `index.html` no navegador ou sirva a pasta:

```
npx serve .
```

## Publicar

Qualquer hospedagem estática funciona (GitHub Pages, Vercel, Netlify). Não há build nem dependências.

## Usar na Nuvemshop (tema Recife)

1. Publique a pasta (por exemplo, no GitHub Pages) para que as imagens tenham URL pública.
2. Em `nuvemshop/pagina-institucional.html`, troque cada `COLE-AQUI-A-URL-DA-IMAGEM-<arquivo>.webp` pela URL pública correspondente, por exemplo `https://SEU-USUARIO.github.io/wesense-black-antecipada/images/wesense-1-million.webp`.
3. No editor da página institucional, entre no modo código e cole o conteúdo inteiro.

## Rastreamento

- Meta Pixel `2140503076558606` com `PageView` no carregamento.
- Evento `Lead` no clique dos dois botões do WhatsApp.
- Se a loja já tem o mesmo pixel pela integração nativa da Nuvemshop, remova o bloco `Meta Pixel Code` do trecho da Nuvemshop para não contar visitas em dobro.

## Identidade

- Preto `#0B0A09`, dourado Wesense `#C49E6D`, marfim `#F7F2EA`
- Tipografia: Montserrat (títulos) e Open Sans (textos)
