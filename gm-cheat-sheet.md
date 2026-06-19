# GM Cheat Sheet

Quick reference for running the game. For complete rules, see the full chapters.

---

## Action Resolution (Quick Flow)

### 1. Player Declares Intent
"What do you do?" → Player describes action + goal

### 2. GM Telegraphs Stakes
- **Action:** Which of the 5 Actions? (Clash, Defy, Talk, Sense, Know)
- **Difficulty:** Easy (+1d Edge), Standard (no mod), Hard (-1d Bane), Very Hard (-2d Bane)
- **Complications:** List any Challenge Traits that apply (each reduces outcome by 1 tier)
- **Consequences:** "On Setback, [X happens]. On Conflict, [Y happens]."

### 3. Roll & Resolve
**Player rolls Approach + Action dice → Apply Complications → Apply Expertise (if any) → Resolve outcome**

| Outcome | Effect |
|---------|--------|
| **Triumph** (two 6s) | Full success + 1 Momentum + ignore Complications + may invoke Trait |
| **Success** (one 6) | Accomplish intent cleanly (no consequence unless fiction demands) |
| **Conflict** (4-5) | Succeed at action + Minor Consequence (GM makes soft Impact Move) |
| **Setback** (1-3) | Fail at action + Major Consequence (GM makes hard Impact Move) |
| **Disaster** (Setback + Complications reduce further) | Catastrophic failure + Severe Consequence |

---

## Consequence Framework

| Outcome | Consequence Tier | Your Response |
|---------|------------------|---------------|
| **Conflict** | **Minor Consequence** | Mark 1 Stress OR inflict Condition tier 1 OR soft Impact Move |
| **Setback** | **Major Consequence** | Mark 2 Stress OR inflict Condition tier 2-3 OR hard Impact Move |
| **Disaster** | **Severe Consequence** | Taken Out, Burden inflicted, catastrophic setback, or objective fails |

**Triumph/Success:** No consequence (clean success)

---

## Resolution Order Algorithm

When Complications, Expertise, or modifying traits (Deadly, Armor, etc.) are involved:

1. **Roll dice** → Determine raw outcome (Setback/Conflict/Success/Triumph)
2. **Apply Complications** → Each reduces outcome by 1 tier (Success → Conflict → Setback → Disaster)
3. **Apply Expertise** → If final outcome is Setback, convert to Conflict outcome (does NOT protect against Disaster)
4. **Map to base Consequence tier** → Conflict = Minor, Setback = Major, Disaster = Severe
5. **Apply trait modifiers** → Deadly increases tier by 1, Armor reduces tier by 1
6. **Resolve final Consequence** → Make Impact Move based on final tier

**Key:** Triumph ignores all Complications (cannot be reduced)

---

## Impact Moves by Tier

### Minor Consequence (Conflict)
- Mark 1 Stress
- Lose advantageous position
- Side effect occurs (noise, time passes, resource consumed)
- Countdown track advances 1 tick
- Enemy gains Edge on next action
- Environmental shift (fire spreads, alarm triggers)

### Major Consequence (Setback)
- Mark 2 Stress
- Mark 2 Stress + Condition tier 1-2
- Serious danger emerges (reinforcements, trap triggers)
- Objective setback (lose ground, ally captured)
- Countdown track advances 2 ticks
- Enemy Challenge Move triggers

### Severe Consequence (Disaster)
- Taken Out (unconscious, fleeing, captured)
- Burden inflicted (tier based on context)
- Catastrophic failure (objective fails completely)
- Countdown completes (ceiling collapses, ritual finishes)
- Enemy Death Move triggers

---

## The 5 Actions (Quick Reference)

| Action | Intent | Marks Track | Examples |
|--------|--------|-------------|----------|
| **Clash** | Harm/destroy | Harm | Attack enemy, smash object, break through barrier |
| **Defy** | Overcome danger | Obstacle | Dodge trap, resist spell, endure pain, overcome physical challenge |
| **Talk** | Influence/persuade | Will | Convince, intimidate, deceive, inspire, seduce |
| **Sense** | Observe/perceive | — | Spot hidden, read situation, track, detect lies (ask 2 questions) |
| **Know** | Recall/deduce | — | Remember lore, solve puzzle, analyze clue (gain information only, use Defy to overcome obstacles) |

**Know does NOT mark tracks.** Use Know to gain information, then use Defy (with Cunning) to overcome the obstacle with that knowledge.

---

## Complications

**Source:** Challenge Traits (enemy armor, magical wards, environmental hazards, NPC suspicion, etc.)

**Effect:** Each Complication reduces outcome by 1 tier (Success → Conflict, Conflict → Setback, Setback → Disaster)

**Counters:**
- **Act with Potency** (spend 1 Momentum) → Ignore 1 Complication + gain 1 Edge + narrative permission for bold action
- **Triumph** → Ignores ALL Complications automatically

