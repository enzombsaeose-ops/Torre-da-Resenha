# Fundos
Pasta: `assets/images/backgrounds/` — tudo em **minúsculo**, formato **.png**.
Fundos inteiros (imagem única).

## Já ligado no código (é só salvar o arquivo com este nome)
| Arquivo | Tipo | Tamanho sugerido | Quando aparece |
|---|---|---|---|
| `main.png` | inteira | ex.: 540×1400 | fundo do jogo, desliza devagar conforme você sobe |
| `menu.png` | inteira | ex.: 540×960 | fundo do menu |
| `<estrutura>.png` | inteira | 820×560 | fundo de cada estrutura (2 andares): `cemiterio`, `floresta`, `corredor`, `oceano`, `fabrica` |

## Ainda NÃO ligado (nome reservado; só funciona depois que a mecânica existir no jogo)
- Estruturas novas: `<id>.png` com o id do editor.

## Regras
- **Animada** = tira horizontal de quadros quadrados (96×32 = 3 quadros). **Inteira** = imagem única, esticada.
- Desenhe olhando para a **direita**.
- Arquivo ausente = o jogo usa a forma vetorial antiga. Para conferir: `index.html?assets`.
