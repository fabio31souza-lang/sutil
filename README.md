# Sutil

Site de demonstração de uma clínica de harmonização facial (marca fictícia).

Página única em HTML, CSS e JavaScript puros, sem dependências. O hero é um vídeo
controlado pela rolagem: a gota cai e a água assenta conforme a pessoa desce a página.
Em celulares, tablets e com "reduzir movimento" ligado, o hero vira uma imagem estática.

## Ver localmente

```bash
python -m http.server 8765
```

Depois abra http://localhost:8765 numa janela larga do navegador.

## Arquivos

- `index.html`: o site inteiro
- `assets/hero-scrub.mp4`: vídeo do hero, codificado para rolagem
- `assets/hero-poster.jpg` e `assets/hero-ending.jpg`: primeiro e último quadro
- `assets/sala.jpg` e `assets/espelho.jpg`: imagens das seções
