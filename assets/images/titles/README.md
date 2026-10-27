# assets/images/tiles

Texturas que se REPETEM em plataformas, paredes e chão (um quadro 32x32 vira azulejo).

Regras: PNG com fundo transparente · cada quadro **32x32 px** · vários quadros ficam LADO A LADO na mesma imagem (o jogo conta sozinho: largura ÷ 32) · nome em minúsculas, sem acento e sem espaço.

| Arquivo (.png) | Situação | O que é |
|---|---|---|
| `plat` | ✅ já funciona | plataforma padrão (qualquer estrutura sem arte própria) |
| `wall` | ✅ já funciona | parede padrão |
| `floor` | ✅ já funciona | chão |
| `goal` | ✅ já funciona | plataforma da meta |
| `<id>_plat` | ✅ já funciona | plataforma de UMA estrutura. Ex.: lar_plat, cemiterio_plat |
| `<id>_wall` | ✅ já funciona | parede de UMA estrutura. Ex.: lar_wall |
| `(ids atuais)` | ✅ já funciona | cemiterio, floresta, corredor, oceano, fabrica, lar. Estrutura nova = o id dela entra automaticamente |
