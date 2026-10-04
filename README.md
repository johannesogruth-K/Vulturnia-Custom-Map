# Vulturnia - Custom Map

## CK3 Mod: Animal Influence System for Aquis Religion

### Overview

This mod adds a complete Animal Influence system to Crusader Kings III (version 1.20.0.3) for the Aquis religion. It includes:

- **11 Unique Animal-Based Buildings**: Each building provides different bonuses tied to Animal Influence
- **Animal Influence Mechanic**: A new resource system tied to the Aquis faith
- **Aquis Religion Restrictions**: All buildings are restricted to Aquis faith followers only
- **Traits System**: Special traits for Animal Champions and Trainers
- **Event System**: Placeholder events for future development
- **Full Localization**: English language support for all buildings, traits, and modifiers

### Buildings Included

1. **Breeding Grounds** - Increases fertility and gold production
2. **Animal Hospitality** - Provides life expectancy bonuses
3. **Bear Wrestling Club** - Increases martial prowess and combat stats
4. **Parrot Gold Mining** - Generates gold through animal labor
5. **Monkey Tree-Cutters** - Produces resources and development
6. **Rhino Transportation Service** - Improves army movement and supply
7. **Lion Hunting Grounds** - High-tier warfare training building
8. **Elephant Construction Crew** - Reduces construction costs
9. **Crow-Led Animal University** - Education and development center
10. **Investments into Wolf Community** - Provides scheme resistance
11. **Animal Holding** - Grand central holding for all animal affairs

### File Structure

```
Vulturnia - Custom Map/
├── descriptor.mod                                    # Mod metadata
├── README.md                                         # This file
├── common/
│   ├── modifiers/
│   │   └── 00_vulturnia_animal_influence_modifiers.txt
│   ├── buildings/
│   │   └── 00_vulturnia_animal_buildings.txt
│   ├── building_requirements/
│   │   └── 00_vulturnia_building_requirements.txt
│   ├── script_values/
│   │   └── 00_vulturnia_animal_influence_values.txt
│   ├── traits/
│   │   └── 00_vulturnia_animal_traits.txt
│   ├── events/
│   │   └── 00_vulturnia_animal_influence_events.txt
│   └── on_actions/
│       └── 00_vulturnia_animal_influence_on_actions.txt
├── localization/
│   └── english/
│       ├── vulturnia_buildings_l_english.yml
│       ├── vulturnia_events_l_english.yml
│       └── vulturnia_traits_l_english.yml
└── gui/
    └── window_character_state.gui                   # UI framework (placeholder)
```

### Installation

1. Download this mod folder
2. Place it in your CK3 mod directory:
   - **Windows**: `Documents\Paradox Interactive\Crusader Kings III\mod\`
   - **Mac**: `~/Documents/Paradox Interactive/Crusader Kings III/mod/`
   - **Linux**: `~/.local/share/Paradox Interactive/Crusader Kings III/mod/`
3. Enable the mod in CK3's launcher
4. Start a new game (or load a save with Aquis religion enabled)

### Features

#### Animal Influence Mechanic
- Acts as a province-level modifier that stacks with other building bonuses
- Represents the harmony between civilization and nature in Aquis territories
- Provides various gameplay benefits (gold, prestige, martial, development)

#### Aquis Religion Restriction
- All buildings require the ruler and/or province to follow Aquis faith
- Building requirement system ensures lore consistency
- Can be modified in `common/building_requirements/` if needed

#### Traits
- **Aquis Animal Champion**: +2 Martial, +5% Army Damage, +0.25 Animal Influence
- **Aquis Animal Trainer**: +1 Stewardship, +0.15 Animal Influence

### Customization

You can easily customize this mod by editing:

- **Building Costs**: Edit `gold_cost` values in `00_vulturnia_animal_buildings.txt`
- **Building Effects**: Modify province/character modifiers in the same file
- **Descriptions**: Edit localization files in `localization/english/`
- **Requirements**: Adjust restrictions in `00_vulturnia_building_requirements.txt`

### Compatibility

- **CK3 Version**: 1.20.0.3
- **Known Compatible Mods**: Any mod that doesn't directly modify the same building files
- **Conflicts**: May conflict with mods that overhaul the Aquis religion or animal systems

### Future Development

- Full GUI implementation showing Animal Influence as a displayed resource
- Additional events tied to Animal Influence milestones
- Decision trees for Aquis faith followers
- Men-at-Arms combinations using animal regiments
- Custom ambitions and lifestyle perks

### Credits

Created for the Vulturnia - Custom Map project.
Based on CK3 1.20.0.3 modding framework.

### Support

For issues or questions, please check:
1. CK3 Mod Community Forums
2. Paradox Interactive Documentation: https://ck3.paradoxwikis.com/
3. The mod's GitHub repository

---

**Enjoy your journey with the Aquis faith and the mastery of animals!**
