# Heroic Fantasy RPG - Core Mechanics

**Framework:** Custom dice pool hybrid (FitD tiered outcomes + PbtA narrative triggers + Fate Approaches)

---

## Resolution Mechanic

**Dice Pool: Xd6 count successes**

Roll a pool of d6s equal to your Approach rating (0–3d) + modifiers. Count successes based on difficulty:

| Difficulty | Success on... | Hit Rate per Die |
|---|---|---|
| **Easy** | 4, 5, 6 | 50% |
| **Moderate** | 5, 6 | 33% (most common) |
| **Hard** | 6 only | 16.67% |

**Outcome Tiers (count Hits):**

- **0 Hits:** Failure — Things go wrong, situation worsens
- **1 Hit:** Conflict — Partial success with cost, complication, or lesser effect
- **2 Hits:** Success — You accomplish your intent
- **3+ Hits:** Triumph — Success with added benefit (earn 1 Momentum)

**Expected Outcomes at Moderate Difficulty:**

| Pool Size | Avg Hits | Failure % | Conflict % | Success % | Triumph % |
|-----------|----------|-----------|------------|-----------|-----------|
| 3d6 | 1.0 | 29.6% | 44.4% | 22.2% | 3.7% |
| 4d6 | 1.33 | 19.8% | 39.5% | 29.6% | 11.1% |
| 5d6 | 1.67 | 13.2% | 32.9% | 32.9% | 21.0% |
| 6d6 | 2.0 | 8.8% | 26.3% | 32.9% | 32.0% |

**Design Note:** Moderate difficulty creates a gritty feel where starting characters (3d6) face frequent Conflicts (44%) and rare Triumphs (3.7%). Advancement from 4d6 → 6d6 feels transformative as Triumph rates climb from 11% to 32%.

---

## Actions (Fictional Triggers)

Actions are **PbtA-style move triggers**, not rated stats. When you take action in the fiction, identify which Action you're performing, then roll using the appropriate Approach.

**The Five Actions:**

1. **Defy** — Overcome obstacles, resist harm, push through adversity, create advantages
2. **Clash** — Engage in combat, inflict harm, compete physically
3. **Talk** — Influence, persuade, deceive, negotiate, command
4. **Sense** — Observe, perceive, read intentions, discern weaknesses
5. **Know** — Recall lore, analyze situations, solve problems, understand magic

**Characters do not have Action ratings.** All Action-specific bonuses come from **Talents** (contextual, not universal). For example, a Talent might grant +1d when you Clash with a two-handed weapon, but not a blanket "+1d to all Clash rolls."

---

## Approaches (How You Act)

Approaches are your **rated stats** (1–4), describing your method:

- **Daring** — Bold, direct, forceful action
- **Grace** — Fluid, precise, finesse-driven action
- **Charm** — Warm, open, heart-led action
- **Cunning** — Clever, indirect, tactical action
- **Spirit** — Intuitive, resolute, spiritually-grounded action

When you make an Action roll, choose the Approach that describes **how** you're acting. Your dice pool starts at your Approach rating.

**Starting Array:** Characters begin with Approaches at 3/2/2/2/1 (assign as desired).

**Example:** When you Clash (the Action) in combat, you might use Daring (charging headlong), Grace (precise strikes), or Cunning (feinting and exploiting openings).

**Advancement:** Approaches can increase to a maximum of 4 (exceptional) or 5 (legendary) at high tiers.

---

## Traits (Passive Bonus)

Traits represent expertise, background, or signature capabilities. Each character has 3–5 Traits.

**Mechanic:** When a Trait is narratively relevant, add **+1d** to your roll (only one Trait per roll).

**Examples:**
- "Veteran of the Iron Wars" (+1d when fighting soldiers or recalling military tactics)
- "Silver Tongue" (+1d when persuading nobility)
- "Shadowborn" (+1d when acting in darkness)

**Design Note:** Traits currently grant passive +1d. At higher tiers of play, we may evolve Traits to allow **Invocation** (spending Momentum for special effects) similar to Fate Aspects or Daggerheart Experiences.

---

## Momentum (Single Currency)

Momentum is the primary player-facing metacurrency. It represents dramatic control, heroic momentum, and narrative leverage.

