---
tags: [minecraft, haven-smp, server, readme]
created: 2026-07-23
updated: 2026-07-23
---

# ⚔️ Haven SMP — Servidor Minecraft Vanilla+ Crossplay

> **IP Java:** `crafty.inovati.cloud` | **Porta Bedrock:** `19132`
> **Versão:** 1.21.8 (Minecraft 26.2) | **Servidor:** Purpur 26.2

Servidor survival Vanilla+ com crossplay entre Java e Bedrock. Sem mods obrigatórios no servidor — tudo que você precisa está nos plugins. O servidor foca em manter a essência vanilla enquanto adiciona qualidade de vida, economia, RPG e uma pitada de aleatoriedade com cervejas e encantamentos custom.

---

## 🔗 Como Entrar

### Java Edition
1. Abra o Minecraft Java (qualquer launcher, offline funciona)
2. Adicione o servidor: **`crafty.inovati.cloud`**
3. Entre!

### Bedrock Edition (Console, Celular, PC)
1. Vá em Servidores → Adicionar
2. IP: **`crafty.inovati.cloud`**
3. Porta: **`19132`**
4. Entre com sua conta Xbox normalmente

### 🔄 Primeira Vez? Linke Suas Contas!
Se você joga tanto no Java quanto no Bedrock e quer **compartilhar o mesmo personagem** (inventário, posição, skills):

1. Entre pelo **Java** com seu nick
2. Digite no chat: `/linkaccount SeuNickNoBedrock` *(ex: `/linkaccount VictorLopes3101`)*
3. Anote o **código** que aparecer (ex: `0298`)
4. Entre pelo **Bedrock** com seu nick
5. Digite: `/linkaccount SeuNickJava CÓDIGO` *(ex: `/linkaccount RopesuDesu 0298`)*
6. Saia e entre de novo — **pronto!** Agora Java e Bedrock são o mesmo personagem.

> ⚠️ Se você joga só em uma plataforma, ignore essa parte. O link é opcional.

---

## 💰 Economia

Moeda: **R$** (Real)

| Como Ganhar                          | Como Gastar           |
| ------------------------------------ | --------------------- |
| `/sell hand` — vender item da mão    | `/home` — R$10        |
| `/sell all` — vender todo inventário | `/sethome` — R$25     |
| Criar loja com `/qs create`          | `/tpa` — R$25         |
| Minerar, farmar, pescar...           | `/tprandom` — R$2.000 |
| Upar skills (R$ por level)           | `/back` — R$500       |
|                                      | `/enderchest` — R$100 |
|                                      |                       |

**Saldo inicial:** R$300

**Preços do `/sell`:** Digite `/worth <item>` no jogo para ver o preço de qualquer item.

> 💲 **Tabela completa**: [[minecraft-smp/worth|Guia de Preços /sell]] — diamante R$100, netherite R$1.000, todos os itens por categoria

> 💰 **Saber mais**: [[minecraft-smp/economy|Guia completo de Economia]] — todos os comandos e custos
> 🏪 **Saber mais**: [[minecraft-smp/shops|Guia de Lojas e Economia]] — como criar loja, top itens pra vender, estratégias pra ficar rico

---

## 📜 Comandos

### Todo Jogador

| Comando | Custo | Faz |
|---|---|---|
| `/sethome <nome>` | R$25 | Salva local como casa (máx 3) |
| `/home <nome>` | R$10 | Teleporta pra casa salva |
| `/spawn` | Grátis | Vai pro spawn |
| `/tpa <jogador>` | R$25 | Pede pra teleportar até alguém |
| `/tpaccept` | Grátis | Aceita pedido de teleporte |
| `/tpdeny` | Grátis | Recusa pedido |
| `/tprandom` | R$2.000 | Teleporte aleatório (500-10.000 blocos) |
| `/back` | R$500 | Volta ao último lugar |
| `/bal` | Grátis | Saldo |
| `/baltop` | Grátis | Ranking dos mais ricos |
| `/pay <nome> <valor>` | Grátis | Enviar dinheiro |
| `/enderchest` | R$100 | Baú do fim portátil (27 slots) |
| `/sell hand` | Grátis | Vender item da mão |
| `/sell all` | Grátis | Vender tudo do inventário |
| `/msg <jogador>` | Grátis | Mensagem privada |
| `/rules` | Grátis | Guia do servidor |
| `/skin <nome>` | Grátis | Trocar skin |
| `/skills` | Grátis | Suas habilidades RPG |
| `/stats` | Grátis | Seus atributos |

