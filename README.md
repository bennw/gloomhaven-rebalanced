# gloomhaven-rebalanced

An intellectual exercise in rebalancing base Gloomhaven.

**Rebalanced Mechanics:** [see here.](#rebalanced-mechanics)

**Rebalanced Starter Characters:**
- [Brute](Brute/Brute.md)
- [Spellweaver](Spellweaver/Spellweaver.md)

**Rebalanced Locked Characters:**
- [Sun](Sun/Sun.md)

## General Principles

**No card should be auto-benched.** All Level 1/X cards should be situationally playable at minimum. For Level 2+ cards, players should have a meaningful decision to make on each level up.

**Players should not be needlessly punished for experimenting with non cookie cutter actions**. The goal is not to perfectly balance each action relative to every other action. However, in cases where an action is very clearly under the power curve or redundant, due consideration is given in rebalancing it. This applies to loss actions in particular; double-loss cards doubly so.

**Maximum one change per card.** Otherwise, this exercise becomes an extreme makeover and we end up redesigning the characters, which is not the aim here.
  - Changes due to [rebalanced mechanics](#rebalanced-mechanics) do not count toward this limit.
  - There are rare cases where this is violated with very specific reasons - [Spellweaver](Spellweaver/Spellweaver.md) is one such example.
  
Guidelines for card changes, in descending order of preference:

1. Change one number
2. Change multiple related numbers. E.g. Attack 2 at the start of the next 4 turns --> Attack 4 at the start of the next 2 turns

3. Swap numbers or the effects on two different cards
4. Add, move or remove the Loss symbol and/or XP (since XP is often tied to Loss actions)
    - If necessary, also change one number on the same action to keep the card balanced
5. Swap the levels of two cards
    - If necessary, also change one number on the same card to keep it balanced

6. Append an effect (Move/Attack/Heal/Shield/Retaliate/status/element)
7. Add elemental consumption to an existing effect
    - Example of nerf: Move 4 --> Move 3, consume element: +1 Move
    - Example of buff: Move 4 --> Move 4, consume element: +1 Move
8. Replace an action with an entirely new action
    - This should only be used to resolve balance issues not resolvable by any of the earlier techniques, by creating a new niche for the class. E.g. rebalancing the [level 1 double loss for Sun](Sun/Sun.md).

## Rebalanced Mechanics

**Instakill:** abilities that outright kill enemies regardless of HP trivialise difficulty scaling. All instakill abilities will be replaced by one of the following:
  - *Kill enemy with 9 or less remaining HP* - for abilities that thematically imply immediate fatality, such as [Brute's Fatal Advance](Brute/Brute.md).
  - *Inflict Bane status* - for abilities that thematically imply delayed fatality, such as [Spellweaver's Spirit of Doom](Spellweaver/Spellweaver.md).
  - *Conditionally kill enemy* - to be used sparingly; the condition should require significant effort to fulfil.

**Invisibility:** "Doorstopping" involves opening a new room by standing in a doorway while invisible, so that most enemies are are unable to advance and attack. Similarly, having the whole party turn invisible (doable especially at low player counts) negates the vast majority of enemy actions. Both these techniques trivialise difficulty scaling in much the same way as instakill does. This problem can easily be solved without changing core gameplay mechanics - just ban most/all sources of invisibility. However, such a heavy-handed approach reduces the variety of defensive plays in the game, and makes rogue classes less fun to play. To preserve the added dimensions Invisibility has to offer, rebalancing necessarily involves changing Invisibility's core mechanics:
  - *Whenever a monster fails to find a focus, the closest invisible player-allied figure within line-of-sight loses Invisible. If invisibility is lost this way, the monster attempts to find a focus again.* Thematically, the enemy senses suspicious movement (a door swinging open for no reason) and searches the vicinity with heightened senses.
