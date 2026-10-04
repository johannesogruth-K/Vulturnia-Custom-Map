# ==============================
# Vulturnia Animal Aging System README
# ==============================

## Animal Lifespan Rule

Animals in the Aquis tradition do not die quickly. Their natural lifespan is deliberately long, with the design target being approximately 10-30 years depending on species, care, and environment.

This is meant to be tuned later, but the core concept is:

- animals live long enough to grow into important economic and military assets
- old age is a real natural event
- the oldest members can die of age, creating historical rhythm and population turnover

## Autonomy Gain Condition

The autonomy system is intentionally simple:

- If the county or realm's **Animal Influence** becomes greater than **Gold**,
- the autonomy slider gradually ticks upward over time,
- leading to more animal independence.

This creates a gameplay loop:

1. You build animal infrastructure and accumulate influence
2. Influence rises faster than gold
3. Animals begin to act with more independence
4. The control/autonomy slider shifts toward freedom
5. You gain stronger bonuses, but lose more command over the animals

## Balance Tuning Guidance

The values can be tuned later to fit the intended powercurve:

- **Lifespan**: 10-30 years is a good placeholder range
- **Autonomy growth tick**: use small increments (e.g. 0.5-2 per month/annual cycle) for future tuning
- **Influence threshold**: gold vs influence comparison should eventually be replaced by actual scoped province or county values

## Future Expansion

Possible next items:

- species-specific lifespan values
- breeding and elder animal events
- a monthly check that compares animal influence and gold
- age-based mortality events
- disease or health modifiers affecting lifespan
- a custom UI element for current animal age and autonomy

---

The Aquis faith respects life, even when life ends. The oldest animals die with dignity, and with each passing generation the balance between control and freedom shifts again.