---

## 🛡️ Proteção de Terreno (GriefPrevention)

Proteja suas construções com claims!

1. Pegue uma **Pá de Ouro** (craft: 2 gravetos + 1 ouro)
2. Clique com botão direito em um canto do terreno
3. Clique no canto oposto
4. Pronto! Só você constroi e quebra ali.

**Você ganha 100 blocos de claim por hora jogada.**

| Comando | Faz |
|---|---|
| `/trust <jogador>` | Amigo pode construir na sua claim |
| `/containertrust <jogador>` | Amigo pode abrir seus baús |
| `/accesstrust <jogador>` | Amigo pode usar botões/alavancas |
| `/abandonclaim` | Deletar a claim (recupera os blocos) |

---

## ⛏️ Mineração e Coleta

**BetterVeinminer** — Agache (Shift) + Picareta = minera a veia inteira de minério e pedras. Cooldown de 10s.

**TreeGravity** — Quebre o tronco de baixo de qualquer árvore = a árvore inteira cai (troncos + folhas).

---

## ✨ Encantamentos Custom (53)

Obtidos na **mesa de encantamento** (nível 25+). Também aparecem em loot de dungeon e trocas de villager. Use `/es list` no jogo para ver todos.

**Raridade**: Comum > Incomum > Raro > Lendário. Quanto menor o peso, mais difícil de aparecer. Encante **livros** em vez de itens direto — assim você pode vender livros raros na sua loja (`/qs create`) por R$500-2000 cada!

Villagers também vendem livros encantados com esses enchants — fique de olho nos trades.

> ✨ **Saber mais**: [[minecraft-smp/enchantments|Guia completo de Encantamentos]] — 53 encantamentos com nível, raridade, ferramenta e 💲 preço

### ⛏️ Mineração e Ferramentas
| Encantamento     | Nível Máx | Mesa | Raridade   | Efeito                                       |
| ---------------- | --------- | ---- | ---------- | -------------------------------------------- |
| **Excavation**   | VII       | III  | ⭐⭐ Raro    | Minera 3x3 (lvl 3), 5x5 (lvl 5), 7x7 (lvl 7) |
| **Sunforged**    | I         | I    | ⭐ Lendário | Auto-smelt — derrete minério ao quebrar      |
| **Telekinesis**  | I         | I    | ⭐⭐ Raro    | Drops vão direto pro inventário              |
| **Haste**        | II        | II   | ⭐ Lendário | Mineração mais rápida (efeito Haste)         |
| **Rejuvenation** | III       | III  | ⭐⭐⭐⭐ Comum | Regenera durabilidade lentamente             |
| **Tree Feller**  | ❌         | —    | —          | Desabilitado (TreeGravity já faz)            |
| **Auto Replant** | I         | I    | ⭐⭐⭐⭐ Comum | Colheita replanta automaticamente            |

### ⚔️ Armas Corpo a Corpo
| Encantamento | Nível Máx | Mesa | Raridade | Efeito |
|---|---|---|---|---|
| **Vampiric** | I | I | ⭐⭐⭐ Incomum | Rouba vida ao bater (lifesteal) |
| **Beheading** | III | III | ⭐⭐⭐ Incomum | Chance de dropar cabeça do mob |
| **Lightning** | III | III | ⭐⭐⭐ Incomum | Raio ao bater no inimigo |
| **Exploding** | I | I | ⭐⭐⭐ Incomum | Inimigos explodem ao morrer |
| **Toxic** | I | I | ⭐⭐⭐ Incomum | Reduz cura do inimigo |
| **Crushing** | III | III | ⭐⭐⭐ Incomum | +Dano contra armadura pesada |
| **Perforating** | III | III | ⭐⭐⭐ Incomum | +Dano contra armadura leve |
| **Withering** | III | III | ⭐⭐⭐ Incomum | Causa Wither ao atacar |
| **Poisoning** | III | III | ⭐⭐⭐ Incomum | Causa Veneno ao atacar |
| **Weakening** | II | II | ⭐⭐⭐ Incomum | Causa Fraqueza ao atacar |
| **Sapping** | III | III | ⭐⭐⭐ Incomum | Drena vida/stamina do inimigo |
| **Stunning** | II | II | ⭐⭐⭐ Incomum | Atordoa o inimigo |
| **Slowness** | II | II | ⭐⭐⭐ Incomum | Causa Lentidão ao atacar |
| **Blinding** | I | I | ⭐⭐⭐ Incomum | Causa Cegueira ao atacar |
| **Nausea** | II | II | ⭐⭐⭐ Incomum | Causa Náusea ao atacar |
| **Streak Damage** | III | III | ⭐⭐ Raro | +Dano por hit consecutivo (combo) |
| **Pulling** | II | II | ⭐⭐⭐ Incomum | Puxa o inimigo pra perto |
| **Ground Stomping** | III | III | ⭐⭐⭐ Incomum | Dano em área ao cair de altura |

