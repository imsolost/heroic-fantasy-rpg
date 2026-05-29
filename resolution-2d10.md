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

**Range:** 2d10 gives 2-20 base roll, modifiers add +1 to +6 (starting characters +3 with Trait, experienced +6 to +6).

**Design Note:** 2d10 creates a **triangular distribution** (flatter bell curve than 2d6), making extreme results more common than 2d6 but still clustering toward the middle. 

**Trait as +2 flat bonus:** This design choice means Traits don't consume Edge "budget" — all Edge sources (Opportunities, Momentum, Talents) stack meaningfully up to the 2 Edge cap (4d10 drop 2). This produces high Triumph rates (14.9-59.8% with stacked advantages) and a sustainable Momentum economy, while avoiding the "wasted Edge" problem that occurs when Trait grants Edge instead.

---

## Approaches

**Starting Array:** 1/0/0/-1/-2 (assign as desired)

**Advancement:** Can increase to 2 (competent) at low-mid tier, 3 (exceptional) at mid-high tier, or 4 (legendary) at heroic tier. Maximum: 4.

**Your base modifier = Approach rating.** Add +2 when a Trait applies.

---

## Traits

**Mechanic:** When a Trait is narratively relevant, **gain +2 to your roll** (only one Trait per roll).

Your total modifier = Approach rating + Trait bonus (+2) + any other situational bonuses.

---

## Edge & Bane

Edge and Bane represent advantage and disadvantage in this system.

**Edge (Advantage):**
- **1 Edge:** Roll 3d10, drop lowest
- **2+ Edges:** Roll 4d10, drop 2 lowest (maximum, no further stacking)
- Sources: Opportunities, Talents, Momentum, tactical positioning, easy tasks

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
| +1 | 66% | 21% | 1% |
| +2 | 72% | 28% | 3% |
| +3 | 79% | 36% | 6% |
| +4 | 85% | 45% | 10% |
| +5 | 90% | 55% | 15% |
| +6 | 94% | 64% | 21% |

### With 1 Edge (3d10 drop lowest)

| Modifier | Conflict+ (11+) | Success+ (16+) | Triumph (21+) |
|----------|-----------------|----------------|---------------|
| +1 | 85.4% | 42.1% | 2.8% |
| +3 | 93.0% | 62.2% | 14.9% |
| +5 | 97.7% | 78.5% | 32.8% |

### With 2 Edges (4d10 drop 2 lowest)

| Modifier | Conflict+ (11+) | Success+ (16+) | Triumph (21+) |
|----------|-----------------|----------------|---------------|
| +1 | 93.4% | 59.8% | 5.2% |
| +3 | 97.8% | 80.3% | 24.9% |
| +5 | 99.5% | 90.3% | 48.8% |

**Starting Character (Approach 1, Trait +2 = 2d10 +3):**
- 79% Conflict+, 36% Success+, 6% Triumph
- Competent with occasional Triumphs

**With 1 Edge (Approach 1, Trait +2, Momentum = 3d10 drop lowest +3):**
- 93.0% Conflict+, 62.2% Success+, 14.9% Triumph
- Reliable with meaningful Triumph rate

**Experienced Character (Approach 4, Trait +2, 2 Edges = 4d10 drop 2 +6):**
- 99.9%+ Conflict+, 93.6% Success+, 59.8% Triumph
- Heroic with routine Triumphs

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

**Starting Power Level:** 2d10 +3 (Approach 1 + Trait +2)
- 79% Conflict+, 36% Success+, 6% Triumph
- Competent with occasional Triumphs

**Tier 1 (Early Game):** Increase Approach to 2
- Gain situational Talents that grant Edge or other effects
- Target: 2d10 +4 or 3d10 drop lowest +3 (with Edge)
- 85% Conflict+, 45% Success+, 10% Triumph (base) or 93% Conflict+, 62% Success+, 15% Triumph (with 1 Edge)

**Tier 2 (Mid Game):** Approach 3, stack multiple Edge sources
- Trait +2 + Talent Edge + Momentum Edge = 4d10 drop 2 +5
- Target: 4d10 drop 2 +5 (99.5% Conflict+, 90.3% Success+, 48.8% Triumph)

**Tier 3 (Heroic Tier):** Capstone Approach 4, multiple Edge sources, powerful Talents
- Unlock Trait Invocation mechanics
- Frequent double-Edge scenarios
- Target: 4d10 drop 2 +6 (99.9%+ Conflict+, 93.6% Success+, 59.8% Triumph)

**Maximum Modifier:** +6 (Approach 4 + Trait +2), 4d10 drop 2

---

## Design Notes

**Why 2d10+Modifier?**
- **Faster resolution:** One roll, add modifier, done (no counting)
- **Wider numerical range:** 2-20 base provides more room for modifiers
- **Longer advancement runway:** Can scale from +2 to +6 over multiple tiers
- **Triangular distribution:** Flatter bell curve than 2d6, making extreme results more common but still clustering toward middle

**Edge vs. Flat Bonuses:** Trait grants +2 flat bonus (doesn't consume Edge budget), while situational advantages grant Edge (extra dice, drop lowest). This preserves the triangular distribution feel while allowing all Edge sources to stack meaningfully.

**Momentum Economy:** With cap of 2, players face tight resource decisions. Triumph rates of 14.9-59.8% (depending on Edge stacking and tier) create a sustainable Momentum generation cycle. The flat +2 from Trait significantly improves Triumph rates compared to Edge-based Traits.

**Talent Design:** Talents should avoid bonus bloat. Focus on:
- Failure mitigation (turn Failure into Conflict)
- Edge grants in specific circumstances
- Unique moves and special techniques
- Passive effects (extra Stress box, raise Momentum cap to 3, etc.)
- Triggered effects (when X happens, you may Y)
- Situational flat bonuses (narrow contexts only)

---

## Quick Reference

**Roll 2d10 + Approach + Trait bonus, compare to thresholds (11/16/21)**

**Typical Starting Roll:** 2d10 +3 (Approach 1 + Trait +2)
- ≤10 = Failure (21%)
- 11-15 = Conflict (43%)
- 16-20 = Success (30%)
- 21+ = Triumph (6%, gain 1 Momentum + choose from Triumph menu)

**With 1 Edge (from Momentum/Opportunity):** 3d10 drop lowest +3
- ≤10 = Failure (7%)
- 11-15 = Conflict (31%)
- 16-20 = Success (47%)
- 21+ = Triumph (15%)

**Spending Momentum for Edge:** 1 Edge for 1 Momentum (before rolling) = roll 3d10 drop lowest

**Using a Trait:** +2 to your roll when narratively relevant

**Easy Tasks:** Grant 1 Edge (3d10 drop lowest)

**Hard Tasks:** Impose 1 Bane (3d10 drop highest)

**Opportunities/Complications:** Convert to Edge or Bane (max 2 Edges or 2 Banes)
