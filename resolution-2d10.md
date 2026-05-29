# Resolution System: 2d10+Modifier

**System Type:** 2d10 + modifiers vs. static thresholds (triangular distribution)

For shared foundational mechanics (Actions, Approaches, Momentum, Stress, Talents), see [core-foundations.md](core-foundations.md).

---

## Resolution Mechanic

**Roll 2d10 + Approach + modifiers, compare to thresholds.**

Your modifier = Approach rating + situational bonuses (from Edge, flat bonuses).

### Thresholds

| Threshold | Outcome | Effect |
|-----------|---------|--------|
| **10 or less** | Failure | Things go wrong, situation worsens |
| **11–15** | Conflict | Partial success with cost, complication, or lesser effect |
| **16–20** | Success | You accomplish your intent cleanly |
| **21+** | Triumph | Success with added benefit (earn 1 Momentum + choose one from Triumph menu in [core-foundations.md](core-foundations.md#triumph-menu)) |

**Range:** 2d10 gives 2-20 base roll, modifiers add +1 to +6 (starting characters +2, experienced +4 to +6).

---

## Approaches

**Starting Array:** 2/1/1/0/-1 (assign as desired)

**Advancement:** Can increase to 3 (exceptional) at mid-tier, or 4 (legendary) at heroic tier. Maximum: 4.

**Your modifier starts with your Approach rating.**

---

## Traits

**Mechanic:** When a Trait is narratively relevant, **gain Edge on your roll** (only one Trait per roll).

**Edge = roll 3d10, drop the lowest, add your modifier.**

---

## Edge & Bane

Edge and Bane represent advantage and disadvantage in this system.

**Edge (Advantage):**
- **1 Edge:** Roll 3d10, drop lowest
- **2+ Edges:** Roll 4d10, drop 2 lowest (maximum, no further stacking)
- Sources: Traits, Opportunities, Talents, tactical positioning

**Bane (Disadvantage):**
- **1 Bane:** Roll 3d10, drop highest
- **2+ Banes:** Roll 4d10, drop 2 highest (maximum, no further stacking)
- Sources: Complications, Conditions, hostile environment

**Cancellation:** Edge and Bane cancel each other 1:1 before applying.

---

## Opportunities & Complications

**Opportunities:**
- Each Opportunity grants **1 Edge**
- Multiple Opportunities stack up to maximum 2 Edges (4d10 drop 2 lowest)

**Complications:**
- Each Complication inflicts **1 Bane**
- Multiple Complications stack up to maximum 2 Banes (4d10 drop 2 highest)

Opportunities and Complications cancel 1:1 before applying as Edge/Bane.

---

## Conditions (Penalty Details)

| Tier | Penalty |
|---|---|
| **Minor** | -1 to relevant rolls |
| **Moderate** | -2 to relevant rolls |
| **Severe** | -3 to relevant rolls, fictional restrictions |
| **Critical** | Cannot act in specific ways, may force Taken Out |

---

## Momentum

**Momentum Cap:** 2 (can be increased to 3 with specific Talent)

### Momentum Spends (2d10 Effects)

**Boost (1/2/3 Momentum):** Gain Edge before rolling.
- First Edge costs 1 Momentum
- Second Edge costs 2 Momentum (total 3 spent, grants 2 Edges = 4d10 drop 2)
- Third Edge costs 3 Momentum but provides no additional benefit beyond 2 Edges (rarely used)

**Act with Potency (2 Momentum):** Gain Potency on this roll. Remove all Banes imposed by difficulty (keep Banes from other sources). On Triumph, choose two options from Triumph menu instead of one.

**Aid Ally (1 Momentum):** Grant 1 Edge to an ally's upcoming roll.

See [core-foundations.md](core-foundations.md#momentum-single-currency) for full Momentum spending options.

**Design Note:** With Momentum cap of 2, players typically cannot afford multiple boosts on a single roll. Strategic spending is crucial.

---

## Probability Tables

### Base 2d10 Outcomes (No Edge)

| Modifier | Conflict+ (11+) | Success+ (16+) | Triumph (21+) |
|----------|-----------------|----------------|---------------|
| +2 | 72% | 28% | 3% |
| +3 | 79% | 36% | 6% |
| +4 | 85% | 45% | 10% |
| +5 | 90% | 55% | 15% |
| +6 | 94% | 64% | 21% |

### With 1 Edge (3d10 drop lowest)

| Modifier | Conflict+ (11+) | Success+ (16+) | Triumph (21+) |
|----------|-----------------|----------------|---------------|
| +2 | 91.8% | 58.9% | 7.9% |
| +4 | 96.7% | 71.1% | 23.3% |
| +6 | 99.1% | 84.1% | 42.9% |

### With 2 Edges (4d10 drop 2 lowest)

| Modifier | Conflict+ (11+) | Success+ (16+) | Triumph (21+) |
|----------|-----------------|----------------|---------------|
| +2 | 97.01% | 75.79% | 13.91% |
| +4 | 99.19% | 87.45% | 36.68% |
| +6 | 99.9%+ | 95.2% | 60.3% |

**Starting Character (Approach 2, Trait grants Edge = 3d10 drop lowest +2):**
- 91.8% Conflict+, 58.9% Success+, 7.9% Triumph
- Consistent and competent with rare Triumphs

**Experienced Character (Approach 3 or 4, Trait Edge, Talent Edge = 4d10 drop 2 +4):**
- 99.19% Conflict+, 87.45% Success+, 36.68% Triumph
- Heroic with frequent Success, meaningful Triumph rate

---

## Difficulty Modulation

**Instead of changing thresholds, GM grants Edge or Bane:**

| Difficulty | Modifier |
|------------|----------|
| **Easy** | Grant 1 Edge |
| **Standard** | No modifier (most common) |
| **Hard** | Impose 1 Bane |
| **Very Hard** | Impose 2 Banes |

---

## Advancement Structure

**Starting Power Level:** 3d10 drop lowest +2 (Approach 2 + Trait Edge)
- 91.8% Conflict+, 58.9% Success+, 7.9% Triumph
- Consistent with rare heroic moments

**Tier 1 (Early Game):** Increase to +3 or +4 through Approach advancement
- Gain situational Talents that grant Edge or flat bonuses
- Target: 3d10 drop lowest +3 or +4

**Tier 2 (Mid Game):** Stack multiple Edge sources
- Trait Edge + Talent Edge + situational Opportunity = 4d10 drop 2
- Target: 4d10 drop 2 +4 (99.19% Conflict+, 87.45% Success+, 36.68% Triumph)

**Tier 3 (Heroic Tier):** Capstone Approaches at 4, multiple Edge sources, powerful Talents
- Unlock Trait Invocation mechanics
- Frequent double-Edge scenarios
- Target: 4d10 drop 2 +6 (99.9%+ Conflict+, 95.2% Success+, 60.3% Triumph)

**Maximum Modifier:** +6 (Approach 4 + situational bonuses), 4d10 drop 2

---

## Design Notes

**Why 2d10+Modifier?**
- **Faster resolution:** One roll, add modifier, done (no counting)
- **Wider numerical range:** 2-20 base provides more room for modifiers
- **Longer advancement runway:** Can scale from +2 to +6 over multiple tiers
- **Triangular distribution:** Flatter bell curve than 2d6, making extreme results more common but still clustering toward middle

**Edge vs. Flat Bonuses:** This system uses Edge (extra dice, drop lowest) as the primary bonus mechanism to preserve the triangular distribution feel. Flat bonuses (+1, +2) are reserved for permanent advancement (Approach increases) and rare situational effects.

**Momentum Economy:** With cap of 2, players face tight resource decisions. 13.91% Triumph rate with double Edge keeps Momentum generation sustainable but not abundant.

**Talent Design:** Talents should avoid bonus bloat. Focus on:
- Failure mitigation (turn Failure into Conflict)
- Edge grants in specific circumstances
- Unique moves and special techniques
- Passive effects (extra Stress box, etc.)
- Triggered effects (when X happens, you may Y)

---

## Quick Reference

**Typical Starting Roll:** 3d10 drop lowest +2
- 10 or less = Failure (8.2%)
- 11-15 = Conflict (32.9%)
- 16-20 = Success (51%)
- 21+ = Triumph (7.9%)

**Spending Momentum for Edge:** 1 Edge for 1 Momentum (before rolling)

**Using a Trait:** Gain 1 Edge when narratively relevant

**Opportunities/Complications:** Convert to Edge or Bane (max 2 Edges or 2 Banes)
