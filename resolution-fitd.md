# Resolution System: Forged in the Dark Dice Pool

**System Type:** Highest-die dice pool (Forged in the Dark method)

For shared foundational mechanics (Actions, Approaches, Momentum, Stress, Talents), see [core-foundations.md](core-foundations.md).

---

## Resolution Mechanic

**Roll Xd6, check the highest single die result (and look for double 6s).**

Your dice pool = Approach rating + modifiers (Traits, Edge/Bane, Talents, Momentum boosts).

### Difficulty & Edge/Bane

**Standard Difficulty:** Roll your pool and check results (no target number to remember).

**Easy Tasks:** Grant **1 Edge** (+1d to your pool)
- Task within character competence, favorable conditions
- Examples: Climbing a ladder with good handholds, persuading a friendly NPC, fighting distracted enemies

**Hard Tasks:** Impose **1 Bane** (-1d from your pool)
- Task at edge of capability, unfavorable conditions
- Examples: Leaping across a wide chasm, negotiating with hostile faction, fighting in pitch darkness

**GM Note:** Default to standard difficulty (no Edge or Bane). Use Edge when PCs have clear advantage. Reserve Bane for dramatic moments where conditions work against them.

### Outcome Tiers

Check your dice results:

- **All 1-3:** Failure — Things go wrong, situation worsens (also called Setback in FitD)
- **Any 4-5:** Conflict — Partial success with cost, complication, or lesser effect
- **Any 6:** Success — You accomplish your intent cleanly
- **Two or more 6s:** Triumph — Success with added benefit (earn 1 Momentum + choose one from Triumph menu in [core-foundations.md](core-foundations.md#triumph-menu))

**Key Principle:** Only the highest single die matters (except for double 6s triggering Triumph).

**Design Note:** This method feels faster and more forgiving than count-successes. Failures become rare past 3d6 (12.4% at 3d6, 6.2% at 4d6), creating a competent-hero feel from the start. However, Triumph rates cap around 33% even at large pools because you need double 6s.

---

## Approaches

**Starting Array:** 2/1/1/0/0 (assign as desired)

**Advancement:** Can increase to 3 (exceptional) or 4 (legendary) at high tiers. Maximum: 4.

**Your dice pool starts with your Approach rating.**

---

## Traits

**Mechanic:** When a Trait is narratively relevant, gain **+1d to your pool** (not Edge — just a direct die). Only one Trait per roll.

**Design Note:** Unlike the Xd6 count-successes system where Traits grant "Edge," in FitD we just say "+1d" to keep language simple. Mechanically it's the same (add a die), but conceptually Traits feel more like "expertise gives you more dice" than "advantage."

---

## Edge & Bane

Edge and Bane represent advantage and disadvantage in this system.

**Edge (Advantage):**
- **1 Edge:** +1d to your pool
- **2 Edges:** +2d to your pool (maximum, no further stacking)
- Sources: Easy tasks, Opportunities, Talents, Momentum, tactical positioning

**Bane (Disadvantage):**
- **1 Bane:** -1d from your pool
- **2 Banes:** -2d from your pool (maximum, no further stacking)
- Sources: Hard tasks, Complications, Conditions, hostile environment

**Minimum Pool:** If reduced to 0 dice, roll 2d6 and take the lowest result.

**Cancellation:** Edge and Bane cancel each other 1:1 before applying to your pool.

**Design Note:** FitD caps Edge/Bane at ±2d to prevent excessive pool bloat. This keeps resolution fast while still rewarding stacking advantages.

---

## Conditions (Penalty Details)

| Tier | Penalty |
|---|---|
| **Minor** | 1 Bane (-1d) to relevant rolls |
| **Moderate** | 2 Banes (-2d) to relevant rolls |
| **Severe** | -3d to relevant rolls, fictional restrictions |
| **Critical** | Cannot act in specific ways, may force Taken Out |

**Note:** Severe Conditions exceed the normal ±2d Edge/Bane cap to represent truly debilitating injuries.

---

## Momentum Spends (FitD Effects)

**Boost (1 Momentum):** Gain 1 Edge (+1d) before rolling.

**Act with Potency (2 Momentum):** Gain Potency on this roll. Remove all Banes from task difficulty (keep Banes from other sources like injuries). On Triumph, choose two options from Triumph menu instead of one.

**Aid Ally (1 Momentum):** Grant 1 Edge (+1d) to an ally's upcoming roll.

See [core-foundations.md](core-foundations.md#momentum-single-currency) for full Momentum spending options.

---

## Probability Tables

### Expected Outcomes (Highest die matters + double 6s)

| Pool Size | Failure % | Conflict % | Success % | Triumph % |
|-----------|-----------|------------|-----------|-----------|
| 1d6 | 49.8% | 33.5% | 16.7% | 0.0% |
| 2d6 | 25.1% | 44.3% | 27.8% | 2.8% |
| 3d6 | 12.4% | 45.5% | 34.7% | 7.3% |
| 4d6 | 6.2% | 42.0% | 38.5% | 13.3% |
| 5d6 | 3.1% | 37.0% | 40.3% | 19.6% |
| 6d6 | 1.6% | 31.9% | 40.2% | 26.3% |
| 7d6 | 0.8% | 27.1% | 39.0% | 33.1% |

**Starting Character (Approach 2 + Trait = 3d6):**
- 12.4% Failure, 45.5% Conflict, 34.7% Success, 7.3% Triumph
- Competent with low failure rate from the start

**Experienced Character (Approach 3 + Trait = 4d6):**
- 6.2% Failure, 42.0% Conflict, 38.5% Success, 13.3% Triumph
- Reliable with failures becoming rare

**Heroic Character (Approach 4 + Trait = 5d6):**
- 3.1% Failure, 37.0% Conflict, 40.3% Success, 19.6% Triumph
- Success tier most common, failures very rare

**Legendary Character (Approach 4 + Trait + 2 Edges = 7d6):**
- 0.8% Failure, 27.1% Conflict, 39.0% Success, 33.1% Triumph
- Success/Triumph combined = 72%, catastrophic failure nearly impossible

**Edge/Bane Impact:**
- Each Edge significantly reduces failure chance (especially at low pools)
- Success tier remains consistent (38-40%) across most pool sizes
- Triumph rate grows but caps around 33% due to double-6 requirement

---

## Advancement Structure

**Starting Power Level:** 3d6 typical pool (Approach 2 + Trait)
- Competent with 12.4% failure rate (much lower than count-successes)

**Tier 1 (Early Game):** 3d6 → 4d6 progression
- Increase Approach 2 → 3, gain situational Talents
- Target: 4d6 pools (6.2% failure, 13.3% Triumph)

**Tier 2 (Mid Game):** 4d6 → 5d6 progression
- Increase Approach 3 → 4, gain more Talents
- Target: 5d6 pools (3.1% failure, 19.6% Triumph)

**Tier 3 (Heroic Tier):** 5d6 → 6d6+ progression
- Stack multiple Edge sources, powerful Talents
- Unlock Trait Invocation mechanics
- Target: 6-7d6 pools (1.6-0.8% failure, 26-33% Triumph)

**Maximum Recommended Pool:** 7d6 (represents legendary heroes, Triumph caps around 33%)

---

## Design Notes

**Why Forged in the Dark Method?**
- **Faster resolution:** Look for highest die (and double 6s), no counting needed
- **More forgiving:** Low failure rates (12.4% at 3d6 vs 29.6% in count-successes)
- **Competent-hero feel:** Characters feel capable from the start
- **Easier to assess:** Glance at dice, see highest result
- **Success-heavy gameplay:** Success tier (38-40%) is most common at higher pools

**Trade-offs:**
- **Triumph caps at ~33%** (requires double 6s, diminishing returns past 6d6)
- **Weaker Momentum economy at high tiers** (compared to count-successes which reaches 43% Triumph)
- **Less dramatic variance** (outcomes more predictable, fewer extreme swings)

**When to Use This System:**
Choose FitD over count-successes if you want:
- Starting characters to feel competent (not struggling)
- Faster resolution (no counting multiple dice)
- More forgiving gameplay (failures rare past 3d6)
- Success-focused narrative (40% Success tier feels reliable)

**Advancement Feel:**
- 3d6 → 4d6 is transformative (failure drops from 12.4% to 6.2%)
- 4d6 → 5d6 feels good (Triumph climbs from 13.3% to 19.6%)
- 5d6 → 6d6 → 7d6 has diminishing returns (Triumph only goes 19.6% → 26.3% → 33.1%)

---

## Quick Reference

**Roll pool, check highest die (and look for double 6s)**

**Typical Starting Roll:** 3d6 (Approach 2 + Trait)
- All 1-3 = Failure (12.4%)
- Any 4-5 = Conflict (45.5%)
- Any 6 = Success (34.7%)
- Two+ 6s = Triumph (7.3%, gain 1 Momentum + choose from Triumph menu)

**Spending Momentum for Edge:** 1 Edge (+1d) for 1 Momentum (before rolling)

**Using a Trait:** +1d to your pool when narratively relevant

**Easy Tasks:** Grant 1 Edge (+1d)

**Hard Tasks:** Impose 1 Bane (-1d)

**Edge/Bane:** Add or remove dice from pool (cap at ±2d), cancel 1:1

**Zero Dice:** If pool reduced to 0d, roll 2d6 and take lowest result