### 🏹 Arco e Distância
| Encantamento | Nível Máx | Mesa | Raridade | Efeito |
|---|---|---|---|---|
| **AOE Arrows** | II | I | ⭐⭐ Raro | Flechas causam dano em área |
| **Rapid Shot** | III | III | ⭐⭐⭐ Incomum | Dispara flechas mais rápido |
| **Grappling** | II | I | ⭐⭐⭐ Incomum | Flecha te puxa até onde acertou |

### 🛡️ Armadura e Defesa
| Encantamento | Nível Máx | Mesa | Raridade | Efeito |
|---|---|---|---|---|
| **Shielding** | III | III | ⭐⭐⭐ Incomum | Chance de defletir projéteis |
| **Chemical Shield** | I | I | ⭐⭐⭐ Incomum | Bloqueia efeitos de poções ao defender |
| **Steady** | II | II | ⭐⭐⭐ Incomum | Resistência a knockback |
| **Reinforced Plating** | III | III | ⭐⭐⭐ Incomum | +Armor adicional |
| **Damage Reduction** | III | III | ⭐⭐⭐ Incomum | Reduz dano recebido |
| **Vitality** | V | IV | ⭐⭐⭐⭐ Comum | +% de cura recebida |
| **Vigorous** | V | V | ⭐⭐⭐ Incomum | +Vida máxima |
| **Metabolism** | II | II | ⭐⭐⭐⭐ Comum | Reduz fome |
| **Kinship** | III | III | ⭐⭐⭐⭐ Comum | Bônus por aliados próximos |
| **Potion Potency Buff** | II | II | ⭐ Lendário | Poções duram mais e são mais fortes |

### 🏃 Movimento e Utilidade
| Encantamento        | Nível Máx | Mesa | Raridade    | Efeito                               |
| ------------------- | --------- | ---- | ----------- | ------------------------------------ |
| **Flight**          | III       | II   | ⭐ Lendário  | Elytra voa sem foguete               |
| **Speed Boost**     | II        | II   | ⭐⭐⭐ Incomum | +Velocidade ao equipar               |
| **Jump Boost**      | II        | II   | ⭐⭐⭐ Incomum | +Pulo ao equipar                     |
| **Fire Resistance** | I         | I    | ⭐ Lendário  | Resistência ao fogo ao equipar       |
| **Night Vision**    | I         | I    | ⭐⭐ Raro     | Visão noturna ao equipar             |
| **Water Breathing** | I         | I    | ⭐⭐⭐⭐ Comum  | Respiração aquática ao equipar       |
| **Luck**            | III       | III  | ⭐⭐⭐ Incomum | +Sorte ao equipar                    |
| **Strength**        | II        | II   | ⭐⭐⭐ Incomum | +Força ao equipar                    |
| **Step Height**     | I         | I    | ⭐⭐⭐ Incomum | Sobe blocos inteiros (igual cavalo)  |
| **Block Reach**     | III       | III  | ⭐⭐ Raro     | +Alcance de blocos                   |
| **Lava Walker**     | II        | II   | ⭐⭐ Raro     | Anda sobre lava (igual Frost Walker) |
| **Illuminated**     | I         | I    | ⭐⭐⭐ Incomum | Ilumina área ao redor                |
| **Soulbound**       | I         | I    | ⭐⭐⭐⭐ Comum  | Não perde o item ao morrer           |
| **Shockwave**       | III       | III  | ⭐⭐ Raro     | Click direito → empurra mobs         |

