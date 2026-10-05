# EdsonKaizen — site pessoal

Versão construída a partir do layout visual aprovado.

## Testar localmente
```bash
python3 -m http.server 8000
```
Abra `http://localhost:8000`.

## Publicar no GitHub
```bash
git add .
git commit -m "Atualiza EdsonKaizen conforme novo layout"
git push
```

## Estrutura
- `index.html`
- `assets/css/style.css`
- `assets/js/main.js`
- `assets/images/edson-hero.png`
- `assets/images/edson-original.jpg`
- `assets/images/referencia-layout.png`

A imagem `referencia-layout.png` é apenas referência visual e não é carregada pela página.

## Desafios Kaizen
A página `desafios.html` inclui três jogos em JavaScript puro: Quiz Kaizen, Mini Sudoku 4x4 e Kaizen Flight (Canvas). Pontos, nível e recorde ficam no `localStorage` do navegador e não exigem cadastro ou servidor.
