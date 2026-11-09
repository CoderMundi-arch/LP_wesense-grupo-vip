# Wesense Perfumes | Festival 11/11 (Grupo VIP)

Landing page do Festival 11/11 da Wesense Perfumes, seguindo a arte oficial da campanha. Objetivo único: levar o visitante ao Grupo VIP no WhatsApp.

## Estrutura

```
wesense-festival-11-11/
├── index.html                      # página completa (site estático)
├── images/
│   ├── fundo-rosa-champagne.webp   # fundo rosé com bokeh e piso
│   ├── logo-wesense.webp           # logo dourada 3D
│   ├── festival-11-11.webp         # "11/11 Festival" 3D
│   ├── beneficio-1.webp            # parcelamento em até 11x sem juros
│   ├── beneficio-2.webp            # descontos de até 50%
│   ├── beneficio-3.webp            # enviamos para todo o Brasil
│   ├── card-11-11.webp             # selo "11/11 aproveite essa data"
│   ├── presente-wesense.webp       # caixa de presente com laço
│   ├── fita-esquerda.webp          # fita decorativa (canto superior esquerdo)
│   ├── fita-direita.webp           # fita decorativa (lateral direita)
│   └── fita-base.webp              # fita decorativa (base, atrás do selo e do presente)
└── nuvemshop/
    └── pagina-institucional.html   # trecho para colar no editor HTML da Nuvemshop
```

Todas as imagens, exceto o fundo, têm transparência. O fundo cobre a página inteira e fica ancorado embaixo, para o presente apoiar no piso.

## Rodar localmente

```
npx serve .
```

## Publicar

Qualquer hospedagem estática funciona (GitHub Pages, Vercel, Netlify). Não há build nem dependências.

## Usar na Nuvemshop (tema Recife)

1. Publique o repositório para que a pasta `images/` tenha URL pública.
2. Em `nuvemshop/pagina-institucional.html`, use **localizar e substituir** uma única vez:
   - localizar: `URL-DAS-IMAGENS`
   - substituir por: `https://SEU-USUARIO.github.io/wesense-festival-11-11/images` (sem barra no final)
3. No editor da página institucional, entre no modo código e cole o conteúdo inteiro.

## Copy (fonte: artes oficiais do Festival 11/11)

- É o momento perfeito para *se presentear!*
- Parcelamento em até 11x sem juros
- Descontos de até 50%
- Enviamos para todo o Brasil
- 11/11: aproveite essa data com condições especiais!

## Rastreamento

- Meta Pixel `2140503076558606` com `PageView` no carregamento.
- Evento `Lead` (content_name: Grupo VIP Festival 11/11) no clique dos dois botões.
- Se a loja já tem o mesmo pixel pela integração nativa da Nuvemshop, remova o bloco `Meta Pixel Code` do trecho da Nuvemshop para não contar visitas em dobro.

## Identidade

- Rosé `#F2DCD8`, dourado `#C2914E`, chocolate `#3A2214`, texto `#2B1A12`
- Tipografia: Montserrat, Great Vibes (script) e Open Sans
