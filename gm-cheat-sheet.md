# GM Cheat Sheet

Quick reference for running the game. For complete GM guidance, principles, moves, and examples, see **[Chapter 7: GM Guide](07-gm-guide.md)**.

---

## Action Resolution (Quick Flow)

### 1. Player Declares Intent
"What do you do?" → Player describes action + goal

### 2. GM Telegraphs Stakes
- **Action:** Which of the 5 Actions? (Clash, Defy, Talk, Sense, Know)
- **Vantage:** Certain (auto-success), Strong (no mod), Limited (1-2 Banes), Impossible (cannot attempt)
- **Stakes:** Low (-1 tier), Regular (default), High (+1 tier)
- **Complications:** List any Complications that apply (each reduces outcome by 1 tier)
- **Consequences:** "On Setback, [X happens]. On Conflict, [Y happens]."

### 3. Roll & Resolve
**Player rolls Approach + Action dice → Apply Complications → Apply Expertise (if any) → Resolve outcome**

| Outcome | Effect |
|---------|--------|
| **Triumph** (two 6s) | Full success + 1 Momentum + ignore Complications + may invoke Trait |
| **Success** (one 6) | Accomplish intent cleanly (no consequence unless fiction demands) |
| **Conflict** (4-5) | Succeed at action + Minor Consequence |
| **Setback** (1-3) | Fail at action + Major Consequence |
| **Disaster** (Setback + Complications reduce further) | Catastrophic failure + Severe Consequence |

---

## Consequence Framework

| Outcome | Consequence Tier | Your Response |
|---------|------------------|---------------|
| **Conflict** | **Minor Consequence** | Mark 1 Stress OR inflict Condition tier 1 OR narrative complication |
| **Setback** | **Major Consequence** | Mark 2 Stress OR inflict Condition tier 2-3 OR serious problem |
| **Disaster** | **Severe Consequence** | Taken Out, Burden inflicted, catastrophic setback, or objective fails |

**Triumph/Success:** No consequence (clean success)

---

## Resolution Order (Step-by-Step)

**For complete algorithm with examples, see Chapter 4: Action Resolution**

```
1. Roll Dice
   ↓
2. Read Outcome (highest die, or two+ 6s = Triumph)
   ↓
3. Apply Complications (each reduces outcome 1 tier)
   ↓
4. Apply Edge (cancels Complications 1:1)
   ↓
5. Apply Expertise (Setback → Conflict if in domain)
   ↓
6. Final Outcome & Consequence Tier
   ↓
7. Invoke Trait (if Conflict+ and relevant)
```

**Key Reminders:**
- **Triumph ignores ALL Complications** (skip steps 3-5, go straight to step 6)
- **Expertise does NOT prevent Disaster** (only upgrades Setback → Conflict)
- **Triumph cannot be created** (requires raw roll of two+ 6s, not upgraded via Expertise/Edge)
- **Check Complication tags** to see which apply to the action (Chapter 6)

---

## Consequences by Tier

### Minor Consequence (Conflict)
PC succeeds but faces complication:
- Mark 1 Stress
- Lose advantageous position
- Attract attention or raise suspicion
- Warn of imminent danger (enemy prepares to strike)
- Countdown track advances 1 tick
- Side effect occurs (noise, time passes, resource consumed)

### Major Consequence (Setback)
PC fails AND faces serious problem:
- Mark 2 Stress (or 1 Stress + Condition tier 2-3)
- Enemy counterattacks or gains major advantage
- Serious danger emerges (reinforcements, trap triggers)
- Lose something important (weapon, position, ally)
- Objective setback (lose ground, harder to achieve)
- Countdown track advances 2 ticks

### Severe Consequence (Disaster)
Catastrophic failure:
- Taken Out (unconscious, fleeing, captured)
- Burden inflicted (persistent Condition)
- Objective fails completely
- Countdown completes (ceiling collapses, ritual finishes)
- Enemy Death Move triggers (if defeated)

---

## The 5 Actions (Quick Reference)

| Action | Intent | Marks Track | Examples |
|--------|--------|-------------|----------|
| **Clash** | Harm/destroy | Harm or Will | Attack enemy, smash object, intimidate through force |
| **Defy** | Push limits / risky action | Obstacle (if sustained) | Dodge trap, leap chasm, pickpocket, knockdown foe (no harm), resist spell, cast debuff spell |
| **Talk** | Influence/persuade | Will | Convince, inspire, deceive, negotiate |
| **Sense** | Observe/perceive | — | Spot hidden, read situation, track, detect lies (ask 2 questions) |
| **Know** | Recall/deduce | — | Remember lore, solve puzzle, analyze clue (gain info, then use Defy to act on it) |

