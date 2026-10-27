# assets/images/player

Personagem. Uma tira horizontal por estado (quadros lado a lado, 32x32 cada).

Regras: PNG com fundo transparente · cada quadro **32x32 px** · vários quadros ficam LADO A LADO na mesma imagem (o jogo conta sozinho: largura ÷ 32) · nome em minúsculas, sem acento e sem espaço.

| Arquivo (.png) | Situação | O que é |
|---|---|---|
| `idle` | ✅ já funciona | parado |
| `walk` | ✅ já funciona | andando |
| `run` | ✅ já funciona | correndo (sprint) |
| `jump` | ✅ já funciona | subindo no pulo |
| `fall` | ✅ já funciona | caindo |
| `wall` | ✅ já funciona | deslizando na parede |
| `hurt` | ✅ já funciona | tomou dano |
| `dead` | ✅ já funciona | foi resenhado (eliminado) |
| `push` | ✅ já funciona | usando EMPURRAR |
| `paralyzed` | 🕓 reservado (ainda sem código) | paralisado (Etapa 6) |
