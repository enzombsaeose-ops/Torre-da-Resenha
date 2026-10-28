# Efeitos
Pasta: `assets/images/effects/` — tudo em **minúsculo**, formato **.png**.
Efeitos visuais de jogo.

## Já ligado no código (é só salvar o arquivo com este nome)
| Arquivo | Tipo | Tamanho sugerido | Quando aparece |
|---|---|---|---|
| `lava.png` | animada | 32×32 | faixa de superfície da lava (borda de cima = linha que mata) |
| `lava_body.png` | animada (1º quadro) | 32×32 | corpo da lava, repetido abaixo da superfície |
| `shield.png` | animada | 48×48 | aura dos 3 s de invulnerabilidade |
| `hit.png` | animada | 48×48 | impacto ao perder coração (toca 1 vez, 0,35 s) |
| `push.png` | animada | 48×48 | onda do EMPURRAR (toca 1 vez, 0,25 s) |

## Ainda NÃO ligado (nome reservado; só funciona depois que a mecânica existir no jogo)
- `stun` efeito de paralisia · `dust` poeira de pulo/aterrissagem — ainda sem código.

## Regras
- **Animada** = tira horizontal de quadros quadrados (96×32 = 3 quadros). **Inteira** = imagem única, esticada.
- Desenhe olhando para a **direita**.
- Arquivo ausente = o jogo usa a forma vetorial antiga. Para conferir: `index.html?assets`.
