# Traits, Complications, and Challenges

This document defines how Traits, Challenge Traits, and Complications work in the heroic fantasy RPG system.

For core mechanics (Actions, Approaches, Momentum, Stress), see [core-foundations.md](core-foundations.md).

---

## Traits (Tactical Menu)

Traits are evocative narrative descriptors defining who your character is. When a Trait is narratively relevant to your action, you may invoke it.

**When you invoke a Trait, roll first, then choose one option after seeing your result:**

### 1. Greater Impact
Double your effect.

**On Conflict or Success:**
- Mark 2 ticks instead of 1
- Ask 4 questions instead of 2 (Sense)
- Gain 2 Edge instead of 1 (Know)

**On Triumph:** Doubles your chosen Critical Bonus:
- Greater Effect: Mark 4 ticks (instead of 2), ask 9 questions (instead of 6), gain 4 additional Edge
- Secondary Effect: Affect 2 targets, escalate severity, or produce more significant consequence
- Create Opportunity: Grant 2 Edge, affect 2 allies, or grant Edge + negate Complication to same ally

**Does not apply on Setback** (you failed).

**Examples:**
- "Veteran of the Iron Wars" → Greater Impact when Clashing (mark 2 ticks on enemy's Challenge Track)
- "Silver Tongue" → Greater Impact when Talking (mark 2 ticks on Accord Track)
- "Scholar of the Ruins" → Greater Impact when using Know in ancient sites (gain 2 Edge when acting on knowledge)

---

### 2. Negate a Complication
Cancel one Complication imposed by a Challenge Trait.

**Effect:** Choose one Challenge Trait affecting this action. It does not impose its Complication for this roll (prevents outcome reduction from that Trait).

**Applies on any outcome** (prevents outcome reduction).

**Examples:**
- Your "Armor Piercer" negates enemy's "Heavily Armored"
- Your "Silver Tongue" negates NPC's "Suspicious of Outsiders"
- Your "Shadowborn" negates ward's "Mystic Detection"
- Your "Giant Slayer" negates troll's "Tough Hide"

**Note:** You can stack this with Momentum (spend 1 Momentum to Negate a second Complication) or Talents (some negate Complications automatically in specific situations).

---

## Declaring Trait Use

**Timing:** Roll dice → See outcome → Choose Trait option (if relevant) → Apply remaining Complications → Resolve final outcome

**This creates informed tactical decisions:**
- You see your raw result (Success, Conflict, Setback, Triumph)
- You see what Complications apply (enemy has "Heavily Armored")
- You choose: Double your effect with Greater Impact, OR negate Complication for clean success

**Example:**
- You attack an armored knight (has "Heavily Armored" = 1 Complication)
- You roll Success → Would be reduced to Conflict by Heavy Armor
- **Option A:** Use Greater Impact (Conflict, mark 2 ticks, but take consequences from Conflict)
- **Option B:** Negate Heavy Armor (Success, mark 1 tick cleanly, no consequences)

**Only one Trait per roll.** You cannot use multiple Traits or choose multiple options.

---

## Complications (Outcome Reduction)

**Complications** represent special defenses, advantages, or abilities that make Challenges harder to overcome. Each Complication reduces your outcome tier by one step.

### Outcome Reduction Chain

**Triumph** → Success → Conflict → Setback → **Taken Out**

**How it works:**
- Each uncanceled Complication moves your result one step down the chain
- **Triumph cannot be reduced** (it ignores all Complications)
- Reducing below Setback means you are Taken Out (unconscious, captured, defeated, overwhelmed)

**Examples:**

**1 Complication:**
- Success → Conflict (partial success with cost)
- Conflict → Setback (failure with consequences)
- Setback → Taken Out

**2 Complications:**
- Success → Setback (skip Conflict entirely)
- Conflict → Taken Out
- Setback → Taken Out

**3+ Complications:**
- Success → Taken Out (or Setback at GM discretion)
- Anything less than Triumph is likely Taken Out

---

## Negating Complications

Complications can be negated after rolling:

### 1. Talents (Automatic)

Some Talents negate Complications automatically in specific situations (applied first).

**Example:**
- Enemy has "Heavily Armored" + "Shielded" (2 Complications)
- Your "Shield Splitter" Talent automatically negates shield-related Complications
- "Shielded" negated automatically, "Heavily Armored" remains

### 2. Negate a Complication (Trait Option)

After rolling, use the "Negate a Complication" Trait option to counter one specific Challenge Trait.

**Example:**
- You roll Success against armored knight
- Enemy has "Heavily Armored" + "Shielded" (2 Complications)
- You use "Armor Piercer" Trait to Negate "Heavily Armored"
- You still face 1 Complication from "Shielded" (Success → Conflict)

### 3. Negate a Complication (Momentum)

After rolling, spend 1 Momentum to negate one Complication.

**Example:**
- You roll Success against armored knight
- Enemy has "Heavily Armored" + "Shielded" (2 Complications)
- You use "Armor Piercer" Trait to Negate "Heavily Armored"
- You spend 1 Momentum to Negate "Shielded"
- Both Complications negated → Success remains Success

### 4. Triumph Ignores All Complications

**Triumph results cannot be reduced.** No matter how many Complications exist, Triumph stays Triumph.

**This makes Triumph extremely valuable against heavily defended targets.**

---

## Negation Priority

**Order of resolution:**

1. **Roll dice** → Determine raw outcome (Success, Conflict, Setback, Triumph)
2. **Talents** automatically negate specific Complications (if applicable)
3. **Trait "Negate a Complication"** removes one Challenge Trait (choose after seeing result)
4. **Momentum "Negate a Complication"** removes one Challenge Trait (spend 1 Momentum after seeing result)
5. **Apply any remaining Complications** to reduce outcome tier
6. **Triumph ignores all remaining Complications** (cannot be reduced)

**Tactical Decision:** After rolling, you see your raw outcome and what Complications apply. Then you decide whether to use Trait/Momentum to negate, or accept the reduced outcome.

**Full Example:**
- You attack a knight with "Heavily Armored" + "Shielded" + "Warded" (3 Complications)
- You roll Success (raw result before Complications)
- **Automatic:** Your "Shield Splitter" Talent negates "Shielded" (2 Complications remain)
- **Choice 1:** Use "Armor Piercer" Trait to Negate "Heavily Armored"? (would leave 1 Complication)
  - If yes: Success → Conflict by "Warded"
- **Choice 2:** Also spend 1 Momentum to Negate "Warded"? (would remove all Complications)
  - If yes: Success stays Success (clean hit, 1 Stress to knight)
- **Alternative:** Accept Conflict outcome, use Trait for Greater Impact instead (Conflict, deal 2 Stress, take consequences)

If you had rolled Triumph instead, it ignores all 3 Complications automatically (no choices needed).

---

## Challenge Design

Challenges are adversaries, obstacles, or situations that oppose the PCs. They have two key attributes:

### Challenge Tier (Consequence Severity)

**Tier determines what happens on Setback or Conflict:**

**Tier 1 - Minor Challenge**
- **On Setback:** 1 Stress OR minor consequence
- **On Conflict:** Mark 1 tick/progress, take 1 Stress OR minor consequence
- **Examples:** Bandits, routine obstacles, minor NPCs

**Tier 2 - Moderate Challenge**
- **On Setback:** 2 Stress OR moderate consequence (Moderate Condition, lose equipment, enemy gains major advantage)
- **On Conflict:** Mark 1 tick/progress, take 2 Stress OR moderate consequence  
- **Examples:** Veterans, dangerous obstacles, important NPCs, most enemies

**Tier 3 - Severe Challenge**
- **On Setback:** 3 Stress OR severe consequence (Severe Condition, Taken Out, catastrophic complication)
- **On Conflict:** Mark 1 tick/progress, take 3 Stress OR severe consequence
- **Examples:** Elite warriors, deadly obstacles, powerful magic, boss enemies

**GM Note:** Default to Tier 2 for most Challenges. Tier 1 is for easy encounters or weakened foes. Tier 3 is for dramatic climactic moments.

---

### Challenge Traits (Special Abilities)

Not all Challenges have Traits. When they do, Traits represent special defenses, abilities, or characteristics.

**Types of Challenge Traits:**

#### Defensive Traits (Most Common)
**Impose 1 Complication** when PCs act against them.

**Examples:**
- **"Heavily Armored"** - Physical attacks reduced
- **"Shielded"** - Frontal attacks reduced
- **"Warded"** - Magical effects reduced
- **"Suspicious"** - Social manipulation reduced
- **"Ancient Wards"** - Intrusion/bypass attempts reduced
- **"Regeneration"** - Lasting harm reduced

#### Exploitable Traits (Less Common)
**Grant advantage** when PCs exploit them.

**Examples:**
- **"Easily Frightened"** - When intimidated/surprised, grants 1 Edge to PCs
- **"Overconfident"** - When pride exploited, reduce Tier by 1
- **"Slow"** - When speed/agility used against it, grants 1 Edge
- **"Arrogant"** - Social flattery grants 1 Edge
- **"Weak to Fire"** - Fire attacks grant 1 Edge or reduce Complication

#### Contextual Traits
**Apply only in specific situations.**

**Examples:**
- **"Master Duelist"** (only in melee combat)
- **"Silver Tongued"** (only in social situations)
- **"Eagle-Eyed"** (only when perception matters)

---

### Challenge Design Quick Guide

**Not every Challenge needs Traits.** Reserve Traits for significant opposition or tactical puzzles.

| Tier & Traits | Power Level | Examples |
|---------------|-------------|----------|
| **Tier 1, 0 Traits** | Trivial opposition | Goblins, bandits, routine obstacles, locked doors |
| **Tier 1, 1 Trait** | Competent but fragile | Skilled archer with "Eagle-Eyed", scout with "Fast" |
| **Tier 2, 0 Traits** | Standard opposition | Knights, veterans, basic wards, complex negotiations |
| **Tier 2, 1 Trait** | Dangerous opposition | Armored knight, warded vault, suspicious noble |
| **Tier 2, 2 Traits** | Elite opposition | Master duelist, ancient golem, layered defenses |
| **Tier 3, 0 Traits** | Deadly baseline | Dragon, archmage, deadly trap (dangerous even without defenses) |
| **Tier 3, 1-2 Traits** | Boss-tier | Requires team coordination, multiple setup actions, perfect tactics |
| **Tier 3, 3+ Traits** | Near-impossible | Only achievable with extensive preparation, full party coordination, or Triumph |

**Balance Note:** More Traits = more preparation required. Challenges with 2+ Complications usually require at least 2 Edge (from allies, positioning, or setup) OR Triumph to succeed cleanly.

---

### Challenge Examples

**Tier 1 Goblin Scout**
- **Tier:** 1 (1 Stress on Setback/Conflict)
- **Traits:** "Easily Frightened"
  - When intimidated, grants 1 Edge to PCs
- **Clock:** 2 ticks to defeat

**Tier 2 Armored Knight**
- **Tier:** 2 (2 Stress on Setback/Conflict)
- **Traits:** "Heavily Armored"
  - Physical attacks face 1 Complication (Success → Conflict)
- **Clock:** 4 ticks to defeat

**Tier 3 War Troll**
- **Tier:** 3 (3 Stress on Setback/Conflict)
- **Traits:** "Tough Hide," "Regeneration"
  - Physical attacks face 2 Complications (Success → Setback)
  - Requires exploiting weakness (fire, magic) or heavy Edge investment
- **Clock:** 6 ticks to defeat

**Tier 2 Ancient Vault Door**
- **Tier:** 2 (2 Stress on Setback/Conflict)
- **Traits:** "Sealed," "Warded"
  - Bypass attempts face 2 Complications
  - Can be defeated by finding key, dispelling wards, or brute force with Edge
- **Clock:** 6 ticks to bypass

---

## Edge & Bane Interaction

**Edge and Bane** remain unchanged from [core-foundations.md](core-foundations.md). They form a separate system from Complications.

### Cancellation Rules

1. **Edge and Bane cancel 1:1** (as normal)
2. **Edge does NOT cancel Complications** (separate systems)
3. **Bane does NOT create Complications** (Bane only affects dice, not outcome tier)

**Example:**
- Enemy has "Heavily Armored" (1 Complication)
- You have 2 Edge (flanking + ally assist)
- Enemy gives you 1 Bane (you're wounded)
- Resolution: 2 Edge - 1 Bane = 1 Edge remaining
- Roll with 1 Edge (better dice roll)
- Still face 1 Complication from "Heavily Armored" (Success → Conflict unless negated by Trait/Momentum/Talent)

**Design Note:** Edge makes your roll better (more likely to succeed). Complications make your success less effective (outcome reduction). These are independent mechanical tracks.

---

## System-Specific Implementation

All three resolution systems use the same Trait/Complication framework. The difference is in how Edge/Bane modify rolls.

### Xd6 Count-Successes

**Edge:** +1d to pool (unlimited stacking)  
**Bane:** -1d from pool (unlimited stacking)  
**Minimum pool:** 1d6

**Complication Interaction:**
- After rolling, count successes (5-6s)
- Each uncanceled Complication reduces outcome tier by 1
- Triumph ignores all Complications

**Example:** 3d6, roll [5, 5, 4] = 2 successes = Success
- 1 uncanceled Complication → Success becomes Conflict

---

### Forged in the Dark

**Edge:** +1d to pool (cap +2d)  
**Bane:** -1d from pool (cap -2d)  
**Minimum pool:** Roll 2d6, take lowest

**Complication Interaction:**
- After rolling, check highest die (+ doubles for Triumph)
- Each uncanceled Complication reduces outcome tier by 1
- Triumph ignores all Complications

**Example:** 3d6, roll [6, 4, 2] = Success (highest is 6)
- 1 uncanceled Complication → Success becomes Conflict

---

### 2d10+Modifier

**Edge:**  
- 1 Edge: Roll 3d10, drop lowest
- 2+ Edge: Roll 4d10, drop 2 lowest (cap)

**Bane:**  
- 1 Bane: Roll 3d10, drop highest
- 2+ Bane: Roll 4d10, drop 2 highest (cap)

**Thresholds:** ≤9 Setback, 10-14 Conflict, 15-19 Success, 20+ Triumph

**Complication Interaction:**
- After rolling and adding modifier, compare to thresholds
- Each uncanceled Complication reduces outcome tier by 1
- Triumph ignores all Complications

**Example:** Roll [12, 8] + 3 = 15 total = Success
- 1 uncanceled Complication → Success becomes Conflict

---

## GM Guidance

### Setting Challenge Tier

**Ask:** "How severe should consequences be?"

**Tier 1 - Minor:** Minor encounters, weakened foes, routine obstacles
- Bandits, goblins, locked doors, simple traps
- Setback/Conflict = 1 Stress or minor consequence

**Tier 2 - Moderate:** Standard encounters, competent opposition, meaningful obstacles
- Veterans, knights, magical wards, complex negotiations
- Setback/Conflict = 2 Stress or moderate consequence
- **Default to Tier 2 for most Challenges**

**Tier 3 - Severe:** Boss fights, elite opposition, deadly hazards, climactic moments
- Dragons, archmages, ancient curses, powerful tyrants
- Setback/Conflict = 3 Stress or severe consequence
- **Use sparingly for dramatic moments**

---

### Assigning Challenge Traits

**Not every Challenge needs Traits.** Reserve Traits for:
- Significant opposition (named NPCs, important enemies)
- Special defenses or abilities
- Creating tactical puzzles

**Guidelines:**
- **0 Traits:** Standard challenges, mooks, routine obstacles
- **1 Trait:** Competent opposition with one defining feature
- **2 Traits:** Elite opposition with layered defenses
- **3+ Traits:** Boss-tier opposition requiring team coordination

**Balance:** More Traits = more preparation required. 2+ Complications means only Triumph or Trait/Momentum negation succeeds cleanly.

---

### Communicating Stakes

**Always telegraph before the roll:**

> **GM:** "The Armored Knight is Tier 2 with 'Heavily Armored.' If you roll Success, his armor will reduce it to Conflict (you'd take 2 Stress). You could negate his armor with your Trait or Momentum if you want."

> **Player:** "Got it. I'll decide after I roll." *(rolls Success)*

> **Player:** "I'll use my 'Armor Piercer' Trait to negate his armor. Clean success, 1 Stress to him."

**Clear communication prevents surprises and creates informed tactical choices. Players know their options before rolling, then make final decisions after seeing results.**

---

### Exploitable Traits

Use exploitable Traits to reward creative play:

**"Easily Frightened"** → Intimidation/surprise grants Edge  
**"Overconfident"** → Exploiting pride reduces Tier  
**"Slow"** → Speed/agility grants Edge  
**"Arrogant"** → Flattery grants Edge  
**"Weak to Fire"** → Fire attacks grant Edge  

**When PCs exploit these, narrate how their approach leverages the weakness.**

---

### Encouraging Tactical Play

Edge improves dice rolls but doesn't negate Complications. Encourage players to:
- **Position tactically** (flanking, high ground, cover) → grants Edge for better rolls
- **Work together** (Create Opportunity for allies) → grants Edge for better rolls
- **Prepare** (scout, gather intel, acquire tools) → grants Edge or reveals exploitable Traits
- **Use Traits strategically** (after rolling, decide whether to negate Complications or push for Greater Impact)
- **Spend Momentum** (negate additional Complications when Trait already used for Greater Impact, or vice versa)
- **Exploit weaknesses** (target exploitable Traits that grant Edge or reduce Tier)

**Reward creative tactics with Edge.** When facing multiple Complications, players make informed post-roll decisions: accept reduced outcome with bonus effect, or negate defenses for clean success. This creates meaningful tactical choices every roll.

---

## Quick Reference

### Trait Options (Choose One After Rolling)
1. **Greater Impact** - Double your effect
   - Success/Conflict: Mark 2 ticks, ask 4 questions, gain 2 Edge (the first time you use it)
   - Triumph: Doubles Critical Bonus (mark 4 ticks, ask 9 questions, gain 4 Edge the first time you use it, affect 2 targets, etc.)
   - Does not apply on Setback
2. **Negate a Complication** - Cancel one Challenge Trait's Complication
   - Applies on any outcome

### Complications
- Challenge Traits impose Complications
- Each Complication reduces outcome by 1 tier (Success → Conflict → Setback → Taken Out)
- Negate with Trait option (after roll), Momentum (1 per Complication, after roll), or certain Talents (automatic)
- Triumph ignores all Complications

### Challenge Tier
- **Tier 1:** 1 Stress or minor consequence on Setback/Conflict
- **Tier 2:** 2 Stress or moderate consequence on Setback/Conflict (default)
- **Tier 3:** 3 Stress or severe consequence on Setback/Conflict

### Action Core Functions
- **Defy/Clash/Talk:** Mark 1 tick on track (Success/Conflict), or resolve immediately if simple
- **Sense:** Ask 2 questions (Success), 1 question (Conflict)
- **Know:** GM tells you useful info + gain 1 Edge the first time you roll when acting on that information (Success)

### Triumph Critical Bonus (choose one)
1. **Greater Effect** — Mark 2 ticks, ask 6 questions, gain 4 Edge (the first time you use it)
2. **Secondary Effect** — Produce additional consequence (Take Something, Inflict Condition, etc.)
3. **Create an Opportunity** — Grant ally 1 Edge OR negate 1 Complication
