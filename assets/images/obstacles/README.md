# Obstáculos
Pasta: `assets/images/obstacles/` — tudo em **minúsculo**, formato **.png**.
Armadilhas e objetos do cenário.

## Já ligado no código (é só salvar o arquivo com este nome)
| Arquivo | Tipo | Tamanho sugerido | Quando aparece |
|---|---|---|---|
| `spike.png` | animada | 16×16 | espinho fixo (repetido a cada ~18 px) |
| `rspike.png` | animada, 4 quadros FIXOS | 16×16 | espinho retrátil: 1 seguro, 2 aviso, 3 ativo, 4 recolhendo (sem ela usa `spike`) |
| `saw.png` | animada | 32×32 | serra (com 1 quadro o jogo gira) |
| `spin_bar.png` | inteira | 56×12 | barra giratória: pivô na esquerda, aponta para a direita |
| `spin_hub.png` | animada | 16×16 | pivô da barra |
| `piston_body.png` | inteira | 12×40 | haste do pistão (estica na vertical) |
| `piston_head.png` | inteira | 40×16 | cabeça do pistão |
| `flag.png` | animada | 48×48 | bandeira da meta |

## Ainda NÃO ligado (nome reservado; só funciona depois que a mecânica existir no jogo)
- `spring` plataforma impulsionadora · `fan` ventilador · `door` porta · `switch` interruptor · `gravity_zone` zona de gravidade invertida — esses obstáculos da Etapa 4 ainda não foram implementados.

## Regras
- **Animada** = tira horizontal de quadros quadrados (96×32 = 3 quadros). **Inteira** = imagem única, esticada.
- Desenhe olhando para a **direita**.
- Arquivo ausente = o jogo usa a forma vetorial antiga. Para conferir: `index.html?assets`.
