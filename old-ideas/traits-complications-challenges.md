# Traits, Opportunities, Complications, and Challenges

This document defines how Traits, Opportunities, Complications, and Challenges work in the heroic fantasy RPG system.

For core mechanics (Actions, Approaches, Momentum, Stress), see [core-foundations.md](core-foundations.md).

---

## Traits (Special Effects)

Traits are evocative narrative descriptors defining who your character is. When a Trait is narratively relevant to your action, you gain a **Special Effect**.

### Using a Trait

**Timing: After rolling**

When a Trait is narratively relevant and you achieve **Conflict or higher**, you may invoke your Trait to gain one Special Effect:

**Special Effects:**
1. **Greater Effect** — Mark 2 ticks (instead of 1), ask 4 questions (instead of 2), or provide significantly more information
2. **Secondary Effect** — Produce additional consequence (Take Something, Inflict Condition, Affect Multiple Targets, etc.)
3. **Build Momentum** — Grant 1 Momentum to yourself or an ally

**Examples:**
- "Veteran of the Iron Wars" → Relevant when Clashing in melee → On Conflict+, choose Special Effect (e.g., Greater Effect to mark 2 ticks, or Secondary Effect to disarm enemy)
- "Silver Tongue" → Relevant when Talking to influence → On Conflict+, choose Special Effect (e.g., Greater Effect to mark 2 ticks on Accord Track, or Secondary Effect to shift attitude dramatically)
- "Shadowborn" → Relevant when acting in darkness/stealth → On Conflict+, choose Special Effect (e.g., Build Momentum to grant 1 Momentum to ally, or Secondary Effect to remain undetected)

---

### Trait Rules

**Only one Trait per roll.** You cannot invoke multiple Traits (even if multiple are relevant).

**Requires Conflict or higher.** If you roll Setback, you cannot invoke your Trait (you failed completely).

**On Triumph:** You can still invoke your Trait for one Special Effect, in addition to gaining Momentum and ignoring Complications.

**Narrative relevance required.** The GM is the final arbiter of whether a Trait applies to the situation.

---

### Trait Breadth

**Traits should be broad enough to apply frequently, but not so broad they apply to everything.**

**Good Traits:**
- "Bladedancer" — applies to any melee combat with a blade
- "Shadow of the Thieves Guild" — applies to stealth, social situations with criminals, lockpicking, deception
- "Veteran of the Iron Wars" — applies to combat, military knowledge, dealing with soldiers

**Too Broad:**
- "Competent" — applies to everything (not interesting)
- "Lucky" — could justify any situation (no fictional grounding)

**Too Narrow:**
- "Longsword Expert vs Knights" — only applies in one very specific situation
- "Knows Fire Elemental Weaknesses" — one-use knowledge

**Aim for 3-5 Traits per character** that cover different aspects of their identity and expertise.

---

### Example: Warrior Attacks Armored Knight

**Setup:**
- Warrior has "Bladedancer" Trait (relevant to melee combat)
- Enemy: Tier 2 Knight with "Heavily Armored" (1 Complication)
- Warrior's base pool: 3d6 (Approach 3)

**Warrior's Turn:**
- Roll 3d6 → Success
- Apply "Heavily Armored" Complication → Success reduced to Conflict
- Invoke "Bladedancer" Trait → Choose Greater Effect
- Final: Mark 2 ticks (instead of 1), take 2 Stress

**Analysis:** Trait doubled output (2 ticks vs 1 tick) at no cost. Strong, consistent value.

---

### Example: Scout Creates Opportunity for Warrior

**Setup:**
- Scout has "Tactical Genius" Trait (relevant to battlefield analysis)
- Scout uses Sense to spot opening for ally
- Scout's pool: 3d6

**Scout's Turn:**
- Roll 3d6 → Success
- Ask 2 questions (Sense base effect)
- Invoke "Tactical Genius" → Choose Build Momentum
- Grant Warrior: 1 Momentum

**Warrior's Next Turn:**
- Warrior spends 1 Momentum on Act with Potency (gains +1d and ignores 1 Complication)
- Roll 4d6 → Success
- "Heavily Armored" ignored by Potency
- Final: Mark 1 tick, no Stress (clean Success)

**Analysis:** Scout's Trait granted Momentum, allowing Warrior to use Act with Potency to ignore the Complication. Teamwork enabled by Build Momentum.

---


## Complications

**Complications** reduce your outcome by **-1 tier** after rolling.

**Tier Shift:** Triumph → Success → Conflict → Setback → Taken Out

*Note: Triumph ignores all Complications (cannot be reduced)*

### Sources of Complications

1. **Challenge Traits** - Significant enemies/obstacles have defensive Complications
2. **Environmental Hazards** - GM may impose Complications for dangerous situations

### How Complications Work

Each uncanceled Complication moves your result one step down:

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
- Anything less than Triumph → Taken Out

### Rules

- **Unlimited stacking** (but most enemies have 0-2 Complications)
- **Triumph immunity:** Triumph cannot be reduced by Complications