**Defy is the catch-all for risky/extraordinary actions** not covered by other Actions. Simple tasks resolve in one roll; complex challenges use Obstacle tracks.

---

## Complications

**Source:** Complications (enemy armor, magical wards, environmental hazards, NPC suspicion, etc.)

**Effect:** Each Complication reduces outcome by 1 tier (Success → Conflict, Conflict → Setback, Setback → Disaster)

**Counters:**
- **Create an Opening** (spend 1 Momentum) → Your action gains 1 Boon (+1d) and 1 Edge (ignore 1 Complication), plus narrative permission for extraordinary feats
- **Create Advantage** (via Secondary Effect: free Defy) → Grant ally 1 Boon OR 1 Edge (player suggests, GM decides)
  - **Boon:** General advantage (flanking, distraction, high ground)
  - **Edge:** Bypass specific Complication (target armor gap, reveal hidden foe)
- **Triumph** → Ignores ALL Complications automatically
- **Fictional Positioning** → Smart setup can bypass or remove Complications (see Chapter 6)

**Boon vs Edge Decision:**
- Does it target a specific Complication source? → Edge
- Does it create general advantage? → Boon

**Common Complications:**
- **Resilient** — Physical attacks reduced by 1 tier (armor, tough hide)
- **Warded** — Magical effects reduced by 1 tier (counterspells, wards)
- **Elusive** — Targeting/detection reduced by 1 tier (speed, stealth, small size)
- **Vigilant** — Stealth/deception reduced by 1 tier (keen senses, awareness)
- **Complex** — Understanding/navigation reduced by 1 tier (mechanisms, politics)
- **Resolute** — Social influence reduced by 1 tier (discipline, conviction)
- **Deadly** — Combat actions face increased lethality (Consequence tier +1)
- **Legendary** — ALL actions reduced by 1 tier (overwhelming presence)

---

## Expertise

**What It Does:** When you make an Action Roll within your area of Expertise, if your final outcome (after Complications) would be a **Setback**, the outcome is a **Conflict** instead.

**What It Doesn't Protect Against:**
- Disaster outcomes (Expertise only converts Setback → Conflict, not Disaster)
- Increased Consequence severity (Universal Complications like Deadly can still increase Consequence tier)

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
- **Create an Opening:** Your action gains 1 Boon (+1d) and 1 Edge (ignore 1 Complication), plus narrative permission for extraordinary feats
- **Resist Consequence:** Automatically reduce Consequence Tier by 1 (no roll required)
- **Assist:** Grant an ally 1 Boon on their next roll (mark 1 Stress, no action required)

**Cap:** 2 Momentum maximum (some Talents raise to 3)

---

## Stress & Conditions

### Stress Track (5 boxes)
- Mark left to right
- Clear all Stress on Short Rest (1 hour, safe location)
- When full and you'd mark more → Choose: **Take a Burden** or **Be Taken Out**

**Stress Overflow Procedure:**
1. GM announces: "You would mark [X] Stress, but your track is full."
2. Player may spend 1 Momentum to Resist Consequence (automatically reduce by 1)
3. If any Stress remains, player chooses:
   - **Take a Burden** (tier = Stress amount, Stress clears to 0)
   - **Be Taken Out** (unconscious/fleeing/captured, GM narrates)

### Conditions
- **Name + Tier** (e.g., Poisoned 2, Frightened 1)
- **Effect:** 1 Bane per Condition (multiple Conditions stack)
- **Pool Modifier Cap:** ±2d maximum (universal rule — Boons and Banes cancel 1:1 before cap)
- **Tick Down:** Reduce tier by 1 each time you roll where Condition applies
- **Clear:** All Conditions clear on Short Rest (1 hour, safe location)

**Common Conditions:** Poisoned, Burned, Blinded, Frightened, Stunned, Prone, Disarmed, Grappled, Weakened

### Burdens (Persistent Impairments)
- Like Conditions but do NOT clear on Short Rest
- **Recovery:** Reduce by 1 tier per Long Rest (overnight) OR special narrative resolution
- **Sources:** Stress Overflow, Disaster outcomes, Death Moves, significant narrative events
- **Examples:** Wounded, Cursed, Haunted, Crippled

