# ASSIGNMENT-3

## HOW TO RUN

```bash
python3 game.py
```

- To review gameplay

```bash
python3 replay.py
```

## GAME ADDITIONS

### CONTROLS

#### Stealth Archers

- t - spawn at point 1
- y - spawn at point 2
- u - spawn at point 3

#### Healers

- f - spawn at point 1
- g - spawn at point 2
- m - spawn at point 3

### ASSUMPTIONS

#### Stealth Archer

- Each Stealth Archer becomes invisible for 10 sec from the moment it was spawned. They cannot be targeted by any buildings while invisible.
- After 10 seconds are over from the time the Stealth Archers were spawned, they will
behave like normal Archers.
- Range of stealth archer - 4 tiles
- Maximum limit of stealth archers spawned = 7

#### Healer

- Healer targets the nearest troop, and heals the troops in its area of effect.
- Heal Range = 7 tiles
- Heals every troop in the area of effect(3X3 matrix)

#### BONUS

***BONUS WAS IMPLEMENTED***