**Starting Momentum:** 2 (refreshes between sessions or at story beats)

### Earning Momentum

1. **Triumph (3+ Hits)** — Gain 1 Momentum
2. **Failure on Favored Action** — When you fail (0 Hits) using an Action covered by one of your Talents, gain 1 Momentum (learning from failure)
3. **Accept a Complication** — GM offers a Complication; if you accept, gain 1 Momentum
4. **Create Advantages** — When you Defy to create an advantage for yourself or an ally, you may gain Momentum instead of inflicting harm or marking progress
5. **Discern Weakness** — When you Sense to discern a foe's weakness in combat, you may gain Momentum

### Spending Momentum

- **Boost (1/2/3 Momentum):** Add +1d to an upcoming roll (before rolling). First boost costs 1, second costs 2, third costs 3 (max +3d per roll, total 6 Momentum).
- **Escalate (2 Momentum):** After rolling, shift your outcome tier up one step (Failure → Conflict, Conflict → Success, Success → Triumph)
- **Increased Effect (1 Momentum):** Your success accomplishes more, affects a larger area, or has greater impact
- **Aid Ally (1 Momentum):** Grant +1d to an ally's upcoming roll
- **Recover (2 Momentum):** Clear 1 Stress or reduce a Condition severity by one tier
- **Negate Complication (1 Momentum):** Cancel a Complication before it takes effect
- **Invoke Trait (Cost TBD, Tier 3+ only):** Use a Trait for a special effect beyond +1d (future design space)

**Design Note:** Escalating Boost costs (1/2/3) create meaningful "how confident am I?" decisions. Spending 6 Momentum for +3d is desperate and expensive, but occasionally necessary.

---

## Opportunities & Complications

**Opportunities** and **Complications** are **situational modifiers**, not tradable currency. Each one adds or removes dice from your pool.

**Opportunities (Advantage):**
- **1 Opportunity:** +1d to your roll
- **2 Opportunities:** +2d to your roll
- Triggered by: favorable positioning, environmental advantage, clever setup, ally assists, GM reward for good roleplay
- Opportunities stack — multiple sources each add +1d
- Not spent or traded — they apply when the fiction supports them

**Complications (Disadvantage):**
- **1 Complication:** -1d from your roll
- **2 Complications:** -2d from your roll
- Triggered by: poor positioning, hostile environment, injuries, fictional consequences, Conditions
- Complications stack — multiple sources each remove -1d
- Can be negated by spending 1 Momentum per Complication

**Cancellation:** Opportunities and Complications cancel each other 1:1 before applying to your pool.

**Design Note:** This stacking model keeps Opportunities/Complications powerful but not overwhelming. Going from 4d6 to 5d6 (1 Opportunity) increases Triumph chance from 11% to 21% — meaningful but not game-breaking. Compare to 2d6+X systems where a single Advantage can increase Triumph from 8% to 40%.

---

## Stress & Conditions

### Stress (Unified Buffer)

Stress represents all harm — physical wounds, mental strain, social humiliation, spiritual corruption.

**Stress Track:** 4–5 boxes (determined by character build)

- When you suffer harm, mark Stress equal to the severity (1–3 boxes)
- **At maximum Stress:** You're Taken Out (unconscious, captured, defeated, broken)
- **Recovery:** Clear 1 Stress per rest scene; clear all Stress at end of session or downtime

### Conditions (Lasting Penalties)

When Stress overflows or specific narrative triggers occur, you gain a **Condition**. Conditions are tiered, escalating penalties:

| Tier | Penalty | Examples |
|---|---|---|
| **Minor** | -1d to relevant rolls | Bruised, Shaken, Embarrassed |
| **Moderate** | -2d to relevant rolls | Wounded, Rattled, Discredited |
| **Severe** | -3d to relevant rolls, fictional restrictions | Maimed, Traumatized, Exiled |
| **Critical** | Cannot act in specific ways, may force Taken Out | Dying, Broken, Cursed |

**Clearing Conditions:**
- Minor: Clear at end of scene or with rest
- Moderate: Requires dedicated recovery scene or spending 2 Momentum
- Severe: Requires extended downtime (days/weeks) or quest resolution
- Critical: Requires major story resolution

