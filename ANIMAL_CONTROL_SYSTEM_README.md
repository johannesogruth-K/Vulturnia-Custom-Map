# ==============================
# README - Animal Control & Autonomy System
# ==============================

## Overview

This system adds a **Control vs. Autonomy mechanic** to the Aquis religion. Players can choose how much autonomy to give their animals, creating a strategic gameplay choice:

- **More Control** = You can direct animals and buildings, but lower production bonuses
- **More Autonomy** = Higher production bonuses, but animals won't obey commands

## Control Levels

### Full Control (0%)
- **Bonus**: -10% (penalty)
- **Effects**: Complete dominion, can direct animals in warfare, full tax collection
- **Drawback**: Animals are less efficient
- **Use Case**: Military-focused gameplay

### Strict Control (20%)
- **Bonus**: +5%
- **Effects**: Animals mostly obey, some autonomy but you retain command
- **Drawback**: Minimal efficiency gains
- **Use Case**: Balanced approach

### Balanced Management (40%)
- **Bonus**: +15%
- **Effects**: Moderate control, animals work with decent efficiency
- **Drawback**: Some loss of direct command capability
- **Use Case**: **Recommended for most players**

### Mostly Autonomous (60%)
- **Bonus**: +35%
- **Effects**: Animals largely independent, significant productivity boost
- **Drawback**: Limited ability to direct them
- **Use Case**: Economy-focused gameplay

### Full Autonomy (100%)
- **Bonus**: +60%
- **Effects**: Maximum production, animals work at peak efficiency
- **Drawback**: Cannot use animal power, animals won't obey, cannot siphon treasury
- **Penalties**: Animals may disobey in warfare
- **Use Case**: Late-game economic powerhouse

## Animal Centers (New Holding Type)

**Animal Centers** are a new holding type exclusive to Aquis followers:

- Can **only house animal-related buildings** (breeding grounds, hunting grounds, etc.)
- Provide **5 building slots** (vs 3-4 for other holding types)
- Base **+100 supply limit** (excellent for military logistics)
- Base **+0.5 gold income** (low base, but buildings make it profitable)
- Cannot contain castles, cities, or temples
- Can be constructed with the decision "Construct an Animal Center"

### Why Animal Centers?
- **Specialization**: Focus all your animal buildings in one holding
- **Efficiency**: More building slots = more animal production
- **Lore**: Aquis faith sees animal sanctuaries as sacred complexes
- **Strategy**: Create a specialized "animal economy" separate from your regular holdings

## How to Change Control Policy

1. Go to one of your counties
2. Use the decision "Adjust Animal Control Policy"
3. Choose your desired control level:
   - Full Control
   - Strict Control
   - Balanced Management
   - Mostly Autonomous
   - Full Autonomy
4. The county receives a modifier reflecting that policy
5. All animal buildings in that county are affected by the modifier

## Traits

### Aquis Animal Controller
- Prefers strict control
- **Bonus**: +2 Stewardship, +10% County Tax
- **Penalty**: -10% Animal Influence
- Best for: Military-focused rulers

### Aquis Animal Liberator
- Prefers autonomy
- **Bonus**: +1 Diplomacy, +25% Animal Influence, +0.15 Gold/Month
- **Penalty**: None (animals harder to command)
- Best for: Economy-focused rulers

## Script Values

Modders can use these script values:

- `vulturnia_get_animal_control_level` - Returns 0-100 based on current policy
- `vulturnia_get_autonomy_bonus` - Returns the production modifier (e.g., 0.60 for 60%)
- `vulturnia_can_use_animal_power` - Returns 1 if control level <= 60%
- `vulturnia_animals_autonomous` - Returns 1 if control level >= 80%

## Strategic Decisions

### Early Game (0-20% autonomy)
- Use Full or Strict Control
- Focus on military applications
- Build in regular castle/temple holdings
- Good for expansion and warfare

### Mid Game (40% autonomy)
- Switch to Balanced Management
- Begin constructing Animal Centers
- Mix military and economic benefits
- Build diverse animal buildings

### Late Game (60-100% autonomy)
- Transition to Mostly Autonomous or Full Autonomy
- Maximize production and income
- Use as wealth engine to fund wars
- Accept loss of direct animal control

## Interaction with Regular Buildings

- Animal Influence buildings work in **any holding type** (castles, cities, temples, animal centers)
- Control policies apply **at the county level** to all holdings in that county
- A single county can only have **one active control policy** at a time
- Switching policies removes the old one and applies the new one

## Balance Notes

- **Full Control** has a penalty to encourage players to try autonomy
- **Balanced (40%)** is the "sweet spot" for most playstyles
- **Full Autonomy (100%)** provides massive bonuses but removes warfare control
- The autonomy bonus scales production, not direct income (applies to all animal buildings)

## Future Expansion

Potential additions:
- Rebellion events when control becomes too strict
- Animal escape/death events during high autonomy
- Religious debate/schism about "correct" animal management
- Decisions to negotiate with animals
- Animal-specific wars and conflicts

---

**The path of the Aquis is one of choice: dominate the beasts, or free them and prosper.**
