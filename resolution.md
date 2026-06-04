# Resolution System

**Dice Pool Method:** Highest-die (Forged in the Dark inspired)

For shared foundational mechanics (Actions, Approaches, Momentum, Stress, Talents), see [core-foundations.md](core-foundations.md).

---

## Resolution Mechanic

**Roll Xd6, check the highest single die result (and look for double 6s).**

Your dice pool = Approach rating + Edge - Bane

### Difficulty & Edge/Bane

**Standard Difficulty:** Roll your pool and check results (no target number to remember).

**Easy Tasks:** Grant **1 Edge** (+1d to your pool)
- Task within character competence, conditions favor success
- Examples: Climbing a ladder with good handholds, persuading a friendly NPC, fighting distracted enemies

**Hard Tasks:** Impose **1 Bane** (-1d from your pool)
- Task at edge of capability, conditions work against success
- Examples: Leaping across a wide chasm, negotiating with hostile faction, fighting in pitch darkness

**Very Hard Tasks:** Impose **2 Banes** (-2d from your pool, maximum)
- Task at extreme difficulty, multiple unfavorable factors
- Requires Potency to attempt reliably

**GM Note:** Default to standard difficulty (no Edge or Bane). Use Edge when PCs have clear advantage. Reserve Bane for dramatic moments where conditions work against them. See [core-foundations.md](core-foundations.md#edge--bane) for all sources of Edge and Bane.

### Outcome Tiers

Check your dice results:

- **All 1-3:** Setback — Things go wrong, situation worsens
- **Any 4-5:** Conflict — Partial success with cost, consequence, or lesser effect
- **Any 6:** Success — You accomplish your intent cleanly
- **Two or more 6s:** Triumph — You accomplish your intent fully, gain 1 Momentum, ignore all Complications

**Key Principle:** Only the highest single die matters (except for double 6s triggering Triumph).

**Design Note:** This method feels fast and forgiving. Setbacks become rare past 3d6 (12.4% at 3d6, 6.2% at 4d6), creating a competent-hero feel from the start.

---

## Approaches

**Starting Array:** 3/2/1/0/0 (assign as desired)

**Advancement:** Can increase to 4 (exceptional) or 5 (legendary) at high tiers. Maximum: 5.

**Your dice pool starts with your Approach rating.**

**The Five Approaches:**
- **Daring** — Bold, direct, forceful action
- **Grace** — Agile, precise, elegant action
- **Charm** — Warm, personable, likable action
- **Cunning** — Clever, indirect, calculating action
- **Spirit** — Willful, passionate, determined action

---

## Traits

**Traits provide Special Effects when narratively relevant.**

When a Trait is narratively relevant to your action and you achieve **Conflict or higher**, you may invoke your Trait (after rolling) to gain a **Special Effect**:
- **Timing:** After rolling, when determining final outcome
- **If Conflict or higher:** Gain one Special Effect (Greater Effect, Secondary Effect, or Create Opportunity)
- **If Setback:** Cannot invoke Trait (you failed)
- **If Triumph:** You gain Momentum + ignore Complications + may invoke Trait for one Special Effect

**Special Effects:**
1. **Greater Effect** — Mark 2 ticks (instead of 1), ask 6 questions (instead of 2), or provide significantly more information
2. **Secondary Effect** — Produce additional consequence (Take Something, Inflict Condition, Affect Multiple Targets, etc.)
3. **Create an Opportunity** — Grant yourself or an ally 1 Edge OR negate 1 Complication for their next action

**See [traits-complications-challenges.md](traits-complications-challenges.md) for complete rules.**

---

## Edge & Bane

Edge and Bane represent advantage and disadvantage.

**Edge (Advantage):**
- **1 Edge:** +1d to your pool
- **Maximum:** +3d (cap)
- Sources: Easy tasks, Momentum, Talents, tactical positioning, ally assists, favorable environment, Know action
- See [core-foundations.md](core-foundations.md#edge--bane) for full list

**Bane (Disadvantage):**
- **1 Bane:** -1d from your pool
- **Maximum:** -3d (cap)
- Sources: Hard tasks, Very Hard tasks, Conditions, hostile environment, poor positioning, injuries
- See [core-foundations.md](core-foundations.md#edge--bane) for full list

**Minimum Pool:** If reduced to 0 dice, roll 2d6 and take the lowest result.

**Cancellation:** Edge and Bane cancel 1:1

**Design Note:** Edge/Bane affect **probability** (dice rolls). For outcome quality after rolling, Complications reduce tier. Negate Complications with Create an Opportunity, Act with Potency, or Talents. See [traits-complications-challenges.md](traits-complications-challenges.md).

---

## Conditions (Penalty Details)

| Tier | Penalty |
|---|---|
| **Minor** | 1 Bane (-1d) to relevant rolls |
| **Moderate** | 2 Banes (-2d) to relevant rolls |
| **Severe** | -3d to relevant rolls, fictional restrictions |
| **Critical** | Cannot act in specific ways, may force Taken Out |

**Note:** Severe Conditions exceed the normal ±3d Edge/Bane cap to represent truly debilitating injuries.

---

## Momentum

**Momentum Cap:** 2 (can be increased to 3 with specific Talent)

### Momentum Spends

**Act with Potency (1 Momentum):** Gain 1 Edge (+1d), ignore 1 Complication, and gain narrative permission for extraordinary feats (group actions, stretching limits, mystical feats).

See [core-foundations.md](core-foundations.md#momentum-single-currency) for full Momentum spending options.

---

## Probability Tables

### Expected Outcomes (Highest die + double 6s)

| Pool Size | Setback % | Conflict % | Success % | Triumph % |
|-----------|-----------|------------|-----------|-----------|
| 1d6 | 49.8% | 33.5% | 16.7% | 0.0% |
| 2d6 | 25.1% | 44.3% | 27.8% | 2.8% |
| 3d6 | 12.4% | 45.5% | 34.7% | 7.3% |
| 4d6 | 6.2% | 42.0% | 38.5% | 13.3% |
| 5d6 | 3.1% | 37.0% | 40.3% | 19.6% |
| 6d6 | 1.6% | 31.9% | 40.2% | 26.3% |
| 7d6 | 0.8% | 27.1% | 39.0% | 33.1% |

**Starting Character (Approach 3 = 3d6 base):**
- 12.4% Setback, 45.5% Conflict, 34.7% Success, 7.3% Triumph
- Competent with low setback rate from the start

**Experienced Character (Approach 4 = 4d6 base):**
- 6.2% Setback, 42.0% Conflict, 38.5% Success, 13.3% Triumph
- Reliable with setbacks becoming rare

**Heroic Character (Approach 5 = 5d6 base):**
- 3.1% Setback, 37.0% Conflict, 40.3% Success, 19.6% Triumph
- Success tier most common, setbacks very rare

**Legendary Character (Approach 5 + 2 Edges = 7d6):**
- 0.8% Setback, 27.1% Conflict, 39.0% Success, 33.1% Triumph
- Success/Triumph combined = 72%, catastrophic setback nearly impossible

**Edge/Bane Impact:**
- Each Edge significantly reduces setback chance (especially at low pools)
- Success tier remains consistent (38-40%) across most pool sizes
- Triumph rate grows but caps around 33% due to double-6 requirement

---

## Advancement Structure

**Starting Power Level:** 3d6 typical pool (Approach 3)
- Competent baseline: 12.4% setback rate

**Tier 1 (Early Game):** 3d6 → 4d6 progression
- Increase Approach 3 → 4, gain situational Talents
- Target: 4d6 pools (6.2% setback, 13.3% Triumph)

**Tier 2 (Mid Game):** 4d6 → 5d6 progression
- Increase Approach 4 → 5, gain more Talents
- Target: 5d6 pools (3.1% setback, 19.6% Triumph)

**Tier 3 (Heroic Tier):** 5d6 → 6d6+ progression
- Stack multiple Edge sources, powerful Talents
- Target: 6-7d6 pools (1.6-0.8% setback, 26-33% Triumph)

**Maximum Recommended Pool:** 7d6 (represents legendary heroes, Triumph caps around 33%)

---

## Design Principles

**Why This System?**
- **Fast resolution:** Look for highest die (and double 6s), no counting needed
- **Competent heroes:** Low setback rates (12.4% at 3d6) create capable characters from the start
- **Easier to assess:** Glance at dice, see highest result immediately
- **Success-focused:** Success tier (38-40%) is most common at higher pools
- **Traits provide options:** Free Special Effects on Conflict+ when narratively relevant

**Advancement Feel:**
- 3d6 → 4d6 is transformative (setback drops from 12.4% to 6.2%)
- 4d6 → 5d6 feels good (Triumph climbs from 13.3% to 19.6%)
- 5d6 → 6d6 → 7d6 has diminishing returns (Triumph only goes 19.6% → 26.3% → 33.1%)

---

## Quick Reference

**Roll Xd6, check highest die (and look for double 6s)**

**Typical Starting Roll:** 3d6 (Approach 3)
- All 1-3 = Setback (12.4%)
- Any 4-5 = Conflict (45.5%)
- Any 6 = Success (34.7%)
- Two+ 6s = Triumph (7.3%, gain 1 Momentum + ignore all Complications)

**Act with Potency (1 Momentum):** Gain 1 Edge (+1d), ignore 1 Complication, and gain narrative permission for extraordinary feats

**Using a Trait (after rolling):**
- When narratively relevant and outcome is Conflict+: Invoke for Special Effect
- If Setback: Cannot invoke Trait (you failed)

**Special Effects:**
1. Greater Effect (mark 2 ticks, ask 6 questions, or provide significantly more information)
2. Secondary Effect (Take Something, Inflict Condition, Affect Multiple Targets, etc.)
3. Create an Opportunity (grant yourself or ally 1 Edge OR negate 1 Complication for next action)

**Complications:**
- **Complication:** -1 tier (Triumph → Success → Conflict → Setback → Taken Out), unlimited
- Source: Challenge Traits (enemy defenses)
- Negate with: Create an Opportunity (grant 1 Edge OR negate 1 Complication), Act with Potency (ignore 1), Talents
- Triumph ignores all Complications

**Action Primary Effects:**
- Defy → Overcome: Mark Obstacle track or automatically overcome simple tasks
- Clash → Harm: Mark Harm track or outright defeat weaker foes
- Talk → Influence: Mark Accord track or outright convince lesser creatures
- Sense → Assess: Ask 2 questions (Success), 1 question (Conflict)
- Know → Recall: GM tells you something useful (Success)

**Easy Tasks:** Grant 1 Edge (+1d)

**Hard Tasks:** Impose 1 Bane (-1d)

**Very Hard Tasks:** Impose 2 Banes (-2d)

**Edge/Bane:** Cap ±3d, cancel 1:1, affect probability (not outcomes)

**Zero Dice:** If pool reduced to 0d, roll 2d6 and take lowest result