### 🔱 Tridente
| Encantamento | Nível Máx | Mesa | Raridade | Efeito |
|---|---|---|---|---|
| **Trident Sharpness** | V | IV | ⭐⭐⭐ Incomum | +Dano no tridente |
| **Scale / Scale 2** | II | II | ⭐⭐ Raro | Escala paredes / nada melhor |
| **Shield Downer** | III | III | ⭐⭐⭐ Incomum | Quebra escudo do inimigo |

### 💀 Maldições
| Encantamento         | Nível Máx | Mesa | Raridade   | Efeito                   |
| -------------------- | --------- | ---- | ---------- | ------------------------ |
| **Curse of Brittle** | III       | III  | ⭐ Lendário | Item quebra mais rápido  |
| **Curse of Heavy**   | I         | I    | ⭐ Lendário | Movimento mais lento     |
| **Curse of Hunger**  | I         | I    | ⭐ Lendário | Fome constante           |
| **Curse of Berserk** | I         | I    | ⭐ Lendário | +Dano causado E recebido |


> 💰 **Dica de ouro**: Encante **livros** em vez de itens! Livros com `Excavation V`, `Flight III` ou `Sunforged` podem ser vendidos por **R$500 a R$5.000** na sua loja (`/qs create`). Os encantamentos lendários (peso 10 ou menos) são os mais valiosos — compre baixo, venda alto!

---

## 🎮 Habilidades RPG (AuraSkills)

Upe suas habilidades jogando normalmente. Ganhe **R$ por level** e desbloqueie habilidades passivas.

| Skill | Como upar |
|---|---|
| Mineração | Quebrar minérios e pedras |
| Combate | Matar mobs com espada/machado |
| Arquearia | Matar mobs com arco |
| Fazenda | Plantar e colher |
| Forrageamento | Cortar árvores |
| Pesca | Pescar |
| Escavação | Quebrar terra/areia/cascalho |
| Defesa | Tomar dano |
| Agilidade | Pular/correr |
| Alquimia | Fazer poções |
| Encantamento | Encantar itens |

**Comandos:** `/skills` (menu), `/stats` (atributos), `/mining`, `/fighting` etc.

> 📖 **Saber mais**: [[minecraft-smp/auraskills|Guia completo de AuraSkills]] — todas as skills, mana abilities, stats, progressão e dicas

---

## 🍺 Cervejaria (BreweryX)

21 receitas de bebidas! **Não usa brewing stand** — use **caldeirões** com fogo embaixo.

### Como Fazer

1. Coloque um **caldeirão** e **fogo embaixo** (magma block, fogueira, netherrack+fogo)
2. Encha de **água** com balde
3. Jogue os **ingredientes** dentro (clique direito com cada item)
4. Use um **relógio** (clique direito no caldeirão) pra ver o tempo
5. Pegue com **frasco de vidro** quando pronto
6. Se a receita pedir: **destile** na brewing stand (sem pó de blaze, só a poção) e **envelheça** num barril de madeira

> 🍺 **Saber mais**: [[minecraft-smp/brewery|Guia completo de Cervejaria]] — 21 receitas com ingredientes, tempos, efeitos e 💲 preço sugerido

### Receitas

#### 🟢 Sem Álcool (0%) — beba à vontade

| Poção | Ingredientes | Efeito | Uso |
|---|---|---|---|
| ☕ Café | 4 Cacau + 2 Açúcar + 1 Leite | Velocidade I + Haste I (5min) | Minerar |
| 🔋 Energético | 3 Cacau + 6 Açúcar + 1 Redstone | Velocidade III + Pulo III + Haste II (2min) | Explosão de ação |
| 🌵 Suco de Cacto | 4 Cacto + 2 Açúcar | Regeneração II + Anti-fogo (2min) | Cura rápida |
| 🍷 Suco de Beterraba | 6 Beterraba + 2 Maçã + 2 Açúcar | Vida extra II (4min) | Tankar lutas |
| 🧊 Chá Gelado | 4 Berries + 2 Gelo + 2 Açúcar + 1 Água | Velocidade + Pulo + Queda Lenta | Exploração segura |