**Condition Escalation:** If you take harm while at maximum Stress, your existing Condition escalates one tier (Minor → Moderate → Severe → Critical).

---

## Talents (Character Abilities)

Talents are your special abilities, representing training, heritage, or supernatural gifts. Each character has 3–5 starting Talents (more gained through advancement).

**Types of Talents:**

1. **Favored Actions:** Grant +1d or +2d when using a specific Action in specific circumstances
   - Example: "Bladedancer" — +1d when you Clash with a sword in melee
2. **Unique Moves:** Unlock new actions or special maneuvers
   - Example: "Whirlwind Strike" — When you Clash, you may target multiple adjacent foes
3. **Passive Effects:** Ongoing benefits or modifications
   - Example: "Iron Will" — You have +1 Stress box
4. **Triggered Effects:** Activate in response to specific fiction
   - Example: "Parry and Riposte" — When an enemy misses you in melee, you may immediately Clash against them

**Design Note:** All Action-specific bonuses come from Talents. There are no universal "+1d to Clash" character builds — all bonuses are contextual (weapon type, situation, enemy type, etc.).

---

## Framework Summary

| Element | Mechanical Role |
|---|---|
| **Actions** | Fictional triggers (what you're doing) — not rated |
| **Approaches** | Rated stats 0–3 (how you're doing it) — determines base dice pool |
| **Traits** | Passive +1d when relevant (narrative permission + mechanical boost) |
| **Talents** | Special abilities, Action bonuses, unique moves |
| **Momentum** | Single metacurrency (earn through success, failure, consequences; spend for boosts, recovery, narrative control) |
| **Opportunities/Complications** | Situational bonuses/penalties (not currency) |
| **Stress** | Unified harm buffer (4–5 boxes) |
| **Conditions** | Tiered lasting penalties (Minor/Moderate/Severe/Critical) |

---

## Design Pillars (In Progress)

1. **Heroic fantasy with cost** — You can attempt the impossible, but nothing comes free
2. **Narrative-first resolution** — Fiction determines which Action/Approach applies, not optimization
3. **Elegant resource economy** — One primary currency (Momentum), one harm track (Stress), clean spend options
4. **Meaningful failure** — Failure drives drama and earns Momentum (when using Favored Actions)

---

## Open Questions

1. **Archetypes:** How do we structure character creation? Playbooks? Class-like frameworks? Free-form Talent selection?
2. **Advancement:** What does progression look like? Increase Approaches? Gain new Talents? Unlock Trait Invocation?
3. **GM Tools:** What structure do we provide GMs for setting Difficulty, offering Complications, pacing Momentum?
4. **Magic System:** Is magic a separate subsystem, or integrated through Talents and the Know Action?
5. **Combat Structure:** Turn-based? Zone-based positioning? How do we handle initiative, multiple combatants, progress clocks?

---

## Advancement Structure

**Starting Power Level:** 4d6 typical pool (Approach 3 + Trait)
- 19.8% Failure, 39.5% Conflict, 29.6% Success, 11.1% Triumph at Moderate difficulty
- Competent but still facing frequent costs/complications

**Tier 1 (Early Game):** 4d6 → 5d6 progression
- Increase Approach 3 → 4, gain situational Talents for +1d
- Target: 5d6 pools (13.2% Failure, 32.9% Conflict, 32.9% Success, 21.0% Triumph)

**Tier 2 (Mid Game):** 5d6 → 6d6 progression
- Gain more Talents, increase secondary Approaches
- Target: 6d6 pools (8.8% Failure, 26.3% Conflict, 32.9% Success, 32.0% Triumph)

**Tier 3 (Heroic Tier):** 6d6 → 7d6 progression
- Capstone Approach increases, powerful Talents
- Unlock Trait Invocation mechanics
- Target: 7d6 pools (5.9% Failure, 23.4% Conflict, 28.1% Success, 42.6% Triumph)

**Maximum Recommended Pool:** 7d6 (represents legendary heroes)

---

## Next Steps

- Define Archetypes or character creation framework
- Design sample Talents across all five Actions
- Establish GM guidelines (Difficulty setting, Complication offers, Momentum pacing)
- Flesh out magic system (if distinct from Talents)
- Create combat structure (zones, initiative, progress clocks)
- Playtest core resolution with sample characters
