# Personagem
Pasta: `assets/images/player/` — tudo em **minúsculo**, formato **.png**.
Estados do personagem. Se faltar um estado, usa o mais parecido e, por fim, `idle`.

## Já ligado no código (é só salvar o arquivo com este nome)
| Arquivo | Tipo | Tamanho sugerido | Quando aparece |
|---|---|---|---|
| `idle.png` | animada | 32×32 | parado (obrigatório como base) |
| `walk.png` | animada | 32×32 | andando |
| `run.png` | animada | 32×32 | correndo (sprint) |
| `jump.png` | animada | 32×32 | subindo no pulo |
| `fall.png` | animada | 32×32 | caindo |
| `wall.png` | animada | 32×32 | deslizando na parede |
| `hurt.png` | animada | 32×32 | levou dano |
| `dead.png` | animada | 32×32 | eliminado |
| `push.png` | animada | 32×32 | usando EMPURRAR |
| `done.png` | animada | 32×32 | chegou na meta |
| `<cor>/<estado>.png` | animada | 32×32 | skin por cor: `vermelho/`, `azul/`, `verde/`, `amarelo/`, `roxo/` (crie subpastas e ligue `SPR.colorSkins = true`) |

## Ainda NÃO ligado (nome reservado; só funciona depois que a mecânica existir no jogo)
- `stun` — personagem paralisado (a paralisia do EMPURRAR ainda não existe: Etapa 6).

## Regras
- **Animada** = tira horizontal de quadros quadrados (96×32 = 3 quadros). **Inteira** = imagem única, esticada.
- Desenhe olhando para a **direita**.
- Arquivo ausente = o jogo usa a forma vetorial antiga. Para conferir: `index.html?assets`.
