# Interface
Pasta: `assets/images/ui/` — tudo em **minúsculo**, formato **.png**.
Elementos da interface. Todos **inteiros** (imagem única).

## Já ligado no código (é só salvar o arquivo com este nome)
| Arquivo | Tipo | Tamanho sugerido | Quando aparece |
|---|---|---|---|
| `heart_full.png` | inteira | 24×24 | coração cheio |
| `heart_empty.png` | inteira | 24×24 | coração vazio (sem ele, usa o cheio apagado) |
| `title.png` | inteira | ~420 de largura | logo do menu (no lugar do texto) |
| `button.png` | inteira | 380×68 | fundo dos botões do menu (o texto fica por cima) |
| `button_go.png` | inteira | 380×68 | fundo do botão INICIAR |
| `btn_left.png` | inteira | 128×128 | botão ◀ de toque |
| `btn_right.png` | inteira | 128×128 | botão ▶ |
| `btn_jump.png` | inteira | 128×128 | botão PULAR |
| `btn_sprint.png` | inteira | 128×128 | botão CORRER |
| `btn_push.png` | inteira | 128×128 | botão EMPURRAR (o cooldown aparece por cima) |
| `btn_menu.png` | inteira | 64×64 | botão ☰ |
| `btn_<nome>_down.png` | inteira | igual ao normal | opcional: versão pressionada (ex.: `btn_jump_down`) |

## Ainda NÃO ligado (nome reservado; só funciona depois que a mecânica existir no jogo)
- Telas de lobby e resultados ainda são desenhadas por código, sem sprites próprios.

## Regras
- **Animada** = tira horizontal de quadros quadrados (96×32 = 3 quadros). **Inteira** = imagem única, esticada.
- Desenhe olhando para a **direita**.
- Arquivo ausente = o jogo usa a forma vetorial antiga. Para conferir: `index.html?assets`.
