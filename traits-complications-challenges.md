# Traits, Complications, and Challenges

This document defines how Traits, Challenge Traits, and Complications work in the heroic fantasy RPG system.

For core mechanics (Actions, Approaches, Momentum, Stress), see [core-foundations.md](core-foundations.md).

---

## Traits (Critical Effects)

Traits are evocative narrative descriptors defining who your character is. When a Trait is narratively relevant to your action, you may invoke it to gain a **Critical Effect**.

### Invoking a Trait

**After rolling and determining your final outcome:**

**On Conflict or Success:** Choose one Critical Effect:
1. **Greater Effect** — Mark 2 ticks (instead of 1), ask 6 questions (instead of 2), gain 4 Edge the first time you use it (instead of 1)
2. **Secondary Effect** — Produce additional consequence (Take Something, Inflict Condition, Affect Multiple Targets, etc.)
3. **Create an Opportunity** — Grant ally 1 Edge OR negate 1 Complication for their next related action

**On Triumph:** Choose **two** Critical Effects (can choose the same one twice for enhanced effect)

**On Setback:** Cannot invoke Trait (you failed)

**Examples:**
- "Veteran of the Iron Wars" → Relevant when Clashing in melee combat → Invoke for Critical Effect (e.g., Greater Effect to mark 2 ticks, or Secondary Effect to disarm enemy)
- "Silver Tongue" → Relevant when Talking to influence people → Invoke for Critical Effect (e.g., Greater Effect to mark 2 ticks on Accord Track, or Secondary Effect to dramatically shift attitude)
- "Shadowborn" → Relevant when acting in darkness/stealth → Invoke for Critical Effect (e.g., Create Opportunity to grant ally Edge, or Secondary Effect to remain undetected)

---

## Declaring Trait Use

**Timing:** Roll dice → Determine raw outcome → Apply Complications → Determine final outcome → If Conflict or higher and Trait relevant, invoke for Critical Effect(s)

**This creates dramatic moments:**
- You see your final outcome after Complications
- If you achieved Conflict or better and your Trait is relevant, you invoke it
- Choose which Critical Effect best fits the situation

**Example:**
- You attack an armored knight (has "Heavily Armored" = 1 Complication)
- You have "Armor Piercer" Trait and 2 Edge
- **Before roll:** Trade 1 Edge to negate "Heavily Armored", roll with +1 Edge remaining
- **Roll result:** Success (no Complications remain)
- **Invoke Trait:** "Armor Piercer" is relevant → Choose Critical Effect:
  - **Greater Effect:** Mark 2 ticks total (nearly defeated!)
  - **Secondary Effect:** Disarm him as you strike (Take Something)
  - **Create Opportunity:** Grant ally 1 Edge to follow up

**Only one Trait per roll.** You cannot use multiple Traits (but Triumph + one Trait = two Critical Effects total).

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

Complications can be negated in two ways:

### 1. Trade Edge (Before Rolling)

**Before rolling**, you can trade Edge 1:1 to negate Complications:
- Each Edge traded removes one Complication from affecting this roll
- You roll with remaining Edge (improved dice) and face remaining Complications (outcome reduction)

**Example:**
- Enemy has "Heavily Armored" + "Shielded" (2 Complications)
- You have 3 Edge (positioning + ally + Momentum)
- **Trade 2 Edge:** Negate both Complications, roll with +1 Edge remaining
- **Trade 1 Edge:** Negate one Complication, roll with +2 Edge, face 1 remaining Complication
- **Trade 0 Edge:** Roll with +3 Edge, face both Complications (Success → Setback)

**Tactical Decision:** Probability boost (keep Edge for better roll) vs outcome security (negate Complications for cleaner result).

### 2. Create an Opportunity (Critical Effect)

When you or an ally gains a Critical Effect (from Triumph or relevant Trait), you can choose **Create an Opportunity** to grant:
- 1 Edge OR negate 1 Complication for ally's next related action

**Example:**
- Ally will attack armored knight next
- You achieve Triumph on Sense → Choose "Create Opportunity" → Negate "Heavily Armored" for ally's attack

