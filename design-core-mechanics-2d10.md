# Heroic Fantasy RPG - Core Mechanics (2d10 Variant)

**Framework:** Custom 2d10+modifier hybrid (flat probability + PbtA narrative triggers + Fate Approaches)

**Design Philosophy:** This alternate system trades the dice pool's modular difficulty and counting overhead for faster resolution, wider numerical range, and longer advancement runway. It maintains the same five Actions, five Approaches, and Momentum economy, but shifts the "feel" from assembling pools to building modifiers.

---

## Resolution Mechanic

**2d10 + Approach + Trait vs. Static Thresholds**

Roll 2d10, add your Approach rating (1–4) and relevant Trait bonus (+0 to +2). Compare total to thresholds:

| Threshold | Outcome | Effect |
|-----------|---------|--------|
| **10 or less** | Failure | Things go wrong, situation worsens |
| **11–15** | Conflict | Partial success with cost, complication, or lesser effect |
| **16–20** | Success | You accomplish your intent cleanly |
| **21+** | Triumph | Success with added benefit (earn 1 Momentum) |

**Range:** 2d10 roll gives 2-20, modifiers add +2 to +6 (starting characters +2 with Edge, experienced +4 to +6)

**Expected Outcomes by Modifier (2d10):**

| Modifier | Conflict+ (11+) | Success+ (16+) | Triumph (21+) |
|----------|-----------------|----------------|---------------|
| +2 | 72% | 28% | 3% |
| +3 | 79% | 36% | 6% |
| +4 | 85% | 45% | 10% |
| +5 | 90% | 55% | 15% |
| +6 | 94% | 64% | 21% |

**Expected Outcomes with Edge (3d10 drop lowest):**

| Modifier | Conflict+ (11+) | Success+ (16+) | Triumph (21+) |
|----------|-----------------|----------------|---------------|
| +2 | 91.8% | 58.9% | 7.9% |
| +4 | 96.7% | 71.1% | 23.3% |
| +6 | 99.1% | 84.1% | 42.9% |

**Expected Outcomes with Double Edge (4d10 drop 2 lowest):**

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

**Design Note:** 2d10 creates a **triangular distribution** (flatter bell curve than 2d6), making extreme results more common than 2d6 but still clustering toward the middle. Edge dramatically improves consistency (raising Success+ rate) while modestly improving Triumph rate. Multiple Edge sources stack to maximum 4d10 drop 2.

---

## Actions (Fictional Triggers)

Actions are **PbtA-style move triggers**, not rated stats. When you take action in the fiction, identify which Action you're performing, then roll 2d10 + relevant Approach.

**The Five Actions:**

1. **Defy** — Overcome obstacles, resist harm, push through adversity, create advantages
2. **Clash** — Engage in combat, inflict harm, compete physically
3. **Talk** — Influence, persuade, deceive, negotiate, command
4. **Sense** — Observe, perceive, read intentions, discern weaknesses
5. **Know** — Recall lore, analyze situations, solve problems, understand magic

**Characters do not have Action ratings.** All Action-specific bonuses come from **Talents** (contextual, not universal). For example, a Talent might grant +1 when you Clash with a two-handed weapon, but not a blanket "+1 to all Clash rolls."

---

## Approaches (How You Act)

Approaches are your **rated stats** (1–4), describing your method. They add directly to your 2d10 roll.

- **Daring** — Bold, direct, forceful action
- **Grace** — Fluid, precise, finesse-driven action
- **Charm** — Warm, open, heart-led action
- **Cunning** — Clever, indirect, tactical action
- **Spirit** — Intuitive, resolute, spiritually-grounded action

**Starting Array:** Characters begin with Approaches at 2/1/1/0/-1 (assign as desired).

**Advancement:** Approaches can increase to 3 (exceptional) at mid-tier, or 4 (legendary) at heroic tier. Maximum: 4.

**Example:** When you Clash (the Action) in combat, you might use Daring (charging headlong), Grace (precise strikes), or Cunning (feinting and exploiting openings). Your modifier starts with that Approach rating.

---

## Traits (Provide Edge)

Traits represent expertise, background, or signature capabilities. Each character has 3–5 Traits.

**Mechanic:** When a Trait is narratively relevant, **gain Edge on your roll** (only one Trait per roll).

