---
tags: [minecraft, haven-smp, litematica, mods, construção]
created: 2026-07-23
updated: 2026-07-23
---

# Litematica — Guia de Construção

## O Que é?

Litematica é um mod client-side que permite carregar **schematics** (plantas de construções) como hologramas no mundo. Você vê exatamente onde cada bloco vai, incluindo cor, orientação e material — e constroi por cima.

No Haven SMP, é a ferramenta principal pra projetos comunitários: alguém desenha no criativo, exporta a schematic, e todo mundo constroi junto no survival.

---
## Teclas e Atalhos

| Tecla | Ação |
|---|---|
| `M` | Abre menu principal do Litematica |
| `M + C` | Abre config da schematic atual (mover, rotacionar) |
| `M + G` | Schematic Verifier — mostra blocos corretos/errados |
| `M + P` | Ativa Printer (auto-constrói, precisa dos blocos no inv) |
| `M + S` | Salva área selecionada como schematic |
| `M + L` | Carrega schematic do arquivo |

---

## Como Usar

### 1. Baixar uma Schematic

Encontre designs prontos:
- [Minecraft Schematics](https://www.minecraft-schematics.com/) — maior acervo
- [Planet Minecraft](https://www.planetminecraft.com/resources/projects/schematics/) — projetos comunitários
- Ou pegue com outros jogadores do Haven (arquivo `.litematic`)

Coloque o arquivo em `.minecraft/schematics/`.

### 2. Carregar no Jogo

1. Pressione `M` → **Schematic Manager**
2. Clique em **Load Schematic** → selecione o arquivo
3. A planta aparece no mundo como holograma

### 3. Posicionar

1. `M + C` → **Configuration Menu**
2. Use os controles para:
   - **Mover** a schematic no eixo X/Y/Z
   - **Rotacionar** (0°, 90°, 180°, 270°)
   - **Espelhar** (flip horizontal/vertical)
3. Ajuste até a projeção ficar no lugar certo

### 4. Construir

Com a schematic posicionada, coloque os blocos manualmente nos lugares indicados pelo holograma.

**Modo Verifier** (`M + G`): mostra em **verde** os blocos já corretos e **vermelho** os que faltam/estão errados. Ideal pra verificar progresso.

**Printer** (`M + P`): coloca blocos automaticamente se você tiver eles no inventário. Útil pra preencher áreas grandes.

### 5. Salvar Sua Própria

1. No criativo, selecione uma área: `M` → **Area Selection** → **Create New Selection**
2. Clique em dois cantos opostos
3. `M` → **Schematic Manager** → **Save Schematic**
4. Dê um nome e salve

---

## Dicas Para o Haven SMP

- 🏘️ **Cidade comunitária**: um jogador desenha o layout no criativo, exporta a schematic, todos constroem no survival
- 🏗️ **Farms eficientes**: schematics de farm de ferro, mob, villager — monte em grupo
- 🎯 **Competição de construção**: cada um faz uma casa e o melhor design vira schematic oficial
- 📐 **Pontes e estradas**: conecte bases com caminhos padronizados
- 🔄 **Backup**: sempre salve suas schematics — se o servidor resetar, você ainda tem o design

---

## Mods Complementares

| Mod | Pra Quê |
|---|---|
| **MaLiLib** | Biblioteca obrigatória |
| **MiniHUD** | Mostra chunk borders, light levels, coordenadas no canto |
| **Tweakeroo** | Auto-reabastece blocos da shulker (pro Printer), fast place, gamma |
| **Litematica Printer** | Auto-constrói — coloca blocos sozinho se tiver no inventário |

Todos já inclusos no modpack do Haven SMP.

---

## Troubleshooting

| Problema | Solução |
|---|---|
| Schematic não aparece | Verifique se está na pasta `.minecraft/schematics/` e se é `.litematic` |
| Printer não funciona | Confira se tem os blocos no inventário E se o Printer está no modo correto (survival) |
| Não acha a tecla `M` | Vá em Options → Controls → Key Binds → procure "Litematica" |
| Holograma travado | `M + C` → "Reset Placement" |

## See Also

- [[minecraft-smp/README]] — Guia completo do servidor
- [Minecraft Schematics](https://www.minecraft-schematics.com/) — Baixar plantas