#### 🟡 Álcool Baixo (5-15%) — social

| Poção | Ingredientes | Efeito | Álcool |
|---|---|---|---|
| 🍺 Cerveja | 6 Trigo + 2 Açúcar | Resistência I | 10% |
| 🍏 Cidra | 6 Maçã + 2 Açúcar | Sorte I (5min) | 8% |
| 🍯 Hidromel | 4 Mel + 2 Açúcar | Regeneração + Velocidade | 15% |
| 🍷 Vinho Tinto | 8 Berries + 2 Glow Berries + 2 Açúcar | Regeneração II | 12% |
| 🌑 Stout | 8 Trigo + 2 Cacau + 2 Açúcar | Força I (5min) | 12% |
| 🎃 Licor de Abóbora | 6 Abóbora + 3 Açúcar + 2 Ovo + 1 Leite | Absorção II + Sorte (5min) | 10% |

#### 🟠 Álcool Médio (30-45%) — aventureiro

| Poção | Ingredientes | Efeito | Álcool |
|---|---|---|---|
| 🥃 Rum | 12 Cana + 4 Açúcar | Força I + Velocidade (3min) | 30% |
| 🌵 Tequila | 8 Cacto + 4 Açúcar + 2 Glow Berries | Pulo II + Velocidade II | 35% |
| 🥃 Whiskey | 10 Trigo + 3 Açúcar | Haste II (4min) | 40% |
| 🌊 Poção do Mar | 6 Kelp + 4 Prismarine + 2 Bacalhau | Respiração + Golfinho + Visão Noturna (8min) | 5% |
| 🟣 Elixir do Fim | 4 Chorus + 2 Chorus Estourado + 2 Ender Pearl | Levitação + Queda Lenta + Visão Noturna | 40% |

#### 🔴 Álcool Forte (45-60%) — guerreiro

| Poção | Ingredientes | Efeito | Álcool |
|---|---|---|---|
| 🥔 Vodka | 8 Batata + 3 Açúcar | Resistência II | 45% |
| 🏴‍☠️ Grog | 10 Cana + 3 Nether Wart + 2 Pólvora + 1 Água | Força III + Respiração | 45% |
| 🥕 Moonshine | 6 Cenoura + 4 Açúcar | Força III | 55% |
| 🧪 Absinto | 4 Nether Wart + 2 Blaze + 2 Glowstone + 2 Frasco | Visão Noturna (10min) + Força II | 60% |
| 🔥 Whiskey Flamejante | 3 Blaze + 2 Pólvora + 2 Nether Wart | Anti-fogo (8min) + Força III | 50% |

### Efeitos da Bebedeira

- Álcool 10-20%: Anda torto, tela balança
- Álcool 30-40%: Náusea, vômito
- Álcool 50%+: Desmaio
- **Curas:** Pão (-4), Maçã (-2), Mel (-3), Leite (-2), Maçã Dourada (-6)

---

## 🎨 Personalização

| Comando | Faz |
|---|---|
| `/skin <nome>` | Trocar sua skin (ex: `/skin Notch`) |

Skins offline — qualquer nome de jogador premium funciona.

---

## 🏪 Lojas

### Criar sua Loja (QuickShop)
1. Segure o item que quer vender
2. Olhe para um baú
3. `/qs create <preço>`
4. Clique no baú pra criar a loja

**Todas as lojas são de jogadores.** Não há loja admin — a economia é 100% movida pelos players.

> 🏪 **Saber mais**: [[minecraft-smp/shops|Guia de Lojas e Economia]] — top 20 itens, estratégias de lucro, como criar loja

---

## 📦 Datapacks e Crafting Tweaks

Melhorias vanilla instaladas no servidor (via Vanilla Tweaks):

**Datapacks:** Armor Statues, More Mob Heads, Player Head Drops, Double Shulker Shells, Dragon Drops Elytra, Cauldron Concrete, Cauldron Mud, Chunk Loaders, Elevators, Ender Chest Always Drops, Armored Elytra, Bat Membranes, Silk Touch Budding Amethyst, XP Bottling, Nether Portal Coords