---

## Negating Complications

Three ways to deal with Complications:

### 1. Build Momentum (Trait Special Effect)

**The primary way** to neutralize Complications is by allies using **Build Momentum** to negate them.

**Example:**
- Enemy has "Heavily Armored" (1 Complication)
- Ally used their Trait to **Build Momentum** for you (negate 1 Complication)
- You roll Success
- Complication negated → Success stays Success

**Teamwork is key!** Allies set each other up by creating Opportunities to overcome defended targets.

### 2. Talents (Automatic)

Some Talents negate Complications automatically in specific situations.

**Example:**
- Enemy has "Heavily Armored" + "Shielded" (2 Complications)
- Your "Shield Breaker" Talent automatically negates shield-related Complications
- "Shielded" negated automatically, "Heavily Armored" remains

### 3. Triumph Ignores All Complications

**Triumph results cannot be reduced.** No matter how many Complications exist, Triumph stays Triumph.

**This makes Triumph extremely valuable against heavily defended targets.**

---

## Resolution Priority

**Order of resolution:**

1. **GM states Complications** present on this Challenge
2. **Calculate Edge and Bane** from all sources (cancel 1:1)
3. **Roll dice** with modified pool
4. **Determine raw outcome** (Success, Conflict, Setback, Triumph)
5. **Apply Complications** (reduce tier, Triumph ignores all)
6. **Determine final outcome**
7. **If Trait relevant and outcome is Conflict+:** Invoke for Special Effect

**Full Example:**
- You attack a knight with "Heavily Armored" (1 Complication)
- You have "Bladedancer" Trait (relevant) and 1 Edge (positioning)
- **Roll:** 4d6 (base 3d6 + 1 Edge) → Result: Success
- **Apply Complication:** "Heavily Armored" → Success reduced to Conflict
- **Invoke Trait:** "Bladedancer" relevant, Conflict qualifies → Choose Greater Effect
- **Final outcome:** Mark 2 ticks (Greater Effect), take 2 Stress (Conflict cost)

**Analysis:** Even with Complication reducing you to Conflict, your Trait's Greater Effect doubled your progress.

---

## Challenge Design

Challenges are adversaries, obstacles, or situations that oppose the PCs. They have Challenge Traits that impose Complications.

### Impact Move Severity

**When GM makes Impact Moves on Conflict or Setback:**

**Soft Impact Move (on Conflict):**
- Mark 1 Stress OR other soft consequence (lose position, reveal danger, etc.)
- Examples: Glancing blow, minor setback, warning sign

**Hard Impact Move (on Setback):**
- Mark 2 Stress OR other hard consequence (Condition tier, lose equipment, dramatic shift)
- Examples: Solid hit, major setback, severe consequence

**Severe Consequences (rare, dramatic moments):**
- Mark 3 Stress OR Severe Condition tier OR Taken Out
- Reserved for: Boss abilities, environmental disasters, catastrophic failures

**GM Note:** Default to 1 Stress (Conflict) or 2 Stress (Setback) for most Impact Moves. Use Conditions and other consequences for variety and narrative weight.

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

**Balance Note:** More Traits = more preparation required. Challenges with 2+ Complications usually require allies to Create Opportunities OR Triumph to succeed cleanly.

---

### Challenge Examples

**Tier 1 Goblin Scout**
- **Tier:** 1 (1 Stress on Setback/Conflict)
- **Traits:** "Easily Frightened"
  - When intimidated, grants 1 Edge to PCs
- **Harm Track:** 2 ticks to defeat

**Tier 2 Armored Knight**
- **Tier:** 2 (2 Stress on Setback/Conflict)
- **Traits:** "Heavily Armored"
  - Physical attacks face 1 Complication (Success → Conflict)
- **Harm Track:** 4 ticks to defeat

**Tier 3 War Troll**
- **Tier:** 3 (3 Stress on Setback/Conflict)
- **Traits:** "Tough Hide," "Regeneration"
  - Physical attacks face 2 Complications (Success → Setback)
  - Requires exploiting weakness (fire, magic), using Traits, or Triumph
- **Harm Track:** 6 ticks to defeat

**Tier 2 Ancient Vault Door**
- **Tier:** 2 (2 Stress on Setback/Conflict)
- **Traits:** "Sealed," "Warded"
  - Bypass attempts face 2 Complications
  - Can be defeated by finding key, dispelling wards, or using Traits
- **Obstacle Track:** 6 ticks to bypass

---

## Edge & Bane Interaction

**Edge and Bane** modify your dice roll. **Complications** reduce your outcome tier. These are separate systems.

### Edge/Bane Sources

**Edge:**
- Easy tasks (1 Edge)
- Act with Potency Momentum spend (1 Edge)
- Talents
- Ally assistance (Quick Assist)
- Superior positioning
- Favorable environment

**Bane:**
- Hard tasks (1 Bane)
- Very Hard tasks (2 Banes)
- Conditions (count checked boxes)
- Hostile environment
- Poor positioning