### 3. Talents (Automatic)

Some Talents negate Complications automatically in specific situations.

**Example:**
- Enemy has "Heavily Armored" + "Shielded" (2 Complications)
- Your "Shield Splitter" Talent automatically negates shield-related Complications
- "Shielded" negated automatically, "Heavily Armored" remains (can trade Edge to negate it)

### 4. Triumph Ignores All Complications

**Triumph results cannot be reduced.** No matter how many Complications exist, Triumph stays Triumph.

**This makes Triumph extremely valuable against heavily defended targets.**

---

## Resolution Priority

**Order of resolution:**

1. **GM states Complications** present on this Challenge
2. **Calculate Edge and Bane** from all sources (cancel 1:1)
3. **Before rolling:** Trade Edge 1:1 to negate Complications (your choice)
4. **Roll dice** with modified pool
5. **Determine raw outcome** (Success, Conflict, Setback, Triumph)
6. **Talents** automatically negate remaining Complications (if applicable)
7. **Apply remaining Complications** to reduce outcome tier
8. **Triumph ignores all Complications** (cannot be reduced)
9. **If Conflict or higher + relevant Trait:** Invoke for Critical Effect(s)

**Full Example:**
- You attack a knight with "Heavily Armored" + "Shielded" (2 Complications)
- You have "Armor Piercer" Trait and 2 Edge (positioning + ally)
- **Before roll:** Trade 1 Edge to negate "Heavily Armored", keep 1 Edge for dice
- **Roll:** 4d6 (base 3d6 + 1 Edge) → Result: 2 successes = Success
- **Apply Complications:** "Shielded" remains → Success becomes Conflict
- **Final outcome:** Conflict (mark 1 tick, take 2 Stress)
- **Invoke Trait:** "Armor Piercer" relevant → Choose Critical Effect:
  - **Greater Effect:** Mark 2 ticks despite Conflict
  - **Secondary Effect:** Disarm him as you strike (Take Something)
  - **Create Opportunity:** Grant ally 1 Edge to follow up

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

**Edge and Bane** modify your dice roll. **Complications** reduce your outcome tier. These are separate but related systems.

### How They Interact

**Edge serves two purposes:**
1. **Roll better dice** (keep Edge to improve success probability)
2. **Negate Complications** (trade Edge before rolling to prevent outcome reduction)

**Before rolling, you choose:** Keep Edge for dice OR trade Edge to negate Complications (1:1).

### Cancellation Rules

1. **Edge and Bane cancel 1:1** (before you can trade Edge for Complications)
2. **After cancellation**, remaining Edge can be kept for dice OR traded for Complication negation
3. **Bane does NOT create Complications** (Bane only affects dice probability)