**Crafting:** Craftable Horse Armor, Enchanted Golden Apple (8 blocos ouro + maçã dourada), Rotten Flesh → Leather, Back to Blocks, Universal Dyeing, More Bricks/Stairs/Trapdoors, Unpackable Ice/Wool/Wart

---

## 🎭 Roleplay e Loop de Jogo

### O Conceito

Haven SMP é um servidor **semi-vanilla comunitário**. Construímos juntos uma cidade ao redor do spawn — cada um com sua casa, loja, fazenda. O foco é colaboração: um fazendeiro vende comida, um minerador vende minérios, um cervejeiro vende poções. A economia é movida pelos jogadores.

As áreas mais distantes (via `/tprandom`) são para mineração e coleta de recursos raros. Você sempre volta ao spawn — não existem bases isoladas a 10.000 blocos.

### O Loop do Jogador

Você começa jogando vanilla normalmente. Aos poucos:

1. **Spawn** → Veja `/rules`, explore a cidade. Construa sua primeira casa nas redondezas do spawn
2. **Primeira Grana** → Mine, farme, pesque, venda itens com `/sell hand`. Junte os primeiros R$
3. **Sua Claim** → Com uma pá de ouro, proteja seu terreno com `/trust` pros amigos
4. **Evolua** → Upe suas skills jogando (ganha R$ por level). Encante itens na mesa com os +50 encantamentos custom
5. **Explore** → `/tprandom` (R$1.000) para minerar em lugares distantes. Pegue os recursos e volte ao spawn
6. **Comércio** → Monte sua loja com `/qs create`. Venda o que produz, compre o que precisa dos outros jogadores
7. **Especialização** → Seja o cervejeiro da cidade (BreweryX), o minerador com Excavation 7x7, ou o guerreiro com Soulbound e Vampiric
8. **Fim de Jogo** → Derrote o Ender Dragon em grupo, consiga Elytra, explore o End juntos

### Cargos e Profissões

Desbloqueados via **AdvancedAchievements** — conquiste achievements específicos para liberar cargos com benefícios:
- ⛏️ **Minerador** — Bônus de 2x R$ ao vender minérios (achievement: "Rei dos Diamantes")
- 🌾 **Fazendeiro** — Colheita em área maior (achievement: "Fazendeiro")
- 🍺 **Cervejeiro** — Ingredientes rendem mais (achievement: "Sommelier Lendário")
- 🏪 **Mercador** — Taxa reduzida ao criar lojas (achievement: "Bilionário Villager")
- 🏗️ **Construtor** — Ganha mais claim blocks/hora (achievement: "Torre de Vigilância")

Use `/aach list` para ver todos os achievements e `/aach stats` para seu progresso.

---

## 📊 Informações Técnicas

- **IP Java:** `crafty.inovati.cloud` (porta padrão 25565)
- **IP Bedrock:** `crafty.inovati.cloud` porta `19132` (UDP)
- **Versão:** Minecraft 26.2 (1.21.8)
- **Server:** Purpur 26.2-2614
- **Seed:** `682733421648135930` — escolhida por ter **Slime Chunks extremamente densos** próximos ao spawn. A chunk `-1, 9` tem score 13.00 (máximo) — ideal pra farms de slime logo no início.
- **Mundo:** Large Biomes
- **Dificuldade:** Normal
- **RAM:** 6GB dedicados
- **VPS:** Hostinger KVM 2, 2 vCPU, 8GB RAM, 100GB NVMe
- **Painel:** Crafty Controller 4.10.7

### Plugins Instalados (24)

