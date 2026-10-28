# Texturas (tiles)
Pasta: `assets/images/tittles/` — tudo em **minúsculo**, formato **.png**.
O jogo aceita esta pasta com o nome `tittles` (e também `tiles`/`titles`). Textura quadrada repetida; usa o 1º quadro. Plataformas têm 20 px de altura: aparece só a faixa de cima.

## Já ligado no código (é só salvar o arquivo com este nome)
| Arquivo | Tipo | Tamanho sugerido | Quando aparece |
|---|---|---|---|
| `plat.png` | animada (1º quadro) | 32×32 | plataforma comum |
| `wall.png` | idem | 32×32 | parede |
| `floor.png` | idem | 32×32 | chão |
| `goal.png` | idem | 32×32 | plataforma da meta |
| `temp.png` | idem | 32×32 | piso temporário |
| `temp_warn.png` | idem | 32×32 | piso temporário avisando |
| `crumble.png` | idem | 32×32 | plataforma que desmorona |
| `crumble_warn.png` | idem | 32×32 | desmoronando (aviso) |
| `<estrutura>_plat.png` | idem | 32×32 | plataforma de uma estrutura: `cemiterio_plat`, `floresta_plat`, `corredor_plat`, `oceano_plat`, `fabrica_plat` |
| `<estrutura>_wall.png` | idem | 32×32 | parede de uma estrutura: `cemiterio_wall`, `floresta_wall`... |

## Ainda NÃO ligado (nome reservado; só funciona depois que a mecânica existir no jogo)
- Estruturas novas: use `<id>_plat` e `<id>_wall` com o id que o editor gerar.

## Regras
- **Animada** = tira horizontal de quadros quadrados (96×32 = 3 quadros). **Inteira** = imagem única, esticada.
- Desenhe olhando para a **direita**.
- Arquivo ausente = o jogo usa a forma vetorial antiga. Para conferir: `index.html?assets`.