**Example:**
- Enemy has "Heavily Armored" (1 Complication)
- You have 2 Edge (flanking + ally assist)
- Enemy gives you 1 Bane (you're wounded)
- **Step 1:** 2 Edge - 1 Bane = 1 Edge remaining
- **Step 2 (your choice):**
  - **Keep Edge:** Roll with +1 Edge, face "Heavily Armored" (Success → Conflict)
  - **Trade Edge:** Roll base pool, negate "Heavily Armored" (Success stays Success)

**Design Note:** This creates before-roll tactical decisions. High Edge + high Complications = interesting resource allocation puzzle.

---

## System-Specific Implementation

All three resolution systems use the same Trait/Complication framework. The difference is in how Edge/Bane modify rolls.

### Xd6 Count-Successes

**Edge:** +1d to pool (cap +3d)  
**Bane:** -1d from pool (cap -3d)  
**Minimum pool:** 1d6

**Edge Trading:** Before rolling, trade Edge 1:1 to negate Complications

**Example:** 3d6, roll [5, 5, 4] = 2 successes = Success
- 1 uncanceled Complication → Success becomes Conflict
- With relevant Trait on Conflict → Choose Critical Effect (e.g., Greater Effect marks 2 ticks despite Conflict)

---

### Forged in the Dark

**Edge:** +1d to pool (cap +3d)  
**Bane:** -1d from pool (cap -3d)  
**Minimum pool:** Roll 2d6, take lowest

**Edge Trading:** Before rolling, trade Edge 1:1 to negate Complications

**Example:** 3d6, roll [6, 4, 2] = Success (highest is 6)
- 1 uncanceled Complication → Success becomes Conflict
- With relevant Trait on Conflict → Choose Critical Effect (e.g., Greater Effect marks 2 ticks despite Conflict)

---

### 2d10+Modifier

**Edge:**  
- 1 Edge: Roll 3d10, drop lowest
- 2 Edge: Roll 4d10, drop 2 lowest
- 3 Edge: Roll 5d10, drop 3 lowest (cap)

**Bane:**  
- 1 Bane: Roll 3d10, drop highest
- 2 Bane: Roll 4d10, drop 2 highest
- 3 Bane: Roll 5d10, drop 3 highest (cap)

**Edge Trading:** Before rolling, trade Edge 1:1 to negate Complications

**Thresholds:** ≤10 Setback, 11-15 Conflict, 16-20 Success, 21+ Triumph

**Example:** Roll [12, 8] + 3 = 15 total = Conflict
- With relevant Trait on Conflict → Choose Critical Effect (e.g., Greater Effect marks 2 ticks despite Conflict)

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

Encourage players to engage with both Edge and Complications:

**Before Rolling:**
- **Position tactically** (flanking, high ground, cover) → grants Edge (can keep for dice OR trade for Complication negation)
- **Work together** (Quick Assist, Create Opportunity from prior rolls) → grants ally Edge
- **Spend Momentum** → gain Edge (versatile: improve roll OR negate Complication)
- **Prepare** (scout, gather intel, acquire tools) → grants Edge or reveals exploitable Traits
- **Trade Edge strategically** → Resource allocation: keep for better roll vs trade for outcome security

**After Rolling:**
- **Invoke relevant Traits** → Gain Critical Effect (Greater Effect, Secondary Effect, Create Opportunity)
- **Choose Critical Effect wisely** → Match effect to situation (mark ticks, disarm, set up ally)

**Reward creative tactics with Edge.** When facing multiple Complications, Edge trading creates meaningful before-roll decisions. Traits create dramatic after-roll moments. Together they form layered tactical depth.

---

## Quick Reference

### Traits
**When relevant Trait applies (after rolling):**
- **On Conflict or Success:** Choose one Critical Effect
- **On Triumph:** Choose two Critical Effects
- **On Setback:** Cannot invoke Trait

### Critical Effects (choose one, or two on Triumph)
1. **Greater Effect** — Mark 2 ticks, ask 6 questions, gain 4 Edge (the first time you use it)
2. **Secondary Effect** — Produce additional consequence (Take Something, Inflict Condition, Affect Multiple Targets, etc.)
3. **Create an Opportunity** — Grant ally 1 Edge OR negate 1 Complication for their next related action

### Edge Trading
**Before rolling:** Trade Edge 1:1 to negate Complications
- Keep Edge for better dice roll (probability boost)
- Trade Edge to negate Complications (outcome security)
- Maximum ±3 Edge across all systems

### Complications
- Challenge Traits impose Complications
- Each Complication reduces outcome by 1 tier (Success → Conflict → Setback → Taken Out)
- Negate with Edge trading (before roll), Create Opportunity (Critical Effect), or certain Talents (automatic)
- Triumph ignores all Complications

### Challenge Tier
- **Tier 1:** 1 Stress or minor consequence on Setback/Conflict
- **Tier 2:** 2 Stress or moderate consequence on Setback/Conflict (default)
- **Tier 3:** 3 Stress or severe consequence on Setback/Conflict

### Action Core Functions
- **Defy/Clash/Talk:** Mark 1 tick on track (Success/Conflict), or resolve immediately if simple
- **Sense:** Ask 2 questions (Success), 1 question (Conflict)
- **Know:** GM tells you useful info + gain 1 Edge the first time you roll when acting on that information (Success)