| Plugin               | Versão   | Função                                         |
| -------------------- | -------- | ---------------------------------------------- |
| AdvancedAchievements | 7.4.2    | Conquistas com recompensa em R$ — `/aach list` |
| AnimatedScoreboard   | 0.3.9    | Scoreboard lateral (dinheiro, ping, TPS)       |
| AuraSkills           | 2.3.12   | RPG — 11 skills, R$ por level                  |
| BetterSleeping       | 1.4      | Dormir com % de jogadores                      |
| BetterVeinminer      | 1.5.2    | Veia de minério (shift+picareta)               |
| BreweryX             | 3.7.0    | Cervejaria — 21 receitas em caldeirão          |
| Chunky               | 1.5.3    | Pré-geração de chunks (anti-lag)               |
| ClearLag             | 3.2.2    | Limpa itens do chão a cada 10min               |
| DiscordSRV           | 1.30.5   | Chat cruzado Discord↔Jogo                      |
| EconomyShopGUI       | 7.1.1    | Loja do admin (spawn)                          |
| EnchantsSquared      | 2.5.20   | 53 encantamentos na mesa                       |
| EssentialsX          | 2.22.0   | Comandos, economia, /home, /tpa                |
| Floodgate            | 2.2.5    | Autenticação Bedrock + linking                 |
| Geyser-Spigot        | 2.11.0   | Crossplay Bedrock                              |
| GriefPrevention      | 16.18.7  | Claims com pá de ouro                          |
| LuckPerms            | 5.5.60   | Permissões e grupos                            |
| PlaceholderAPI       | 2.12.3   | Placeholders (%player%, %money%)               |
| ProtocolLib          | 5.4.0    | Biblioteca de protocolo                        |
| QuickShop-Hikari     | 6.2.0.11 | Lojas de jogador                               |
| SkinsRestorer        | 15.12.5  | /skin offline                                  |
| StackMob             | 5.9.2    | Agrupa mobs iguais (8 hostis, 16 animais)      |
| TAB                  | 5.0.6    | Tablist com ping e header                      |
| TreeGravity          | 4.7.0    | Árvore cai ao quebrar tronco                   |
| Vault                | 1.7.3    | API de economia                                |

---

## 🖥️ Modpack Client-Side (Opcional)
Se quiser melhorar desempenho e qualidade de vida no seu cliente (100% permitido, zero impacto no servidor):

**Requisitos:** Minecraft 26.2 (1.21.8) + Fabric Loader 0.16.x

**Mods recomendados (43 mods com descrição):**

#### ⚡ Performance
| Mod | Descrição |
|---|---|
| **Sodium** | Renderizador otimizado — 2x-5x mais FPS que o vanilla |
| **Lithium** | Otimiza lógica do servidor (física, mobs, ticking) |
| **Iris Shaders** | Shaders compatíveis com Sodium (Complementary, BSL) |
| **EntityCulling** | Não renderiza mobs atrás de paredes — +FPS grátis |
| **FerriteCore** | Reduz uso de RAM em 30-50% |
| **ModernFix** | Corrige bugs de performance e memory leaks |

#### 🗺️ Mapa
| Mod | Descrição |
|---|---|
| **JourneyMap** | Mapa completo do mundo no canto da tela. Salva explorado, marca waypoints |

#### 🔧 Crafting e Inventário
| Mod | Descrição |
|---|---|
| **JEI (Just Enough Items)** | Catálogo de todas as receitas do jogo (tecla R no item) |
| **JEI WorldGen** | Mostra onde cada minério/bloco gera no mundo |
| **JEP (Just Enough Professions)** | Mostra trades de villager no JEI |
| **JER (Just Enough Resources)** | Mostra % de drop de mobs e loot de baú |
| **Crafting Tweaks** | Botões de rotacionar, balancear e limpar a mesa de craft |
| **Mouse Tweaks** | Arrasta itens com Ctrl+Scroll, shift+clique melhorado |
| **Inventory Profiles Next** | Ordena inventário (tecla R), troca ferramenta quebrada, auto-reabastece |

#### 🛠️ Utilitários
| Mod | Descrição |
|---|---|
| **Zoomify** | Zoom suave (tecla C), configuração de FOV e transição |
| **AppleSkin** | Barra de comida mostra saturação exata |
| **Jade (What am I looking at)** | Mostra nome do bloco/mob/player ao olhar |
| **BetterF3** | F3 turbinado — mostra info que importa, esconde o resto |
| **Light Overlay** | Mostra nível de luz (F7) — blocos vermelhos spawnam mob |

#### 🏗️ Construção — Destaque: Litematica

**Por que Litematica?** É o "WordPress" da construção — carrega uma planta (schematic) que aparece como holograma no mundo, e você constroi por cima. Alguém faz o design no criativo → exporta schematic → todo mundo constroi no survival.

