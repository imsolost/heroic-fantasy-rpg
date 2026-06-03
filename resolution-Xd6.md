# Resolution System: Xd6 Dice Pool

**System Type:** Count-successes dice pool (FitD-inspired)

For shared foundational mechanics (Actions, Approaches, Momentum, Stress, Talents), see [core-foundations.md](core-foundations.md).

---

## Resolution Mechanic

**Roll Xd6, count successes. Each die showing 5 or 6 is a success (Hit).**

Your dice pool = Approach rating + modifiers (Traits, Edge/Bane, Talents, Momentum boosts).

### Difficulty & Edge/Bane

**Standard Difficulty:** Always count 5s and 6s as successes (33% per die).

**Easy Tasks:** Grant **1 Edge** (+1d to your pool)
- Task within character competence, favorable conditions favor success
- Examples: Climbing a ladder with good handholds, persuading a friendly NPC, fighting distracted enemies

**Hard Tasks:** Impose **1 Bane** (-1d from your pool)
- Task at edge of capability, conditions work against success
- Examples: Leaping across a wide chasm, negotiating with hostile faction, fighting in pitch darkness

**Very Hard Tasks:** Impose **2 Banes** (-2d from your pool)
- Task at extreme difficulty, multiple unfavorable factors
- Requires Potency to attempt reliably

