# ==============================
# Vulturnia Animal Capacity System
# ==============================

## Capacity Rules

Animals do not all occupy the same amount of space or contribute equally to the same effect. The design intent is:

- smaller animals (like crows) need far more individuals to match the impact of larger animals
- larger animals (like elephants) are more impactful, but each one occupies more of the province's capacity
- if the total population exceeds the province's capacity, Animal Influence gain is reduced

## Example scaling

- Crow: low individual impact, very high number requirement
- Wolf: moderate impact, reasonable capacity cost
- Lion: strong impact, larger capacity requirement
- Rhino: high impact, large capacity requirement
- Elephant: strongest impact, highest capacity requirement

## Capacity logic

When a province is above capacity:

- Animal Influence gain is reduced
- the province receives an over-capacity penalty modifier
- animals become less efficient at producing spiritual or economic influence

When a province is within capacity:

- Animal Influence gain is normal or boosted
- the province receives an optimized-capacity modifier
- growth and productivity match the intended Aquis philosophy

## Tuning guidance

- Increase the capacity values to make the system more forgiving
- Reduce them to make overcapacity stricter and more punishing
- The current system is deliberately simple and can be refined later based on gameplay feel

## Why this works thematically

This matches the Aquis philosophy: not all creatures are equal in value or usefulness. A flock of crows may be numerically abundant, but a single elephant is far more impactful and burdens the ecosystem differently.

The result is a more realistic and strategic animal economy: players must balance the size and efficiency of their animal population to maximize Animal Influence without overloading the holding.