Edge = roll **3d10, drop lowest**, add your Approach modifier as normal.

**Examples:**
- "Veteran of the Iron Wars" (gain Edge when fighting soldiers or recalling military tactics)
- "Silver Tongue" (gain Edge when persuading nobility)
- "Shadowborn" (gain Edge when acting in darkness)

**Design Note:** Traits grant Edge rather than flat bonuses, making specialties feel dramatically more consistent. At Approach 2, having a relevant Trait shifts you from 72% Conflict+ / 28% Success+ → 91.8% Conflict+ / 58.9% Success+. Your specialty should feel like a major advantage, not just a modest +2.

---

## Edge & Bane (Advantage/Disadvantage)

**Edge** and **Bane** represent situational advantages and disadvantages. They stack to a maximum of +2 dice.

### Edge (Advantage)

**1 Edge:**
- Roll **3d10, drop lowest**, add modifiers as normal
- Costs **1 Momentum** if player-initiated (or granted by Trait, Talent, favorable positioning, ally assist, clever setup)

**2+ Edges:**
- Roll **4d10, drop 2 lowest**, add modifiers as normal
- Maximum benefit - additional Edges beyond 2 have no further effect
- Costs **2 Momentum** if player-initiated (or gained by stacking multiple Edge sources: Trait + ally assist, Trait + Momentum, etc.)

**Impact Examples (Approach 2):**
- Base 2d10+2: 72% Conflict+, 28% Success+, 3% Triumph
- 1 Edge (3d10 drop 1 +2): 91.8% Conflict+, 58.9% Success+, 7.9% Triumph
- 2 Edges (4d10 drop 2 +2): 97.01% Conflict+, 75.79% Success+, 13.91% Triumph

### Bane (Disadvantage)

**1 Bane:**
- Roll **3d10, drop highest**, add modifiers as normal
- Imposed by poor positioning, hostile environment, injuries, Conditions
- Can be negated by spending **1 Momentum**

**2+ Banes:**
- Roll **4d10, drop 2 highest**, add modifiers as normal
- Maximum penalty - additional Banes beyond 2 have no further effect
- Can be negated by spending **2 Momentum**

### Stacking & Cancellation

Edges and Banes cancel each other out before determining final dice pool:

- **1 Edge + 1 Bane** = cancel, roll 2d10 normally
- **2 Edge + 1 Bane** = 1 Edge remaining (3d10 drop lowest)
- **1 Edge + 2 Bane** = 1 Bane remaining (3d10 drop highest)
- **2 Edge + 2 Bane** = cancel, roll 2d10 normally
- **3+ Edge** = treated as 2 Edge (4d10 drop 2 lowest)
- **3+ Bane** = treated as 2 Bane (4d10 drop 2 highest)

**Design Note:** This system is simple - count Edges, count Banes, cancel 1:1, then roll the appropriate dice pool. No special tier-shift rules, just clean stacking to a cap of 2 additional dice. Multiple sources of Edge (Trait + Momentum + Talent) naturally stack together.

---

## Momentum (Single Currency)

Momentum is the primary player-facing metacurrency. It represents dramatic control, heroic momentum, and narrative leverage.

**Starting Momentum:** 2 (refreshes between sessions or at story beats)  
**Maximum Momentum:** 2 (can be increased to 3 with specific Talents)

### Earning Momentum

1. **Triumph (21+)** — Gain 1 Momentum
2. **Failure on Favored Action** — When you fail (10 or less) using an Action covered by one of your Talents, gain 1 Momentum (learning from failure)
3. **Accept a Complication** — GM offers a Complication (Bane); if you accept, gain 1 Momentum
4. **Create Advantages** — When you Defy to create an advantage for yourself or an ally, you may gain Momentum instead of inflicting harm or marking progress
5. **Discern Weakness** — When you Sense to discern a foe's weakness in combat, you may gain Momentum

### Spending Momentum

