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
| **10 or less** | Setback | Things go wrong, situation worsens |
| **11–15** | Conflict | Partial success with cost, consequence, or lesser effect |
| **16–20** | Success | You accomplish your intent cleanly |
| **21+** | Triumph | You accomplish your intent fully, gain 1 Momentum, ignore all Complications (see [core-foundations.md](core-foundations.md#outcome-tiers)) |

**Range:** 2d10 gives 2-20 base roll, modifiers add +0 to +5 (starting characters +3, experienced +5).

**Design Note:** 2d10 creates a **triangular distribution** (flatter bell curve than 2d6), making extreme results more common than 2d6 but still clustering toward the middle.

---

## Approaches

**Starting Array:** 3/2/1/0/-1 (assign as desired)

**Advancement:** Can increase to 4 (exceptional) or 5 (legendary) at high tiers. Maximum: 5.

**Your base modifier = Approach rating.**

**Note:** Starting array has been adjusted because Traits no longer grant passive +2. See [traits-complications-challenges.md](traits-complications-challenges.md) for the new Trait tactical menu system.

---

## Traits

**Traits grant Critical Effects when relevant.**

When a Trait is narratively relevant to your action, you may invoke it after rolling:
- **On Conflict or Success:** Choose one Critical Effect
- **On Triumph:** Choose two Critical Effects
- **On Setback:** Cannot invoke Trait

**Critical Effects:** Greater Effect, Secondary Effect, Create an Opportunity

**See [traits-complications-challenges.md](traits-complications-challenges.md) for complete rules.**

---

## Edge & Bane

Edge and Bane represent advantage and disadvantage in this system.

**Edge (Advantage):**
- **1 Edge:** Roll 3d10, drop lowest
- **2 Edge:** Roll 4d10, drop 2 lowest
- **3 Edge:** Roll 5d10, drop 3 lowest (maximum)
- Sources: Easy tasks, Momentum, Talents, tactical positioning, ally assists, favorable environment, Create an Opportunity (Critical Effect), Know action
- See [core-foundations.md](core-foundations.md#edge--bane) for full list

**Edge Trading:**
- **Before rolling:** Trade Edge 1:1 to negate Complications
- Each Edge traded removes one Complication from this roll
- Roll with remaining Edge

**Bane (Disadvantage):**
- **1 Bane:** Roll 3d10, drop highest
- **2 Bane:** Roll 4d10, drop 2 highest
- **3 Bane:** Roll 5d10, drop 3 highest (maximum)
- Sources: Hard tasks, Very Hard tasks, Conditions, hostile environment, poor positioning, injuries
- See [core-foundations.md](core-foundations.md#edge--bane) for full list

**Cancellation:**
1. Edge and Bane cancel 1:1 (before you can trade Edge for Complications)
2. After cancellation, remaining Edge can be kept for dice OR traded for Complication negation

---

## Edge & Bane Stacking

**Edge Sources:**
- Each source of Edge grants **1 Edge**
- Multiple sources stack up to maximum **2 Edges** (4d10 drop 2 lowest)
- See [core-foundations.md](core-foundations.md#edge--bane) for all sources

**Bane Sources:**
- Each source of Bane imposes **1 Bane**
- Multiple sources stack up to maximum **2 Banes** (4d10 drop 2 highest)
- See [core-foundations.md](core-foundations.md#edge--bane) for all sources

**Cancellation:** Edge and Bane cancel 1:1 before applying to your roll.

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

**Gain an Edge (1 Momentum):** Add 1 Edge to YOUR upcoming roll before rolling (roll 3d10 drop lowest, or more if stacking). Can be kept for dice boost OR traded to negate Complication.

**Act with Potency (2 Momentum):** Gain Potency on this roll. Remove all Banes imposed by task difficulty (keep Banes from other sources like injuries, Conditions, environment). Attempt the impossible and achieve enhanced effects.

See [core-foundations.md](core-foundations.md#momentum-single-currency) for full Momentum spending options.

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

**Starting Character (Approach 3 = 2d10 +3):**
- 79% Conflict+, 36% Success+, 6% Triumph
- Competent with occasional Triumphs

**With 1 Edge (Approach 3, Momentum = 3d10 drop lowest +3):**
- 93.0% Conflict+, 62.2% Success+, 14.9% Triumph
- Reliable with meaningful Triumph rate

**Experienced Character (Approach 5, 2 Edges = 4d10 drop 2 +5):**
- 99.5% Conflict+, 90.3% Success+, 48.8% Triumph
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

**Roll 2d10 + Approach, compare to thresholds (11/16/21)**

**Typical Starting Roll:** 2d10 +3 (Approach 3)
- ≤10 = Setback (21%)
- 11-15 = Conflict (43%)
- 16-20 = Success (30%)
- 21+ = Triumph (6%, gain 1 Momentum + ignore all Complications + choose Critical Bonus)

**With 1 Edge (from Momentum or other source):** 3d10 drop lowest +3
- ≤10 = Setback (7%)
- 11-15 = Conflict (31%)
- 16-20 = Success (47%)
- 21+ = Triumph (15%)

**Spending Momentum for Edge:** Gain an Edge (1 Momentum) = add 1 Edge before rolling (can keep for dice OR trade to negate Complication)

**Using a Trait (after rolling):**
- **Conflict or Success:** Choose one Critical Effect
- **Triumph:** Choose two Critical Effects

**Critical Effects:**
1. Greater Effect (mark 2 ticks, ask 6 questions, gain 4 Edge the first time you use it)
2. Secondary Effect (Take Something, Inflict Condition, etc.)
3. Create an Opportunity (grant ally 1 Edge OR negate 1 Complication)

**Action Core Functions:**
- Defy/Clash/Talk: Mark 1 tick on track (Success/Conflict)
- Sense: Ask 2 questions (Success), 1 question (Conflict)
- Know: GM tells you info + gain 1 Edge the first time you roll when acting on that information (Success)

**Edge Trading:** Before rolling, trade Edge 1:1 to negate Complications

**Easy Tasks:** Grant 1 Edge (3d10 drop lowest)

**Hard Tasks:** Impose 1 Bane (3d10 drop highest)

**Very Hard Tasks:** Impose 2 Banes (4d10 drop 2 highest)

**Edge/Bane Cap:** Maximum ±3 (5d10 drop 3), cancel 1:1 before trading