**GM Note:** Default to standard difficulty (no Edge or Bane). Use Edge when PCs have clear advantage. Reserve Bane for dramatic moments where conditions work against them. See [core-foundations.md](core-foundations.md#edge--bane) for all sources of Edge and Bane.

### Outcome Tiers

Count your successes (Hits):

- **0 Hits:** Setback — Things go wrong, situation worsens
- **1 Hit:** Conflict — Partial success with cost, consequence, or lesser effect
- **2 Hits:** Success — You accomplish your intent cleanly
- **3+ Hits:** Triumph — You accomplish your intent fully, gain 1 Momentum, ignore all Complications (see [core-foundations.md](core-foundations.md#outcome-tiers))

---

## Approaches

**Starting Array:** 3/2/2/1/0 (assign as desired)

**Advancement:** Can increase to 4 (exceptional) or 5 (legendary) at high tiers. Maximum: 5.

**Your dice pool starts with your Approach rating.**

**Note:** Starting array has been adjusted because Traits no longer grant passive +1d. See [traits-complications-challenges.md](traits-complications-challenges.md) for the new Trait tactical menu system.

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
- **1 Edge:** +1d to your pool
- **Maximum:** +3d (cap)
- Sources: Easy tasks, Momentum, Talents, tactical positioning, ally assists, favorable environment, Create an Opportunity (Critical Effect), Know action
- See [core-foundations.md](core-foundations.md#edge--bane) for full list

**Edge Trading:**
- **Before rolling:** Trade Edge 1:1 to negate Complications
- Each Edge traded removes one Complication from this roll
- Roll with remaining Edge

**Bane (Disadvantage):**
- **1 Bane:** -1d from your pool
- **Maximum:** -3d (cap)
- Sources: Hard tasks, Very Hard tasks, Conditions, hostile environment, poor positioning, injuries
- See [core-foundations.md](core-foundations.md#edge--bane) for full list

**Minimum Pool:** If reduced to 0 dice or fewer, roll 1d6 (very low chance of success).

**Cancellation:** 
1. Edge and Bane cancel 1:1 (before you can trade Edge for Complications)
2. After cancellation, remaining Edge can be kept for dice OR traded for Complication negation

---

## Conditions (Penalty Details)

| Tier | Penalty |
|---|---|
| **Minor** | 1 Bane (-1d) to relevant rolls |
| **Moderate** | 2 Banes (-2d) to relevant rolls |
| **Severe** | 3 Banes (-3d) to relevant rolls, fictional restrictions |
| **Critical** | Cannot act in specific ways, may force Taken Out |

---

## Momentum Spends (Xd6 Effects)

**Gain an Edge (1 Momentum):** Add 1 Edge (+1d) to YOUR upcoming roll (before rolling). Can be kept for dice boost OR traded to negate Complication.

**Act with Potency (2 Momentum):** Gain Potency on this roll. Remove all Banes imposed by task difficulty (keep Banes from other sources like injuries, Conditions, environment). Attempt the impossible and achieve enhanced effects.

See [core-foundations.md](core-foundations.md#momentum-single-currency) for full Momentum spending options.

---

## Probability Tables

### Expected Outcomes (Count 5-6 as successes)

| Pool Size | Avg Hits | Setback % | Conflict % | Success % | Triumph % |
|-----------|----------|-----------|------------|-----------|-----------|
| 3d6 | 1.0 | 29.6% | 44.4% | 22.2% | 3.7% |
| 4d6 | 1.33 | 19.8% | 39.5% | 29.6% | 11.1% |
| 5d6 | 1.67 | 13.2% | 32.9% | 32.9% | 21.0% |
| 6d6 | 2.0 | 8.8% | 26.3% | 32.9% | 32.0% |
| 7d6 | 2.33 | 5.9% | 23.4% | 28.1% | 42.6% |

**Starting Character (Approach 3, baseline):**
- 3d6: 29.6% Setback, 44.4% Conflict, 22.2% Success, 3.7% Triumph
- Competent but facing frequent Conflicts

**With 1 Edge (Approach 3 + Edge from positioning/allies):**
- 4d6: 19.8% Setback, 39.5% Conflict, 29.6% Success, 11.1% Triumph
- More reliable, Triumphs more common

**Experienced Character (Approach 4 + 1 Edge = 5d6):**
- 13.2% Setback, 32.9% Conflict, 32.9% Success, 21.0% Triumph
- Success and Conflict roughly equal, Triumphs more common

**Heroic Character (Approach 4 + 2 Edges = 6d6):**
- 8.8% Setback, 26.3% Conflict, 32.9% Success, 32.0% Triumph
- Success/Triumph combined = 65%, setbacks rare

**Edge/Bane Impact:**
- Each Edge adds ~+1d (increases success rates significantly)
- Each Bane removes ~-1d (decreases success rates significantly)
- Multiple Edges/Banes stack additively

---

## Advancement Structure

**Starting Power Level:** 3d6 baseline (Approach 3)
- 29.6% Setback, 44.4% Conflict
- With 1 Edge (positioning/allies): 4d6 = 19.8% Setback

**Tier 1 (Early Game):** 3d6 → 4d6 baseline progression
- Increase Approach 3 → 4, gain situational Talents
- Target: 4d6 baseline pools (with Edge: 5d6)

**Tier 2 (Mid Game):** 5d6 → 6d6 progression
- Gain more Talents, increase secondary Approaches
- Target: 6d6 pools

**Tier 3 (Heroic Tier):** 6d6 → 7d6 progression
- Capstone Approach increases, powerful Talents
- Unlock Trait Invocation mechanics
- Target: 7d6 pools

**Maximum Recommended Pool:** 7d6 (represents legendary heroes)

---

## Design Notes

**Why Xd6 Count-Successes?**
- **Fixed target:** Always count 5-6 (33% per die), easy to remember
- **Modular difficulty:** GM grants Edge or imposes Bane, not changing target number
- **Granular outcomes:** Four tiers naturally emerge from counting hits
- **Dramatic feel:** Watching handfuls of dice creates kinetic excitement
- **Transparent probabilities:** Each die is an independent chance
- **Parallel to 2d10:** Both systems use Edge/Bane to modulate difficulty

**Advancement Runway:** 4d6 → 7d6 provides three clear tiers of progression. Triumph rates climb from 11% → 21% → 32% → 43%, making advancement feel transformative.

**Edge/Bane Impact:** Stacking keeps them powerful but not overwhelming. Going from 4d6 to 5d6 (1 Edge) increases Triumph chance from 11% to 21% — meaningful but not game-breaking.

---

## Quick Reference

**Always count 5s and 6s as successes**

**Typical Starting Roll:** 3d6 (Approach 3)
- 0 Hits = Setback (29.6%)
- 1 Hit = Conflict (44.4%)
- 2 Hits = Success (22.2%)
- 3+ Hits = Triumph (3.7%, gain 1 Momentum + ignore all Complications + choose Critical Bonus)

**With 1 Edge (positioning/allies/Momentum):** 4d6
- 0 Hits = Setback (19.8%)
- 1 Hit = Conflict (39.5%)
- 2 Hits = Success (29.6%)
- 3+ Hits = Triumph (11.1%)

**Spending Momentum for Edge:** Gain an Edge (1 Momentum) = add 1 Edge (+1d) before rolling (can keep for dice OR trade to negate Complication)

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

**Easy Tasks:** Grant 1 Edge (+1d)

**Hard Tasks:** Impose 1 Bane (-1d)

**Edge/Bane:** Cap ±3d, cancel 1:1 before trading