- **Edge (1 Momentum):** Gain 1 Edge on upcoming roll (before rolling). Stacks with Edge from other sources (Trait, Talents, situational).
- **Double Edge (2 Momentum):** Gain 2 Edges on upcoming roll (before rolling). If you already have 1 Edge (e.g., from Trait), this brings you to the 2-Edge cap (4d10 drop 2).
- **Increased Effect (1 Momentum):** Your success accomplishes more, affects a larger area, or has greater impact
- **Aid Ally (1 Momentum):** Grant 1 Edge to an ally's upcoming roll
- **Recover (2 Momentum):** Clear 1 Stress or reduce a Condition severity by one tier
- **Negate Bane (1 or 2 Momentum):** Cancel 1 Bane (1 Momentum) or 2 Banes (2 Momentum) before rolling

**Design Note:** Starting characters with Trait Edge (3d10 drop 1 +2) have 7.9% base Triumph. Spending 1 Momentum to add another Edge (4d10 drop 2 +2) increases to 13.91% Triumph — modest but meaningful. At higher Approaches (+4), Double Edge gives 36.68% Triumph. Momentum cap of 2 keeps spending tight.

---

## Stress & Conditions

### Stress (Unified Buffer)

Stress represents all harm — physical wounds, mental strain, social humiliation, spiritual corruption.

**Stress Track:** 4–5 boxes (determined by character build)

- When you suffer harm, mark Stress equal to the severity (1–3 boxes)
- **At maximum Stress:** You're Taken Out (unconscious, captured, defeated, broken)
- **Recovery:** Clear 1 Stress per rest scene; clear all Stress at end of session or downtime

### Conditions (Lasting Penalties)

When Stress overflows or specific narrative triggers occur, you gain a **Condition**. Conditions impose penalties to your 2d10 rolls:

| Tier | Penalty | Examples |
|---|---|---|
| **Minor** | -1 to relevant rolls | Bruised, Shaken, Embarrassed |
| **Moderate** | -2 to relevant rolls | Wounded, Rattled, Discredited |
| **Severe** | -3 to relevant rolls, fictional restrictions | Maimed, Traumatized, Exiled |
| **Critical** | Cannot act in specific ways, may force Taken Out | Dying, Broken, Cursed |

**Clearing Conditions:**
- Minor: Clear at end of scene or with rest
- Moderate: Requires dedicated recovery scene or spending 2 Momentum
- Severe: Requires extended downtime (days/weeks) or quest resolution
- Critical: Requires major story resolution

**Condition Escalation:** If you take harm while at maximum Stress, your existing Condition escalates one tier (Minor → Moderate → Severe → Critical).

**Design Note:** Conditions impose flat penalties (-1/-2/-3) rather than removing dice, making them mechanically simpler than the dice pool variant. A Moderate Condition (-2) is meaningful but survivable even for low-modifier characters (+3 becomes +1, still 64% Conflict+ chance).

---

## Talents (Character Abilities)

Talents are your special abilities, representing training, heritage, or supernatural gifts. Each character has 3–5 starting Talents (more gained through advancement).

**Design Philosophy:** Talents should NOT grant flat numeric bonuses (+1, +2) to avoid bonus bloat. Instead, they provide qualitative mechanical advantages.

**Types of Talents:**

1. **Failure Mitigation:** Convert bad outcomes to better ones
   - Example: "Bladedancer" — When you Clash with a sword and roll Failure, treat it as Conflict instead
   - Example: "Stubborn" — When you Defy and roll Conflict, you may choose to treat it as Success but mark 1 Stress
   
2. **Edge Grants:** Gain situational Edge (stacks with Trait Edge)
   - Example: "Ambush Predator" — Gain Edge when you Clash from stealth or surprise (if your Trait also applies, you have 2 Edges = 4d10 drop 2)
   - Example: "Combat Awareness" — Gain Edge when you Sense in combat to read enemy intentions
   
3. **Unique Moves:** Unlock new actions or special maneuvers
   - Example: "Whirlwind Strike" — When you Clash, you may target multiple adjacent foes (each defends separately)
   - Example: "Battlefield Awareness" — When you Sense in combat, you may grant an ally Edge on their next roll instead of gaining information
   
4. **Passive Effects:** Ongoing benefits or modifications
   - Example: "Iron Will" — You have +1 Stress box
   - Example: "Reserves of Strength" — Your maximum Momentum is 3 instead of 2
   