**Common Complications:**
- **Heavily Armored** — Physical attacks reduced by 1 tier
- **Warded** — Magical attacks reduced by 1 tier
- **Fortified Position** — Attacks against this target reduced by 1 tier
- **Suspicious** — Talk actions to deceive reduced by 1 tier
- **Alert** — Stealth attempts reduced by 1 tier

---

## Expertise

**What It Does:** When you make an Action Roll within your area of Expertise, if your final outcome (after Complications) would be a **Setback**, the outcome is a **Conflict** instead.

**What It Doesn't Protect Against:**
- Disaster outcomes (Expertise only converts Setback → Conflict, not Disaster)
- Increased Consequence severity (traits like Deadly can still increase Consequence tier)

**Example:**
> Expert swordfighter attacks Armored Knight (2 Complications)
> - Rolls Success → Conflict → Setback (after Complications)
> - **Expertise:** Setback → Conflict outcome (you succeed!)
> - **Result:** Mark 1 tick + Minor Consequence (1 Stress)

---

## Momentum

**Earn:**
- Roll Triumph → Gain 1 Momentum
- Ally invokes Trait (Build Momentum) → You gain 1 Momentum
- Enemy rolls Setback near you + you have "Opportunist" Talent → Gain 1 Momentum

**Spend (choose one):**
- **Act with Potency:** Gain 1 Edge + ignore 1 Complication + narrative permission for bold action
- **Resist Consequence:** Roll Defy to reduce incoming Stress/Condition (Success = -2 steps, Conflict = -1 step)
- **Quick Assist:** Grant an ally 1 Edge on their next roll (no action required, can do on their turn)

**Cap:** 2 Momentum maximum (some Talents raise to 3)

---

## Stress & Conditions

### Stress Track (5 boxes)
- Mark left to right
- Clear all Stress on short rest (10-15 min)
- When full and you'd mark more → Choose: **Take a Burden** or **Be Taken Out**

**Stress Overflow Procedure:**
1. GM announces: "You would mark [X] Stress, but your track is full."
2. Player may spend 1 Momentum to Resist Consequence (roll Defy to reduce)
3. If any Stress remains, player chooses:
   - **Take a Burden** (tier = Stress amount, Stress clears to 0)
   - **Be Taken Out** (unconscious/fleeing/captured, GM narrates)

### Conditions
- **Name + Tier** (e.g., Poisoned 2, Frightened 1)
- **Effect:** 1 Bane per Condition (multiple Conditions stack)
- **Pool Modifier Cap:** ±2d maximum (universal rule — Edge and Bane cancel 1:1 before cap)
- **Tick Down:** Reduce tier by 1 each time you roll where Condition applies
- **Clear:** All Conditions clear on short rest (10-15 min)

**Common Conditions:** Poisoned, Burned, Blinded, Frightened, Stunned, Prone, Disarmed, Grappled, Weakened

### Burdens (Persistent Impairments)
- Like Conditions but do NOT clear on short rest
- **Recovery:** Reduce by 1 tier per long rest (overnight) OR special narrative resolution
- **Sources:** Stress Overflow, Disaster outcomes, Death Moves, significant narrative events
- **Examples:** Wounded, Cursed, Haunted, Crippled

---

## Challenge Traits

**Deadly:** Increases Consequence tier by 1 (Minor → Major, Major → Severe)

**Armored / Heavily Armored:** Adds 1-2 Complications vs physical attacks

**Warded:** Adds Complications vs magical attacks

**Elite:** Higher tier (6-tick or 8-tick track), may have additional Challenge Move

**Weak:** Lower tier (2-tick track), easier to defeat

**Pathetic:** 0-tick (defeated on any Success or better)

---

## Progress Tracks

**Harm Track:** HP equivalent (mark to defeat enemies)
- Tier 1 (minion): 2 ticks
- Tier 2 (standard): 4 ticks
- Tier 3 (elite): 6 ticks
- Tier 4 (boss): 8 ticks

**Obstacle Track:** Environmental/physical challenges (mark to overcome)
- Quick: 4 ticks
- Moderate: 6 ticks
- Major: 8 ticks

**Will Track:** Social influence (mark to persuade/convince)
- Hostile NPC: 6-8 ticks
- Neutral NPC: 4 ticks
- Friendly NPC: 2 ticks (or no track, just roleplay)

**Countdown Track:** Threats advancing (GM marks toward disaster)
- When full → Disaster occurs (ritual completes, ceiling collapses, reinforcements arrive)

---

## Combat Quick Flow

