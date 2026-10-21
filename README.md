# MONOLITH Loot

**Site: <https://dezdeqness.github.io/WarEra-Mu-Battle-Loot/>** · version **1.3.1**

Loot tracker for the [WarEra](https://app.warera.io) military unit **MONOLITH**: the active battles its members fight in,
the loot tier each member gets right now, and how much damage it takes to move up.

## What it shows

- **MU battles**: one card per battle, with the **round pool** (paid at round end) and the **battle pool** (paid at
  battle end) side by side. Members are grouped by the tier their rank drops right now: ▲ damage to the next tier,
  ▼ lead over the best player below. The card also has the full ranking.
- **All active battles**: a sortable table with the damage needed for every tier, plus the round, tick, score and
  the earliest possible round end.
- **Drop forecast** for a chosen player. It estimates the damage they can still deal before the round ends, from
  their HP, hunger, food, pill, skills, gear and the battle's damage bonuses. It also shows the tier that damage gets
  them and which items are within reach.
- **Player card**: the item a rank drops now with its roll, better items above, and who is catching up below.

Data comes live from the public WarEra API, straight from the browser. No login, no token.

## About this repository

This branch holds only the **built site** that GitHub Pages serves. Each commit is one release, named after its
version. The source code is not published here.

Fan-made tool, not affiliated with WarEra.