5. **Triggered Effects:** Activate in response to specific fiction
   - Example: "Parry and Riposte" — When an enemy misses you in melee (rolls Failure), you may immediately Clash against them with Edge
   - Example: "Capitalize on Weakness" — When you spend Momentum to Escalate an attack from Conflict to Success, deal +1 Harm

**Design Note:** Talents create mechanical differentiation through special abilities, not stacking bonuses. A character with "Bladedancer" (failure mitigation) + "Ambush Predator" (situational Edge grant) has multiple tactical options. When Trait Edge + Talent Edge stack, you reach 4d10 drop 2 — the maximum benefit.

---

## Framework Summary

| Element | Mechanical Role |
|---|---|
| **Actions** | Fictional triggers (what you're doing) — not rated |
| **Approaches** | Rated stats 1–4 (how you're doing it) — added to 2d10 roll |
| **Traits** | Grant Edge when relevant (narrative permission + 3d10 drop lowest) |
| **Talents** | Special abilities, Action bonuses, unique moves |
| **Momentum** | Single metacurrency (earn through success, failure, consequences; spend for Edge, recovery, narrative control) |
| **Edge/Bane** | Situational advantages/disadvantages (3d10 drop lowest/highest for 1, 4d10 drop 2 for 2+) |
| **Stress** | Unified harm buffer (4–5 boxes) |
| **Conditions** | Tiered lasting penalties (Minor -1 / Moderate -2 / Severe -3 / Critical cannot act) |

---

## Design Pillars (Maintained from Dice Pool Variant)

1. **Heroic fantasy with cost** — You can attempt the impossible, but nothing comes free
2. **Narrative-first resolution** — Fiction determines which Action/Approach applies, not optimization
3. **Elegant resource economy** — One primary currency (Momentum), one harm track (Stress), clean spend options
4. **Meaningful failure** — Failure drives drama and earns Momentum (when using Favored Actions)

---

## Comparison to Dice Pool Variant

### What 2d10 Gains

**Different Advancement Feel:**
- Dice pool: 4d6 → 7d6 (3 steps via Approach increases + Traits)
- 2d10: 3d10 drop 1 +2 → 4d10 drop 2 +4 (Approach increases + gaining more Edge sources)
- Progression through acquiring Talents that grant situational Edge, not higher base modifiers

**Faster Resolution:**
- No counting successes, no assembling pools
- Roll 2d10, add modifier, compare to thresholds
- Estimated 30-40% faster than dice pool counting

**Simpler Math:**
- Flat modifiers (+3, +4, +5) easier to calculate than variable pool sizes
- Conditions as flat penalties (-1, -2, -3) vs. removing dice

**More Dramatic Swings:**
- 2d10 has flatter bell curve than 2d6, creating more variance
- Extreme rolls (2-4 or 18-20) more common than 2d6
- Feels less predictable, more "anything can happen"

### What 2d10 Loses

**Modular Difficulty:**
- Dice pool: Easy/Moderate/Hard difficulties via target number changes (4+/5+/6+)
- 2d10: Static thresholds (11/16/21) with Edge/Bane for difficulty modulation
- Less GM control over challenge granularity

**Tangible Pool Assembly:**
- Some players enjoy physical act of gathering dice (Approach + Trait + Talents + Momentum)
- 2d10 still has pool assembly (2/3/4 d10s), but less modular than dice pool
- Trait grants Edge (adds dice) rather than +1d to existing pool

**Trait Integration:**
- Dice pool: +1d always relevant, scales naturally with pool size
- 2d10: Grants Edge (3d10 drop lowest), very powerful but less elegant
- Both systems have Traits add dice, but 2d10 Trait is more impactful (91.8% Conflict+ vs 85% with +1d to 4d6)

**Momentum Sustainability:**
- Dice pool: 11.11% Triumph with 1 Momentum boost (4d6 Moderate) = tight economy
- 2d10 with Trait Edge: 13.91% Triumph with 1 Momentum (4d10 drop 2 +2) = slightly looser
- Both systems have Momentum cap of 2 (3 with Talent), preventing hoarding
- 2d10 Triumph rate slightly higher when spending, but still under 15% at low Approaches

### Which to Choose?

**Choose Dice Pool (Xd6) if:**
- You want modular difficulty (Easy/Moderate/Hard as GM tool)
- You value tangible pool assembly (players like gathering dice)
- You want tighter Momentum economy (scarcity creates tension)
- You prefer bounded progression (4d6 → 7d6 feels heroic without scaling forever)

**Choose 2d10+X with Trait=Edge if:**
- You want starting characters to feel competent (91.8% Conflict+, 58.9% Success+)
- You want Edge stacking to be core mechanic (Trait + Momentum + Talents)
- You want simpler resolution (no target number changes, just count Edges/Banes)
- You want advancement through Talent acquisition (more Edge sources) rather than higher base modifiers
- You want dramatic moments when 4d10 drop 2 hits (36.68% Triumph at +4)

---

## Advancement Structure

**Starting Power Level:** 3d10 drop lowest +2 (Approach 2, Trait grants Edge)
- 91.8% Conflict+, 58.9% Success+, 7.9% Triumph
- Consistent and competent, rare Triumphs

**With Momentum or second Edge source:** 4d10 drop 2 +2
- 97.01% Conflict+, 75.79% Success+, 13.91% Triumph
- Very reliable, modest Triumph rate

**Tier 1 (Early Game):** Approach 2 → 3
- Gain Talents that grant situational Edge (stacks with Trait)
- When Trait + Talent both apply: 4d10 drop 2 +3
- 98.5% Conflict+, 82.7% Success+, 26.5% Triumph (estimate)

**Tier 2 (Mid Game):** Approach 3 → 4
- Increase secondary Approaches (1 → 2, 0 → 1)
- Gain more Talents (Edge grants, failure mitigation, unique moves)
- Common state: 3d10 drop 1 +4 (96.7% Conflict+, 71.1% Success+, 23.3% Triumph)
- With Talent Edge: 4d10 drop 2 +4 (99.19% Conflict+, 87.45% Success+, 36.68% Triumph)

**Tier 3 (Heroic Tier):** Approach 4 cap, powerful Talent combinations
- Focus on Talent acquisition: multiple Edge-granting Talents for different situations
- Characters feel powerful through consistent access to 4d10 drop 2, not higher modifiers
- Capstone state: 4d10 drop 2 +4 becomes achievable in most relevant situations

**Maximum Base Modifier:** +4 (Approach 4)
- Traits grant Edge (not flat bonus)
- Additional bonuses only via highly situational Talents, never baseline

**Design Note:** Progression is about gaining more situations where you have 2 Edges (4d10 drop 2), not about climbing to +6 or +7. A high-tier character with multiple Edge-granting Talents can achieve 4d10 drop 2 in many circumstances, making them feel heroic without breaking the math.

---

## GM Guidelines: Difficulty via Edge/Bane

Since thresholds are static (11/16/21), difficulty is modulated through Edge and Bane:

**Easy Task:**
- GM grants 1 Edge (player rolls 3d10 drop lowest)
- Use when: favorable conditions, player has clear advantage, task is within character's wheelhouse
- Example: Climbing a tree with good handholds in dry weather

**Standard Task:**
- No Edge or Bane (player rolls 2d10 normally)
- Use when: neutral conditions, fair challenge, typical adventuring difficulty
- Example: Tracking a creature through forest

**Hard Task:**
- GM imposes 1 Bane (player rolls 3d10 drop highest)
- Use when: unfavorable conditions, clear disadvantage, task pushes character limits
- Example: Negotiating with hostile noble while unarmed and injured

**Very Hard Task:**
- GM imposes 2 Bane = Double Bane (player rolls 2d10, shift tier down)
- Use when: nearly impossible, stacked disadvantages, desperation play
- Example: Leaping across rooftop gap while wounded, in storm, pursued

**Design Note:** This replaces the dice pool's Easy/Moderate/Hard target numbers (4+/5+/6+) with situational modifiers. It's less granular but faster to adjudicate ("does this situation favor the PC, hinder them, or neither?").

---

## Next Steps

- Define Archetypes or character creation framework
- Design sample Talents across all five Actions (adapted for flat modifiers)
- Establish GM guidelines for Edge/Bane assignment (when to impose/grant situational modifiers)
- Playtest Momentum economy (is 20% Triumph with Edge too generous?)
- Create combat structure (zones, initiative, progress clocks — identical to dice pool variant)
- Determine if static thresholds need adjustment (21+ for Triumph at high tiers?)
