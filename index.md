## Porject Zomboid - Perhaps lesser known information

### Trapping
Trapping works by moving your character far away enough from the trap that the chunk unloads, roughly 75 tiles.
After that, it checks every hour if you can catch something with the following formulas:

Chance = (Trap type + Bait type + 1.5 * Skill) * (Zone + 1.5 * Skill)

Chance to lose bait: 1 / (trap strength + 10)

Chance to destroy trap: 1 / (40 * trap strength)

### Traits

## Sources:
https://www.reddit.com/r/projectzomboid/comments/poo6gq/trapping_guide_w_insight_from_the_games_code_v4153/
