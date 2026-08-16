---
tags: [minecraft, haven-smp, economy, commands]
created: 2026-07-23
updated: 2026-07-23
---

# Economia e Comandos — Haven SMP

## 💰 Economia

**Saldo inicial:** R$300

### Como Ganhar

| Método | Detalhes |
|---|---|
| `/sell hand` | Vende item da mão (preço via `/worth <item>`) |
| `/sell all` | Vende tudo do inventário |
| `/qs create <preço>` | Cria loja com item na mão **(custa R$300 criar)** |
| AuraSkills | R$ por level em cada skill (8 skills) |
| AdvancedAchievements | R$50-10.000 por achievement |
| Vender livros encantados | `Excavation VII` = R$5.000, `Flight III` = R$6.000 |

### Como Gastar

| Comando | Custo |
|---|---|
| `/home` | R$ 10 |
| `/sethome` | R$ 25 |
| `/spawn` | Grátis |
| `/tpa <jogador>` | R$ 25 |
| `/tprandom` | R$ 2.000 |
| `/back` | R$ 500 |
| `/enderchest` | R$ 100 |

---

## 📜 Todos os Comandos

### Teleporte

| Comando | Custo | Descrição |
|---|---|---|
| `/sethome <nome>` | R$10 | Salva local (máx 3 homes) |
| `/home <nome>` | R$5 | Teleporta pra casa |
| `/delhome <nome>` | Grátis | Deleta uma home |
| `/spawn` | Grátis | Vai pro spawn do servidor |
| `/tpa <jogador>` | R$10 | Pede teleporte até alguém |
| `/tpaccept` | Grátis | Aceita pedido |
| `/tpdeny` | Grátis | Recusa pedido |
| `/tprandom` | R$1.000 | Teleporte aleatório (500-10.000 blocos) |
| `/back` | R$300 | Volta ao último lugar |

### Economia

| Comando | Custo | Descrição |
|---|---|---|
| `/bal` ou `/money` | Grátis | Ver saldo |
| `/baltop` | Grátis | Ranking dos mais ricos |
| `/pay <nome> <valor>` | Grátis | Enviar dinheiro |
| `/sell hand` | Grátis | Vender item da mão |
| `/sell all` | Grátis | Vender inventário inteiro |
| `/worth <item>` | Grátis | Ver preço de venda |
| `/enderchest` | R$50 | Baú do fim portátil (27 slots) |

### Lojas

| Comando | Descrição |
|---|---|
| `/qs create <preço>` | Cria loja (segure o item) |
| `/qs buy` | Compra da loja que está olhando |
| `/qs sell` | Vende pra loja que está olhando |
| `/qs price <preço>` | Muda preço da sua loja |
| `/qs remove` | Remove sua loja |
| `/qs find <item>` | Encontra lojas próximas |

### Proteção (GriefPrevention)

| Comando | Descrição |
|---|---|
| `/trust <jogador>` | Amigo constroi na sua claim |
| `/containertrust <jogador>` | Amigo abre baús |
| `/accesstrust <jogador>` | Amigo usa botões/alavancas |
| `/untrust <jogador>` | Remove acesso |
| `/abandonclaim` | Deleta claim (recupera blocos) |
| `/gp` | Abre menu de ajuda do GP |

### Habilidades (AuraSkills)

| Comando | Descrição |
|---|---|
| `/skills` | Abre menu de skills |
| `/stats` | Ver atributos |
| `/mining` | Abre skill Mineração |
| `/fighting` | Abre skill Combate |
| `/farming` | Abre skill Fazenda |
| `/foraging` | Abre skill Forrageamento |
| `/fishing` | Abre skill Pesca |

### Encantamentos (EnchantsSquared)

| Comando | Descrição |
|---|---|
| `/es list` | Lista todos os 53 encantamentos |
| `/es enchant <nome> <nível>` | Aplica encantamento (admin) |
| `/es info <encantamento>` | Info detalhada |

### Cervejaria (BreweryX)

| Comando | Descrição |
|---|---|
| `/brew` | Menu da cervejaria |
| `/brew info` | Nível de bebedeira |
| `/brew wakeup add` | Marca local de wakeup (admin) |

### Achievements

| Comando | Descrição |
|---|---|
| `/aach list` | Menu de achievements |
| `/aach stats` | Progresso pessoal |
| `/aach book` | Livro com suas conquistas |
| `/aach top` | Ranking de jogadores |
| `/aach week` | Top da semana |
| `/aach month` | Top do mês |

### Utilidades

| Comando | Descrição |
|---|---|
| `/skin <nome>` | Trocar skin (ex: `/skin Notch`) |
| `/rules` | Guia do servidor |
| `/msg <jogador>` | Mensagem privada |
| `/r` | Responder última mensagem |
| `/linkaccount <nick>` | Vincular Java↔Bedrock |
| `/chunky` | Pré-geração de chunks (admin) |
| `/tab reload` | Recarregar configuração do TAB (admin) |

---

## 💲 Preços do `/sell` (Worth)

| Categoria | Exemplos | Preço |
|---|---|---|
| Terra/Pedra | Cobblestone, Dirt, Gravel, Sand | R$0.50-1.50 |
| Madeira | Oak Log, Planks | R$2-11 |
| Comida | Pão, Bife, Maçã | R$3-10 |
| Minérios Básicos | Carvão, Ferro, Cobre | R$8-13 |
| Minérios Médios | Ouro, Redstone, Lápis | R$13-44 |
| Minérios Raros | Diamante, Esmeralda | R$55-550 |
| Netherite | Ancient Debris, Scrap, Ingot | R$1.100-4.800 |
| Drops de Mob | Osso, Pólvora, Pérola do Fim | R$1-55 |
| Blocos Especiais | Obsidian, Beacon, Fragmento de Eco | R$130-28.000 |

Digite `/worth <item>` no jogo para ver o preço exato de qualquer item.

## See Also

- [[minecraft-smp/README]] — Guia completo
- [[minecraft-smp/enchantments]] — Encantamentos custom
- [[minecraft-smp/brewery]] — Cervejaria
