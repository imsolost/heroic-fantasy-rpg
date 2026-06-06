# [Untitled Heroic Fantasy RPG] — Working Design Document
*Version 4 — Actions, Approaches, and probability analysis integrated*

---

## Design Pillars

1. **Heroic Scale** — PCs are exceptional, larger-than-life figures capable of feats well beyond ordinary people. Mechanics should reinforce this feeling without veering into superhero territory.
2. **Narrative First** — Closer to PbtA than D&D. Fiction drives the mechanics; mechanics shape the fiction. Rules exist to create drama, not simulate reality.
3. **Failure Drives Story** — Even failure is forward motion. There is no result that simply stops the narrative cold. Every outcome, including disaster, opens a new door.
4. **Momentum and Consequence** — Actions have weight in both directions. Success builds momentum; failure extracts a cost. The tension between the two is the engine of play.
5. **Elegant Simplicity** — Fewer, cleaner rules that do more work. Each mechanic must earn its place.

---

## Core Mechanical Framework

### Resolution — The Action Roll

When a character faces a risky, difficult, or dramatically significant situation, make an **Action Roll**.

**When to roll:** Only when an action is *difficult*, *dangerous*, or *dramatic*. Trivial actions and uncontested tasks do not require a roll.

**Building the dice pool:**

| Source | Dice Added |
|--------|-----------|
| Approach (rated 0–3) | 0–3d |
| Favored Action | +1d OR triggers Momentum-on-Failure (see Actions) |
| Trait (one per roll, player's choice) | +1d when narratively relevant |
| Momentum spend | +1d per token spent |

- Maximum pool size: **6d6**.
- If your pool would be **0 dice**, roll **2d6 and take the lowest** result.

**Reading the roll:**
- The GM sets a **Difficulty Number** for the roll: **4** (Easy), **5** (Moderate), or **6** (Hard).
- Each die that meets or exceeds the Difficulty Number counts as a **Hit**.
- Count your hits and consult the outcome table:

| Hits | Outcome | Description |
|------|---------|-------------|
| 0 | **Failure** | You fail and suffer a consequence. The story still moves forward. |
| 1 | **Conflict** | You succeed, but suffer a consequence. Success at a cost. |
| 2 | **Success** | You succeed cleanly, as intended. |
| 3+ | **Triumph** | You succeed with exceptional effect. Gain a Momentum token. |

> **Open Question:** Final outcome tier names TBD. Failure / Conflict / Success / Triumph are working terms.

---

### Probability Reference

Simulated at 100,000 trials. Use this to gut-check design decisions.

| Pool | Difficulty | Fail% | Conflict% | Success% | Triumph% |
|------|-----------|-------|-----------|----------|----------|
| 1d | Easy (4+) | 50 | 50 | 0 | 0 |
| 1d | Moderate (5+) | 67 | 33 | 0 | 0 |
| 1d | Hard (6+) | 83 | 17 | 0 | 0 |
| 2d | Easy | 25 | 50 | 25 | 0 |
| 2d | Moderate | 45 | 45 | 11 | 0 |
| 2d | Hard | 69 | 28 | 3 | 0 |
| 3d | Easy | 13 | 38 | 37 | 13 |
| 3d | Moderate | 30 | 45 | 22 | 4 |
| 3d | Hard | 58 | 35 | 7 | 0 |
| 4d | Easy | 6 | 25 | 37 | 31 |
| 4d | Moderate | 20 | 40 | 30 | 11 |
| 4d | Hard | 48 | 39 | 12 | 2 |
| 5d | Easy | 3 | 16 | 31 | 50 |
| 5d | Moderate | 13 | 33 | 33 | 21 |
| 5d | Hard | 40 | 40 | 16 | 4 |
| 6d | Easy | 2 | 9 | 24 | 66 |
| 6d | Moderate | 9 | 26 | 33 | 32 |
| 6d | Hard | 34 | 40 | 20 | 6 |

**Design notes from probability analysis:**
- **3d is the core sweet spot** — the range where play feels heroically tense. Most standard hero rolls in their area of competence should land here.
- **4d feels genuinely heroic** — Triumph becomes achievable (~31% at Easy), right for a character in their specialty.
- **5d+ is generous** — Triumph becomes routine at Easy difficulty (~50%). The Momentum cap of 2 exists specifically to prevent snowballing at this range.
- **1d is punishing** — appropriate for "I have no business doing this." The 0-dice floor (2d take lowest) is essential protection.
- **Hard difficulty should be reserved** for dramatically meaningful moments, not routine difficult tasks, given how punishing it is at small pool sizes.
- **Approach maximum of 3 is correct** — going to 4 would push too many rolls into the 5–6d range.

---

### Difficulty and Complications

The GM sets one of three difficulty tiers before the roll.

| Difficulty | Target Number | Typical Situation |
|------------|---------------|-------------------|
| Easy | 4+ | The task is challenging but within reach |
| Moderate | 5+ | The task is significantly harder than normal |
| Hard | 6+ | Only exceptional effort or skill will suffice |

**Complications** increase difficulty by raising the target number by +1 per complication. In severe cases — incapacitation, acting completely blind, fundamental inability — a Complication instead removes 1d from the pool. Complications cannot raise difficulty beyond 6, and cannot reduce the pool below the 0-dice floor.

**Sources of Complications:**
- *Intrinsic* — Scale of the task, opposing skill, numerical disadvantage
- *External* — Environmental or equipment factors
- *Intangible* — Emotional, informational, or supernatural factors
- *Conditions* — Active Conditions impose Complications (see Conditions)

**Opportunities negating Complications:** One available Opportunity spend is to negate an active Complication. One Opportunity negates one Complication, regardless of type.

---

### The Five Actions

Actions describe *what* a character is doing. There are five:

**DEFY** — Resist pressure, power through adversity, act under duress. Use when dodging, enduring, strongarming through an obstacle, or acting despite an imminent threat.

**CLASH** — Engage in combat or direct physical conflict, at range or up close. Use when exchanging blows, incapacitating with violence, or engaging in direct opposition.

**TALK** — Persuade, deceive, intimidate, perform, charm. Use when convincing someone to do something, using words or presence to get your way, or navigating social conflict.

**SENSE** — Read people and situations, perceive the world, trust instinct. Use when assessing a charged situation, noticing danger before it strikes, or reading someone's emotions and intent.

**KNOW** — Apply ingenuity, recall knowledge, figure things out. Use when recalling lore, solving problems, gathering information, or applying expertise.

**Favored Actions:**
Each character has **two Favored Actions** tied to their Archetype:
- **One grants +1d** on rolls using that Action (reliable competence).
- **One grants Momentum-on-Failure** — when you roll a Failure using this Action, gain a Momentum token (heroic adversity). This represents the warrior who turns defeat into fuel.

> **Design Note:** The two Favored Actions create a dual identity — what you're *reliably good at* and what you *fight hardest through*. These don't have to be the same Action.

---

### The Five Approaches

Approaches describe *how* a character acts. Rated **0–3**, they form the base of the dice pool.

**DARING** — Determination and steel in the face of danger. Forceful, aggressive, courageous.

**GRACE** — Elegance, poise, and agility. Precise, swift, controlled.

**CHARM** — Warmth, social presence, and force of personality. Empathic, magnetic, persuasive.

**CUNNING** — Wit, guile, and subterfuge. Clever, deceptive, analytical.

**SPIRIT** — Mental resolve, concentration, and inner strength. Focused, tenacious, willful.

**Starting distribution:** Two Approaches at 2, two at 1, one at 0.
**Maximum rating:** 3 (raised through milestone advancement).

> **Design Note:** This starting spread puts a hero at 3–4d in their strong areas when combined with Traits and Favored Actions — the core sweet spot identified by probability analysis.

---

### Traits

Traits are evocative narrative descriptors defining who your character is — their history, identity, reputation, and expertise. They are statements of fictional fact, not skill ratings.

**Examples:** *Cavalier Primary of House Erebus* / *Raised by wolves in the Ashen Wood* / *Former spymaster of the collapsed empire*

**At character creation:** 2–3 Traits.
**At higher tiers via milestone advancement:** up to 4–6 Traits.

**Mechanical function:**
- **Passive +1d** when a Trait is narratively relevant to the current roll. Only **one Trait** may apply per roll (player's choice).
- **At higher tiers**, Traits also unlock **Opportunity upgrades** within their domain — successes can be upgraded to stronger effects when a Trait applies.

> **Design Note:** Early-game Traits make you more *consistent*. Late-game Traits make your successes *mean more*. Traits growing through play mirrors the heroic arc of a character becoming who they are.

---

### Momentum — The Metacurrency

**Momentum** represents heroic drive, accumulated skill, and narrative weight behind a character in their element.

**Gaining Momentum:**
- Automatically on a **Triumph**.
- Via **Favored Action (Momentum-on-Failure)** — on a Failure using that specific Action.
- Possibly through specific Talents tied to adversity.

**Momentum Cap:** **2 tokens** by default. A Talent raises this to **3**.

> **Design Note:** The cap of 2 creates real spend pressure and prevents snowballing at large pool sizes (5–6d), where Triumph would otherwise generate Momentum faster than it can be spent.

**Spending Momentum:**
- Spend 1 Momentum to gain an **Opportunity** (see below).
- Spend 1 Momentum to clear 1–2 boxes of **Stress** in-scene (see Recovery).

> **Open Question:** Can Momentum be spent for a flat +1d directly, bypassing the Opportunity system? Keeping it Opportunities-only is more elegant but limits flexibility.

---

### Opportunities

An **Opportunity** is a beneficial effect chosen from the following menu. Gained by spending Momentum, on Triumph results, and through certain Talents.

**Opportunity Menu:**
- *Boost* — Add +1d to an upcoming roll
- *Free Hit* — Count one additional Hit on a roll already made
- *Narrative Impact* — Introduce a beneficial fact or circumstance into the scene (GM approves scope)
- *Aid an Ally* — The next roll by a chosen ally gains +1d or negates a Complication
- *Recover* — Clear a Minor Condition or 1–2 boxes of Stress
- *Negate a Complication* — Cancel one active Complication

> **Open Question:** Should *Free Hit* be a baseline Opportunity option for all characters, or gated behind high-tier Traits or Talents? It bypasses probability entirely and may feel too powerful at early tiers.

---

### Working Together

**Assist:** Help another PC on their roll. Describe how, roll 1d, share the risk. Your result factors into the final outcome — you are exposed to consequences alongside them.

**Setup:** A previous action makes a follow-up more effective. Roll 1d as normal assist; consequences don't apply to you. If setting up your own follow-up, take +1d on that action.

**Teamwork:** When 3+ PCs act together, the GM determines who rolls. All others Assist.

**Outside Assistance:** When help comes from an NPC or environmental factor, the GM rolls 1d to represent it.

---

## Stress and Conditions

### Stress

**Stress** is the primary resilience track — a unified buffer absorbing all incoming costs: physical blows, emotional strain, exertion, fear, and any other consequence the fiction demands.

**Starting Stress boxes:** 4–5 (exact number TBD; may vary by Archetype).

**Marking Stress:**
- When you suffer harm of any kind, you may mark Stress to absorb it.
- The GM may require Stress as the cost of certain actions, abilities, or consequences.
- When your Stress track is full and you must mark Stress, you instead take a **Condition**.
- A character with a full Stress track who cannot take a Condition faces a **Death Move**.

---

### Conditions

Conditions are lasting penalties representing something actually *breaking* rather than being absorbed. The fiction determines the *type* of Condition; the severity tier is fixed and determines mechanical weight.

**Condition Severity Tiers:**

| Tier | Mechanical Effect | Example Names |
|------|-----------------|---------------|
| **Minor** | +1 Complication on relevant rolls | *Bruised, Rattled, Winded, Shaken* |
| **Moderate** | +1 Complication on all rolls | *Bloodied, Frightened, Exhausted, Dazed* |
| **Severe** | +2 Complications on all rolls | *Injured, Broken, Overwhelmed, Haunted* |
| **Critical** | Triggers the Death Move | *Incapacitated, Defeated* |

**Naming Conditions:** The GM and player name the Condition based on the fiction. The source determines the type — a sword blow produces a physical Condition (*Bloodied*); a psychic assault produces a mental one (*Shaken*); a public humiliation might produce a social one (*Disgraced*). The name is narrative; the tier is mechanical.

**Condition escalation:** When a character already has a Condition and would take another of the same *type*, the existing Condition escalates to the next severity tier rather than adding a new one.

> **Example:** A character who is *Bloodied* (Moderate/physical) takes another physical hit they can't absorb with Stress. *Bloodied* escalates to *Injured* (Severe).

> **Open Question:** Maximum simultaneous Conditions across different types needs a defined ceiling. A character could theoretically hold one physical, one mental, and one social Condition — potentially +4 Complications before the Death Move triggers. A hard ceiling of 2–3 simultaneous Conditions is recommended.

---

### Recovery

**In-scene recovery:**
- Spend 1 Momentum to clear 1–2 boxes of Stress.
- Certain Talents allow in-scene Stress recovery without Momentum.
- **Minor Conditions** can be cleared in-scene through appropriate fictional action (catching your breath, a quick bandage, a rallying word from an ally) — no roll required, but needs a moment and narrative justification.

**Downtime recovery:**
- All Stress clears fully during downtime/rest.
- **Moderate Conditions** require downtime and a recovery action (rest, treatment, emotional processing).
- **Severe Conditions** require downtime plus a specific recovery move or resource (a healer, a safe haven, significant time).

---

### The Death Move

When a character would take a Critical Condition and has no remaining capacity to absorb it, they face the **Death Move**.

- The player rolls their current dice pool (accounting for all active Conditions and Complications).
- **Success or Triumph:** The character survives. They are *Incapacitated* and out of the scene, but wake later scarred and alive.
- **Conflict:** The character survives, but must choose — take a **permanent Condition** (a lasting scar, a missing limb, a shattered psyche) or be taken out with a cost the GM defines.
- **Failure:** The character dies, or faces a fate as bad as death. The player narrates the final moment.

> **Design Note:** The Conflict option — survive at permanent cost — is particularly fitting for heroic fantasy, where scars tell stories and characters are defined by what they've endured.

---

## Character Framework

### Archetypes

Characters are built on an **Archetype** — a loose chassis defining general role, starting Talents, Favored Actions, and suggested Approach spread. Archetypes are starting points, not cages.

**Character creation provides:**
- Choice of Archetype (starting Talents, two Favored Actions)
- Approach ratings: two at 2, two at 1, one at 0
- 2–3 Traits (player-written, GM-approved)
- Starting Stress: 4–5 boxes (possibly Archetype-dependent)
- Starting Momentum cap: 2

> **Open Question:** Archetype list TBD. Should have evocative, tone-appropriate names. Likely 4–6 Archetypes at launch.

---

### Advancement — Milestones

Characters advance when the story reaches a **Milestone** — a significant narrative beat such as completing a major quest, resolving a personal arc, or defeating a powerful antagonist.

**At a Milestone, a character may choose one:**
- Gain a new Talent
- Raise one Approach rating by 1 (maximum 3)
- Write a new Trait (growing from 2–3 toward 4–6 over time)
- Raise Momentum cap from 2 to 3 (requires specific Talent)
- Gain an additional Stress box (maximum TBD)

---

## Consequences

Consequences occur on **Failure** and **Conflict** results, and occasionally on **Success** when narratively appropriate.

**Consequence Types:**
- **Stress** — Mark 1–3 Stress boxes depending on severity.
- **Condition** — Take a named Condition at an appropriate tier.
- **Reduced Effect** — Your action works, but achieves less than intended.
- **Complication** — A new problem emerges. Tick a clock or track.
- **Escalated Risk** — Future related rolls become harder.
- **Lost Opportunity** — Your approach didn't work; try something else.

> **Open Question:** Should certain outcome tiers have default consequence types to reduce GM overhead while preserving flexibility?

---

## Combat *(Placeholder)*

Combat uses the same Action Roll system. Named maneuver types worth encoding as Talent options or Opportunity effects:

- **Disarm** — Remove an enemy's weapon
- **Knockdown** — Put an enemy on the ground
- **Pin Down** — Restrict movement or action
- **Pull / Push** — Reposition an enemy
- **Sunder** — Damage gear to reduce effectiveness

**Enemy Stat Block (working template):**

| Field | Description |
|-------|-------------|
| **Danger** | Threat level (1–3+); informs consequence severity |
| **Difficulty** | Target number for rolls against this foe |
| **Resolve** | Enemy Stress track — how much punishment before they're taken out |
| **Approaches** | Which Approaches the enemy uses; relevant to Edge Negation (Talent) |
| **Traits** | Passive abilities (e.g. *Thick Hide — Resist 1*) |
| **Reactions** | Triggered abilities (e.g. *Sweep — 1 Stress to all engaged foes*) |

**Example:**

> **Troll**
> Danger: 2 / Difficulty: Moderate (5+) / Resolve: 3
> Traits: *Thick Hide* — Reduce incoming Stress by 1
> Reactions: *Regeneration* — Recover 1 Resolve at end of round; *Sweep* — 1 Stress to all engaged foes

---

## GM Tools

### Clocks and Tracks

Segmented progress indicators representing ongoing situations, threats, and effort.

**Clock types:**
- *Countdown Clocks* — Something bad happens when this fills.
- *Progress Tracks* — PCs fill this through effort.
- *Threat Clocks* — A threat grows more dangerous over time.

**Diminishing Pools** (alternative): Roll a pool of dice; drop dice on low results. When the pool empties, something changes. Use when dramatic unpredictability matters more than a steady march.

### Consequences as GM Moves

When a roll produces a consequence, the GM narrates it as a *move* — an action the world takes in response. Consequences should always make the fiction more interesting, open new problems, and be proportional to the risk of the roll.

**Consequence menu for GM reference:**

*The character is hurt:* An NPC attacks them / They fall unconscious / They become cursed or diseased

*Their standing is harmed:* They offend someone / They break the law / They lose an ally

*They lose something:* An item is stolen or lost / An item breaks / A costly demand is made

*The environment shifts:* A storm makes travel difficult / A disaster strikes / A mishap creates an impasse

*Their enemies advance:* A villain gains power / An ally loses resources / Danger spreads

**Tough choices** (for Conflict results — offer two equally undesirable consequences):
- Deal reduced effect or mark Stress
- Take a Condition or lose/break an item
- Betray a friend or make an enemy
- Retreat to safety or sacrifice the town
- Save one ally but not another

---

## Talents *(Placeholder)*

Talents are discrete mechanical abilities that modify how the base rules apply to your character. They change *how* you interact with the system, not just add flat bonuses.

**Talent types identified so far:**
- Raise Momentum cap from 2 to 3
- Grant Momentum-on-Failure for a specific Action
- Allow in-scene Stress recovery without Momentum spend
- **Edge Negation** *(Talent option, not baseline rule)* — When your foe shares your Approach, you may still benefit from it; or, alternatively, when you share your foe's Approach, they cannot benefit from theirs.
- Ignore a category of Complication (e.g. speed-based Complications when mounted)
- Unlock additional Opportunity effects within a Trait's domain

> **Open Question:** Full Talent list TBD. Talents are the primary customization layer within Archetypes and the main reward of milestone advancement.

---

## Open Questions (Master List)

1. **Outcome tier names** — Failure / Conflict / Success / Triumph are working terms.
2. **Favored Action mechanic** — Confirmed: two Favored Actions per character (one +1d, one Momentum-on-Failure). Archetype determines starting pair; advancement may allow changes.
3. **Opportunity: Free Hit gating** — Baseline or high-tier unlock?
4. **Momentum spend** — Opportunities + Stress recovery confirmed. Direct +1d still open.
5. **Archetype list** — Names and chassis TBD (4–6 Archetypes).
6. **Stress box count** — Fixed 4–5, or Archetype-dependent?
7. **Maximum simultaneous Conditions** — Needs a defined ceiling (recommendation: 2–3).
8. **Default consequence types per outcome tier** — Free GM choice vs. guided defaults.
9. **Clock vs. Pool guidance** — When does each apply?
10. **Full Talent list** — TBD; primary customization layer.
11. **Trait tier transition point** — At what milestone do Traits shift from +1d to Opportunity upgrades?

---

## Flagged Concerns

- ⚠️ **Hard difficulty at small pools** — Reserve Hard (6+) for dramatically meaningful moments. At 1–2d it approaches near-certain failure.
- ⚠️ **5d+ Triumph frequency** — At 5d Easy, Triumph occurs ~50% of the time. Momentum cap of 2 is essential at this range.
- ⚠️ **Momentum snowball** — Cap confirmed at 2 (3 via Talent). Monitor during playtesting.
- ⚠️ **Condition stacking** — Without a ceiling, multiple simultaneous Conditions across types could create extreme Complication counts before Death Move triggers.
- ⚠️ **Death Move pool degradation** — At Critical tier, active Conditions will significantly reduce the pool. Confirm the Death Move feels tense but survivable at heroic scale.
- ⚠️ **Trait +1d at 5–6d pools** — At max pool sizes, adding +1d from a Trait has diminishing value (already hitting Triumph ~50–66% at Easy). The Opportunity upgrade shift at higher tiers needs a clear trigger point.

---

## Design Snapshot

```
=== DESIGN SNAPSHOT ===
Game: [Untitled Heroic Fantasy RPG]
Version: 4
Last updated: Actions, Approaches, and probability analysis integrated

PILLARS:
1. Heroic Scale — exceptional PCs, not superheroes
2. Narrative First — PbtA-adjacent, fiction drives mechanics
3. Failure Drives Story — all outcomes are forward motion
4. Momentum and Consequence — actions have weight in both directions
5. Elegant Simplicity — fewer, cleaner rules

LOCKED DECISIONS:
- Resolution: Roll Xd6 vs. difficulty number (4/5/6); count hits
- Outcomes: 0=Failure, 1=Conflict, 2=Success, 3+=Triumph
- Max pool: 6d6; 0-pool: roll 2d6 take lowest; Approach max: 3
- Dice pool: Approach (0–3d) + Favored Action + Trait (+1d, one per roll) + Momentum
- Approach starting distribution: two at 2, two at 1, one at 0
- Five Actions: Defy / Clash / Talk / Sense / Know (locked)
- Five Approaches: Daring / Grace / Charm / Cunning / Spirit (locked)
- Two Favored Actions per character: one +1d, one Momentum-on-Failure
- Complications raise difficulty +1 (default) or reduce pool 1d (severe)
- Opportunities negate Complications (one for one)
- Metacurrency: Momentum — cap 2 (raised to 3 via Talent)
- Momentum gained on Triumph; on Failure via Favored Action (Momentum-on-Failure)
- Momentum spent for Opportunities or in-scene Stress recovery
- Teamwork: Assist (share risk), Setup (no risk), Teamwork (GM picks roller)
- Traits: 2–3 at creation → 4–6 via milestones; +1d (one per roll); Opportunity upgrades at higher tiers
- Advancement: Milestone-based
- Character building: Archetype + customization
- Edge Negation: Talent option, not baseline rule
- Enemy stat block: Danger / Difficulty / Resolve / Approaches / Traits / Reactions
- GM tools: Clocks (default), Diminishing Pools (situational)

STRESS AND CONDITIONS (locked):
- Stress: unified buffer, 4–5 boxes, absorbs all harm
- Full Stress → take Condition instead
- Conditions: four tiers (Minor/Moderate/Severe/Critical), fiction-named, escalate on repeat hits
- Minor: +1 Complication relevant rolls, clear in-scene
- Moderate: +1 Complication all rolls, clear on downtime
- Severe: +2 Complications all rolls, clear with downtime + specific recovery
- Critical → Death Move (Success=survive, Conflict=survive+permanent cost, Failure=death)
- Recovery: Minor + Stress clear in-scene; all Stress + Moderate+ on downtime

OPEN QUESTIONS:
1. Outcome tier names
2. Free Hit: baseline or high-tier Opportunity?
3. Momentum: direct +1d or Opportunities-only?
4. Archetype list (4–6, names TBD)
5. Stress box count: fixed or Archetype-dependent?
6. Maximum simultaneous Conditions (recommend 2–3 ceiling)
7. Default consequence types per outcome tier
8. Clock vs. Pool guidance
9. Full Talent list
10. Trait tier transition point (when does +1d shift to Opportunity upgrades?)

FLAGGED CONCERNS:
- Hard difficulty at small pools (reserve for dramatic moments)
- 5d+ Triumph frequency (cap essential)
- Condition stacking ceiling needed
- Death Move survivability
- Trait +1d diminishing value at max pool sizes

NEXT STEPS:
- Review remaining reference documents
- Begin Archetype design
- Resolve Condition stacking ceiling
- Determine Talent design principles
=== END SNAPSHOT ===
```
