# RimWorld Mod Development Notes

## Core References
- Base game data location: `C:\Program Files (x86)\Steam\steamapps\common\RimWorld\Data`

## References
- Vanilla Genetics Expanded
- Vanilla Events Expanded
- Vanilla Traits Expanded
- Vanilla Ideology Expanded - Memes and Structures

## Gilead Ideology Structure

**Primary Memes**
- Male Supremacy
- Supremacist
- Collectivist
- Proselytizer

**Supporting Memes**
- Human Primacy
- Pain is Virtue
- Loyalist

## Implementation Requirements

**Faction Development**
- Create Gilead as a new faction
- Implement slave trader system for handmaids
- Design custom events (escaped handmaids)

**PawnKind Configuration**
- Create handmaiden PawnKind
- Configure trait generation system
- Implement backstory controls

**Handmaid Characteristics**

| Skill Modifiers | Value |
|-----------------|-------|
| Medical Skill   | +5    |
| Social Skill    | -3    |
| Fertility       | +10%  |

**Special Effects**
- Red clothing mood requirement (-5 mood if not wearing red)
- Mental break threshold +10%
- Intellectual work restriction
- Pregnancy mood buff: "Sense of Purpose" (+5)
- Random flashback events

**Trait Conflicts**
- Asexual
- Gay

## Development Tasks
- Implement fertility adjustment system
- Create single-wife, multiple-handmaid structure
- Design custom rituals
- Configure trait and backstory generation
- Develop PawnKind definitions
- Create faction-specific events

## Structure Recommendation
Use "Christian origin" structure template for religious fundamentalist foundation
