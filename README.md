# TORRE DA RESENHA

Jogo de plataforma vertical (celular em pé + teclado no PC). Abra `index.html` ou publique no GitHub Pages.

## Arquivos
- `index.html` — o jogo.
- `editor-estruturas.html` — editor visual para desenhar estruturas (cada quadradinho = 50 px).
- `assets/` — toda a arte e som. **Para adicionar uma textura: salve o PNG com o nome certo na pasta certa. Pronto.**

## Pasta assets
```
assets/
├── images/
│   ├── player/        personagem (idle, walk, run, jump, fall, wall, hurt, dead, push)
│   ├── enemies/       monkey, banana, zombie, ghost, shark, eel
│   ├── obstacles/     saw, spike, piston, fan, spring, door, ...
│   ├── tiles/         plat, wall, floor, goal  +  <id>_plat / <id>_wall por estrutura
│   ├── backgrounds/   fundos (parallax) por estrutura
│   ├── ui/            corações, botões, logo
│   └── effects/       empurrar, impacto, lava, poeira
├── audio/
│   ├── sfx/
│   └── music/
└── fonts/
```
Cada pasta tem um `README.md` com a lista de nomes aceitos e a situação (✅ funciona / 🕓 reservado).

## Regras da arte
1. PNG com fundo transparente, **quadros de 32x32**.
2. Animação = quadros lado a lado na mesma imagem (ex.: andar com 4 quadros = imagem 128x32).
3. Nomes em minúsculas, sem acento, sem espaço.
4. Arquivo ausente não quebra nada: o jogo usa a forma simples antiga.
5. Tamanho de desenho diferente de 32x32 (ex.: tubarão grande): `SPR.dim` no começo do bloco de sprites em `index.html`.
6. Estrutura nova no jogo: o `id` dela vira o prefixo das texturas (`<id>_plat.png`, `<id>_wall.png`).

## GitHub Pages
Mantenha `index.html` na raiz do repositório. Caminhos são relativos (`assets/images/...`). Depois de enviar uma arte, aguarde o Pages atualizar e recarregue sem cache.
