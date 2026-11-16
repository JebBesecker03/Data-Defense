# Changelog

## 2026-11-16: sizes you can read

### Changed

- **Five tiers of size.** Units now run from tiny (a Point) to titan (the super units), with clear
  gaps between the tiers, so a unit's size tells you what it is. Champions are the largest things
  on the lane after the super units.
- **Height layers.** Ranged units hover, each family at its own height: marks low, support above
  them, area highest. Shots leave from and arrive at those heights.
- **Two families have their own shade** inside their side's one colour: Guard units are dark with
  pale trim, Marks are pale with coloured trim. The opponent is still always red.

### Fixed

- **Units drawn at the wrong size.** In Fast graphics (which Auto switches to when the frame rate
  drops), and for some heavy units while walking, small and medium units were drawn up to three
  times too large, so the army looked as if the size tiers had been undone. Ordering a charge made
  it most visible, because walking units were the ones affected.

## 2026-11-14: the full game

The game went from a six-unit prototype to a complete campaign.

Its structure was inspired by **Epic War 3 by Rudy Sudarto**. Data Defense's theme, units, names,
art, numbers and battles are its own.

### Added

- **Campaign**: 28 battles in three acts and an epilogue, one branching map per act. Each act
  ends in a boss led by a one-of-a-kind unit, which is won by beating it.
- **Units**: 36, up from 6. Five families of six, three bonus units and three super units, with
  new abilities: armour, self-repair, healing, slowing, stunning, a charged first hit, bonus
  damage against one line, hunting the back line, rallying friends, bursting on death and
  sweeping blows.
- **Champions**: 6, up from 2. A campaign starts with one; the second and third come from the
  bosses of acts 1 and 2 with a squad each, and three more are won later. A squad is a champion
  and up to five units, and everything spawns by itself.
- **Spells**: 8, bought with Insight and limited by cooldown. Three can be equipped at first,
  five by the end. From battle 9 the opponent casts spells too.
- **Orders**: Retreat, Hold and Charge, for the whole army or any selection. Retreating units
  walk home at their ordinary speed, so leaving it late gets them caught.
- **Enemy art for every unit**, and the opponent is always red.
- **Animation**: every unit has its own way of moving and its own attack.
- **Depth**: larger units stand further back, so small ones are never hidden.
- **Battlefields** grow more corrupted through the campaign and are cleaned when you win.
- **Base upgrades** now show on the tower, one visible piece per level.
- **Music**: five tracks, with volume sliders in the pause menu.
- **Menus**: an army screen with drag and drop, a spells screen, hover cards for every unit,
  champion and spell, and a how-to before the first battle.
- **Graphics modes**: Full, Fast and Auto, for browsers that draw the canvas slowly.

### Changed

- Units are no longer bought one at a time, and base tiers are gone.
- Towers only fall to hits. Holding more of the lane gives a side faster spawns and harder hits.
- Save codes now start `DD3-`. Codes and saved progress from the earlier version are not accepted.

### Known limits

- Difficulty has only been checked by scripted stand-in players, a few runs per battle. The
  opening battles are probably too easy, and two epilogue battles were never won by them.
- Frame rate on a slow machine in Firefox is not confirmed; the Fast mode exists for it.

## 2026-11-13: first version

One lane, six units bought with Insight, an AI opponent with three difficulty levels, an
eight-battle campaign and two champions.
