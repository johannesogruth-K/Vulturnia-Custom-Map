# ==============================
# Vulturnia Animal Aging & Autonomy Design Notes
# ==============================

## Safe cleanup pass

This version keeps the original concept but removes the most fragile placeholder logic.
The design intent remains the same:

- Animals age slowly, with a lifespan target of roughly 10-30 years
- Old age eventually causes a natural death event
- If Animal Influence exceeds Gold, autonomy increases gradually
- The autonomy shift is represented by the county policy system already in the mod

## Core rules

1. Long animal lifespan
   - Base target range: 10-30 years
   - Intended for tuning later

2. Old-age death event
   - Represented by a simple event trigger
   - Can later be expanded with species-specific age curves

3. Autonomy growth loop
   - When Animal Influence becomes stronger than Gold, the county drifts toward more autonomy
   - More autonomy gives higher production bonuses, but weaker direct control

## Future tuning

- Raise/lower the lifespan values in `vulturnia_animal_lifespan_min/max`
- Increase/decrease the autonomy gain in `vulturnia_animal_autonomy_gain`
- Replace the placeholder event triggers with more specific province or county checks later

## Important note

This is still a framework-style mod scaffold rather than a guaranteed live CK3 test build. It is meant to be safe, readable, and easier to tune without breaking parser logic.