1. **Establish initiative order** (GM discretion, often by narrative positioning)
2. **Player turn:** Declare action → GM telegraphs stakes → Roll → Resolve
3. **Enemy turn:** GM narrates enemy action → Pick target → Make Challenge Move or GM makes Impact Move
4. **Repeat** until one side is defeated, flees, or surrenders

**No formal initiative system** — narrative flow determines who acts when. If unclear, GM decides or uses "who acts most decisively."

---

## Spellcasting Quick Reference

### Sage (Cunning-based)
- **Specialist:** 1 Sphere + 4 theorems from that Sphere + Expertise with entire Sphere
- **Generalist:** 4 theorems from any Spheres, no Expertise
- **Arcane Formula:** Cast off-list spell (mark 1 Stress, roll with 1 Bane, Specialist has Expertise if using their Sphere)

### Mystic (Spirit-based)
- **Patron Domains:** 2 domains (e.g., Healing, Nature, Death, Protection)
- **Divine Favor:** When you have Favor, you have Expertise when invoking patron
- **Losing Favor:** Roll Setback while invoking → lose Favor (can still invoke, but no Expertise)
- **Regaining Favor:** Act in accordance with patron's nature, fulfill obligations, make offerings, or complete devotion acts (work with GM)

### Magnitude
- **Cantrips:** Unlimited, no roll required (minor effects)
- **Spells:** Standard casting (roll Action + Approach)
- **Potent Spells:** Cost 1 Stress (significant effects, combat-altering)
- **Rituals:** Require Source + Anchors + Rites (extended casting, no roll, narrative-based)

**Casting Action:** Choose Action matching intent (Defy to protect, Clash to smite, Talk to bless/curse, Sense for visions, Know for communion)

---

## GM Principles

1. **Telegraph stakes before rolls** — Players should know consequences before committing
2. **Complications signal danger** — Use Challenge Traits to show what makes encounters harder
3. **Consequences drive action** — Impact Moves advance threats, change positioning, create urgency
4. **Respect player choices** — When players spend resources (Momentum, Stress, Traits), honor those choices
5. **Fiction first** — If it doesn't make sense in the fiction, don't allow it (even if mechanically valid)
6. **Pace with rests** — Short rests after fights, long rests between adventures
7. **Fail forward** — Setbacks complicate, they don't halt story (unless fiction demands)

---

## Common Pitfalls

**Forgetting Complications:** Challenge Traits do nothing if you forget to apply their Complications. Call them out before rolls.

**Skipping Telegraph:** Players should always know the stakes before rolling. "What happens on Setback?" should be answered before dice hit the table.

**Ignoring Expertise:** When an Expert rolls Setback (after Complications), convert to Conflict — they succeed at a cost.

**Stacking Banes Beyond Cap:** All pool modifiers cap at ±2d. If player has 3 Banes and 1 Edge, net is 2 Banes → capped at -2d when applied.

**Know Marking Tracks:** Know provides information only. Use Defy (with Cunning) to overcome knowledge-based obstacles.

**Letting Triumph Get Reduced:** Triumph ignores all Complications. It cannot be reduced to Success/Conflict/Setback.

---

## Quick Start Example

> **Setup:** Fighter wants to attack Armored Knight (Tier 2, 4-tick Harm track, Heavily Armored trait = 2 Complications)
>
> **GM:** "You're Clashing with Daring. The knight is Heavily Armored — 2 Complications. On Setback, his counterattack hits hard (mark 2 Stress). On Conflict, you land a blow but his armor jars your sword arm (mark 1 Stress)."
>
> **Player:** "I spend 1 Momentum to Act with Potency — ignoring 1 Complication and gaining 1 Edge."
>
> **GM:** "Potency ignores 1 Complication (1 remains). Roll Daring (3d) + 1d Edge = 4d, keep highest."
>
> **Player rolls:** 6, 5, 3, 2 → **Success (6)**
>
> **GM:** "Apply the remaining Complication: Success → Conflict. You cleave into his armor, denting the plate — mark 1 tick on his Harm track. But the impact jars you — mark 1 Stress."
>
> **Player:** "Can I invoke my 'Bladedancer' Trait for Greater Effect?"
>
> **GM:** "Absolutely. Mark 2 ticks instead of 1. He's at 2/4 Harm now. Still mark 1 Stress from the Conflict."

---

## Session Prep Checklist

**For each important NPC or enemy:**
- Name + description
- Tier + Harm/Will track size
- 1-2 Challenge Traits (what makes them hard to deal with?)
- 1-2 Challenge Moves (what do they do when acting?)

**For each location:**
- What's the immediate threat/opportunity?
- Any environmental hazards? (Complications for relevant actions)
- Any Countdown tracks? (What advances toward disaster?)

**For each scene:**
- What do the PCs want?
- What opposes them?
- What happens if they fail? (Telegraph this!)

---

For complete rules, see the full chapters. This cheat sheet is a quick reference only.