**Edge and Bane cancel 1:1 before rolling.**

**Cap:** Maximum ±2 Edge/Bane per roll.

**Pool range:** 3d6 (worst case) to 7d6 (best case at Approach 5 + 2 Edge)

---

## Resolution Mechanics

**Dice Pool:** Xd6 (Approach + Edge - Bane)

**Edge:** +1d to pool (cap +3d)  
**Bane:** -1d from pool (cap -3d)  
**Minimum pool:** Roll 2d6, take lowest

**Outcome (highest die matters):**
- All 1-3: Setback
- Any 4-5: Conflict
- Any 6: Success
- Two+ 6s: Triumph

**Example:** 3d6, roll [6, 4, 2] = Success (highest is 6)
- 1 uncanceled Complication → Success becomes Conflict
- If you used Trait with Greater Effect → Mark 2 ticks despite Conflict

See [resolution.md](resolution.md) for complete dice mechanics and probability tables.

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

**Balance:** More Traits = more teamwork required. 2+ Complications means PCs need allies to Build Momentum or use Act with Potency, or roll Triumph to succeed cleanly.

---

### Communicating Stakes

**Always telegraph before the roll:**

> **GM:** "The Armored Knight has 'Heavily Armored' and 'Shielded'—that's 2 Complications. If you roll Success, it'll drop to Setback. Anyone have Traits that could help?"

> **Player:** "I don't have a relevant Trait for this attack."

> **Alice:** "I could use my 'Tactical Genius' Trait on my Sense check to Build Momentum—grant you 1 Momentum so you can use Act with Potency to ignore one of his Complications."

> **GM:** "That would help! Alice, go ahead."

**Clear communication about Complications creates tactical teamwork. Players coordinate who helps whom.**

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

Encourage players to coordinate and leverage the three tactical layers:

**Edge/Bane Layer (Probability):**
- **Position tactically** (flanking, high ground, cover) → grants Edge
- **Quick Assist** → Mark Stress to grant ally Edge
- **Act with Potency** → Spend Momentum for Edge + ignore 1 Complication
- **Edge improves your roll** but doesn't negate Complications

**Complication Layer (Outcome):**
- **Build Momentum** (Special Effect from Trait) → Grant 1 Momentum to ally so they can use Act with Potency
- **Act with Potency** → Spend 1 Momentum to ignore 1 Complication (+ gain Edge + narrative permission)
- **Coordinate** → Use Traits to set up allies against heavily defended targets
- **Triumph** → Ignores all Complications automatically

**Trait Layer (Effects):**
- **Invoke Trait** → Gain Special Effect on Conflict+ (after rolling)
- **Choose Special Effect wisely** → Greater Effect for doubled progress, Secondary Effect for bonus consequence, Build Momentum for teamwork

**Reward teamwork!** Heavily defended enemies (2+ Complications) require allies to Build Momentum for Act with Potency or rolling Triumph. Solo players struggle; coordinated teams thrive.

---

## Quick Reference

### Traits
**When Trait is narratively relevant (after rolling):**
- **On Conflict or Success:** Choose one Special Effect
- **On Triumph:** Choose one Special Effect (still gain Momentum + ignore Complications)
- **On Setback:** Cannot invoke Trait

### Special Effects (choose one when invoking Trait)
1. **Greater Effect** — Mark 2 ticks, ask 4 questions, or provide significantly more information
2. **Secondary Effect** — Produce additional consequence (Take Something, Inflict Condition, Affect Multiple Targets, etc.)
3. **Build Momentum** — Grant 1 Momentum to yourself or an ally

### Complications
- Reduce outcome by -1 tier (Triumph → Success → Conflict → Setback → Taken Out)
- Unlimited stacking (most enemies have 0-2)
- Sources: Challenge Traits, environmental hazards
- Negate with: Build Momentum (grant 1 Momentum), Talents (auto-negate specific), Triumph (ignores all)

### Edge & Bane
- Edge: +1d to pool (cap ±3), improves roll probability
- Bane: -1d from pool (cap ±3), worsens roll probability
- Cancel 1:1
- Separate system from Complications

### Impact Moves
- **Soft (Conflict):** Mark 1 Stress or other soft consequence
- **Hard (Setback):** Mark 2 Stress or other hard consequence (Condition tier, lose equipment, dramatic shift)
- **Severe (rare):** Mark 3 Stress or Severe Condition tier or Taken Out (boss abilities, disasters)

### Action Core Functions
- **Defy (Overcome):** Mark 1 tick on Obstacle track (Success/Conflict), or automatically overcome simple tasks
- **Clash (Harm):** Mark 1 tick on Harm track (Success/Conflict), or outright defeat weaker foes
- **Talk (Influence):** Mark 1 tick on Accord track (Success/Conflict), or outright convince lesser creatures
- **Sense (Assess):** Ask 2 questions (Success), 1 question (Conflict)
- **Know (Recall):** GM tells you something useful (Success)