| Mod                    | Descrição                                                      |
| ---------------------- | -------------------------------------------------------------- |
| **Litematica**         | Cria, salva e projeta schematics (plantas) no mundo. Tecla `M` |
| **MaLiLib**            | Biblioteca obrigatória do Litematica                           |
| **MiniHUD**            | HUD customizável: chunk borders, light levels, coordenadas     |
| **Tweakeroo**          | Auto-reabastece blocos da shulker, fast place, gamma boost     |
| **Litematica Printer** | Auto-constrói schematics automaticamente                       |

**Teclas principais:** `M` = menu, `M+C` = mover projeção, `M+G` = verificar camadas, `M+P` = auto-construir

> 💡 Baixe schematics em [minecraft-schematics.com](https://www.minecraft-schematics.com/) e monte com os amigos no survival!

> 🏗️ **Saber mais**: [[minecraft-smp/litematica|Guia completo de Litematica]] — teclas, instalação, como usar, dicas e troubleshooting

#### ✨ Visual
| Mod                   | Descrição                                                  |
| --------------------- | ---------------------------------------------------------- |
| **3D Skin Layers**    | Camadas 3D da skin igual Bedrock (capa, chapéu, cabelo...) |
| **Continuity**        | Vidro e arenito se conectam (texturas unidas)              |
| **LambDynamicLights** | Tocha/machado flamejante na mão ilumina ao redor           |
| **Screenshot Viewer** | Galeria de screenshots dentro do jogo                      |

#### 🎁 Bônus
| Mod                     | Descrição                                                                                                                 |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Shulker Box Tooltip** | Passa mouse na shulker → vê o que tem dentro                                                                              |
| **Chest Tracker**       | Busca "diamante" → mostra em qual baú próximo tem                                                                         |
| **Distant Horizons**    | Renderiza chunks a 256 de distância em LOD (visual, não carrega). **Desativado por padrão** — ative no Mod Menu se quiser |
| **CraftPresence**       | Mostra no Discord "Jogando Haven SMP" com detalhes                                                                        |
| **Flashback**           | Grava replay das últimas horas sem perda de FPS                                                                           |

#### 🌄 Shaders e Texturas
| Pack | Descrição |
|---|---|
| **Complementary Reimagined** | Shader leve e bonito — água reflexiva, luz dinâmica, sombras |
| **Sildur's Enhanced Default** | Shader vanilla melhorado — água, luz, sem exagero |
| **Faithful 32x** | Texturas vanilla em alta resolução (minérios destacados) |
| **Stay True** | Vanilla melhorado — folhas densas, grama variada, connected textures |

Use o **Prism Launcher** (ou Freesm Launcher) — gerencie tudo facilmente.  
**Arquivo pronto disponível:** `Haven SMP.zip` — importe direto no Prism Launcher como instância.

---

## 📚 Documentação Completa

| Arquivo | Conteúdo |
|---|---|
| [[minecraft-smp/litematica\|🏗️ Litematica]] | Guia completo: teclas, schematics, printer, dicas comunitárias |
| [[minecraft-smp/auraskills\|🎮 Habilidades RPG]] | 11 skills, mana abilities, stats, progressão e dicas |
| [[minecraft-smp/enchantments\|✨ Encantamentos]] | 53 encantamentos com níveis, raridade, ferramenta e preço de venda |
| [[minecraft-smp/brewery\|🍺 Cervejaria]] | 21 receitas com ingredientes, tempos, efeitos e preço sugerido |
| [[minecraft-smp/shops\|🏪 Lojas e Economia]] | Como criar loja, top 20 itens, estratégias de lucro |
| [[minecraft-smp/worth\|💲 Tabela de Preços]] | Guia `/sell` completo — todos os itens por categoria com preço |
| [[minecraft-smp/economy\|💰 Economia e Comandos]] | Todos os comandos com custos, como ganhar/gastar |

---

## 📋 Regras

1. Respeite os outros jogadores
2. Não faça grief — use o sistema de claims
3. Trapas e hacks = ban permanente
4. Spawn é área comum — não construa no spawn sem autorização
5. Dúvidas? `/msg RopesuDesu` ou pergunte no chat!

---

**Bom jogo e bem-vindo ao Haven SMP! ⚔️**