---

## Complications

**Deadly (Universal Complication):** Increases Consequence tier by 1 (Minor → Major, Major → Severe)

**Armored / Heavily Armored:** Adds 1-2 Complications vs physical attacks

**Warded:** Adds Complications vs magical attacks

**Elite:** Higher tier (6-tick or 8-tick track), may have additional Challenge Move

**Weak:** Lower tier (2-tick track), easier to defeat

**Pathetic:** 0-tick (defeated on any Success or better)

---

## Progress Tracks

**Harm Track:** HP equivalent (mark to defeat enemies)
- CR 1 (minion): 2 ticks
- CR 2 (standard): 4 ticks
- CR 3 (elite): 6 ticks
- CR 4 (boss): 8 ticks

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
3. **Enemy turn:** GM narrates enemy action → Pick target → Deliver consequence or warn of danger
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

## Vantage (Chapter 2)

Your character's capabilities and current situation—determines what you can attempt.

- **Clear Vantage:** Anyone can try (no modifier)
- **Limited Vantage:** Requires Expertise, Trait, gear, or fictional setup (may impose 1 Bane if lacking)
- **No Vantage:** Impossible given who you are or current circumstances (may impose 2 Banes or prevent action entirely)

**Examples:**
- Doctor can suture wounds (Expertise grants vantage)
- Can't pick lock without tools (no vantage → 2 Banes or impossible)
- Can't swing sword with broken arm (Condition removes vantage → 1-2 Banes or impossible)

**At the table:** When a player attempts something unusual, ask: "Do you have vantage for that?" Use Banes to represent difficulty from lacking proper positioning, tools, or capability.

---

## GM Principles

1. **Telegraph stakes before rolls** — Players should know consequences before committing
2. **Complications signal danger** — Use Complications to show what makes encounters harder
3. **Consequences drive action** — Consequences advance threats, change positioning, create urgency
4. **Warn before striking** — Telegraph imminent danger, give PCs a chance to respond
5. **Respect player choices** — When players spend resources (Momentum, Stress, Traits), honor those choices
6. **Fiction first / Check Vantage** — If they lack vantage, it may be harder (Banes) or impossible
7. **Pace with rests** — Short rests after fights, Long Rests between adventures
8. **Fail forward** — Setbacks complicate, they don't halt story (unless fiction demands)

---

## Common Pitfalls

**Forgetting Complications:** Complications do nothing if you forget to apply their Complications. Call them out before rolls.

**Skipping Telegraph:** Players should always know the stakes before rolling. "What happens on Setback?" should be answered before dice hit the table.

**Ignoring Expertise:** When an Expert rolls Setback (after Complications), convert to Conflict — they succeed at a cost.

**Stacking Banes Beyond Cap:** All pool modifiers cap at ±2d. If player has 3 Banes and 1 Boon, net is 2 Banes → capped at -2d when applied.

**Know Marking Tracks:** Know provides information only. Use Defy (with Cunning) to overcome knowledge-based obstacles.

**Letting Triumph Get Reduced:** Triumph ignores all Complications. It cannot be reduced to Success/Conflict/Setback.

---

## Quick Start Example

> **Setup:** Fighter wants to attack Armored Knight (Tier 2, 4-tick Harm track, Heavily Armored trait = 2 Complications)
>
> **GM:** "You're Clashing with Daring. The knight is Heavily Armored — 2 Complications. On Setback, his counterattack hits hard (mark 2 Stress). On Conflict, you land a blow but his armor jars your sword arm (mark 1 Stress)."
>
> **Player:** "I spend 1 Momentum to Create an Opening — gaining 1 Boon and 1 Edge that ignores 1 Complication."
>
> **GM:** "Your Edge ignores 1 Complication (1 remains). Roll Daring (3d) + 1 Boon = 4d, keep highest."
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
- 1-2 Complications (what makes them hard to deal with?)
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

## Additional Resources

**For complete guidance:**
- **[Chapter 7: GM Guide](07-gm-guide.md)** — GM principles, moves, spotlight management, and session prep
- **[Chapter 4: Action Resolution](04-action-resolution.md)** — Complete Action Roll procedures and resolution algorithm
- **[Chapter 6: Challenges](06-challenges.md)** — Enemy design, Complications, Challenge Moves, and balancing encounters

This cheat sheet is a quick reference only.
