# Mythfall — Official Prototype Rules 0.1

**Studio:** PixelForge Studios  
**Format:** Turn-based single-player fantasy card battler

## Objective
Reduce the opposing champion to 0 health before your own champion is defeated. The player starts with 30 health. Each AI trial has a different health total.

## Turn sequence
1. At the start of your turn, maximum energy increases by 1, up to a cap of 5.
2. Energy refills to its maximum.
3. Draw one card, up to a hand limit of five.
4. Summon creatures, use items and creature specials, and attack with ready creatures in any order.
5. End your turn. The AI takes its turn, then your next turn begins.

Each side starts with 1 maximum energy. Cards cost energy to summon. Items and specials do not cost energy in this prototype.

## Board and summoning
Each side has three creature spaces. A creature can only be summoned into an empty space. A newly summoned creature cannot attack until its controller's next turn. A creature stays on the board until its health reaches zero.

## Combat
Select one of your ready creatures, then select an enemy creature to attack it. Both creatures deal their attack as damage simultaneously. A creature with zero or less health is defeated and removed. If the opponent has no creatures, a ready creature can attack the opposing champion directly.

## Starting cards
- **Mossling** — 1 energy, 3 attack, 12 health. Regrowth: restores 2 champion health once per battle.
- **Shardfang** — 2 energy, 5 attack, 18 health. Frostbite: deals 3 damage to the opposing champion and weakens its next attack by 2 (effect under development).
- **Solaryn** — 3 energy, 7 attack, 24 health. Rebirth is represented by a simplified heal in this build; full revive behavior is planned.
- **Prismwyrm** — 4 energy, 9 attack, 30 health. Reality Break: deals 5 damage to the opposing champion and restores 5 champion health.

## Items
- Healing Potion: restore up to 5 champion health.
- Ember Bomb: deal 4 damage to the opposing champion.
- Rune Ward: block up to 3 damage during the current turn.

Items persist between battles and can be used during the player's turn.

## Trials and loot
Defeat the Briar Scout, Crystal Warden and Ashen Oracle in order. Winning grants shards. First victories record progress and unlock further trials and cards. Shards are spent on loot crates.

- Wayfarer Cache — 50 shards: Common 75%, Rare 22%, Legendary 3%.
- Crystal Chest — 100 shards: Common 40%, Rare 45%, Legendary 14%, Exotic 1%.
- Rift Reliquary — 180 shards: Common 15%, Rare 45%, Legendary 32%, Exotic 8%.

Each crate has a 22% chance to award a bonus random item. These are prototype odds; no real-money purchases exist.

## Rarity and scope
Common, Rare, Legendary and Exotic describe collection tiers, not a guaranteed outcome in combat. This is an early prototype with simple AI, placeholder art for Exotic, no multiplayer, no accounts, no server-side saves and ongoing balance work.
