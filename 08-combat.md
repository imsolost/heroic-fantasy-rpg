# Combat Design - Brainstorming

**Goal:** Adapt Dungeon World 2's combat flow for our heroic fantasy system (works for both Xd6 pool and 2d10+X variants)

---

## What We Like From Dungeon World 2 Combat

Based on DW2 analysis and the general PbtA approach:

### 1. **"What Do You Do?" Structure**
- Combat isn't a separate mode with initiative rolls and rigid turn order
- GM presents situation/threat, asks "What do you do?"
- Player describes action in fiction
- Action triggers appropriate Move (Clash, Defy, etc.)
- GM makes soft/hard move based on result

### 2. **Spotlight System (No Initiative)**
- Fluid turn order based on fiction
- GM asks individual PC or group "What do you do?"
- Spotlight passes based on urgency, positioning, dramatic timing
- Can go clockwise for structure when no clear fictional priority
- Urgent threats interrupt turn order naturally

### 3. **Player-Facing Rolls Only**
- GM never rolls dice for NPC attacks
- When enemy attacks PC, PC rolls Defy (or Clash if counterattacking)
- Failure = GM makes hard move (enemy succeeds)
- Conflict = partial success (you resist but at cost)
- Success = you avoid/counter the threat

### 4. **Soft Moves vs Hard Moves**
- **Soft move** = setup, telegraph ("The orc raises his club to smash you")
- **Hard move** = follow-through, consequence ("The club connects, take damage and mark Stress")
- Soft moves on partial success (Conflict) or proactive
- Hard moves on failure or when follow-through is earned
- Creates tension without arbitrary damage

### 5. **GM Moves List**
Standard GM moves for combat:
- Deal damage
- Put someone in a spot
- Separate them
- Reveal an unwelcome truth
- Use up their resources
- Show signs of approaching threat
- Offer an opportunity (with or without cost)

### 6. **Combat as Conversation**
Not separate from rest of game — just more dangerous conversations. Exchange of fictional actions and consequences, punctuated by rolls when outcome uncertain.

---

## Adapting for Our System

### Core Actions in Combat

**Clash** — Attack, inflict harm, engage directly
- **Trigger:** When you attack an enemy in melee or ranged combat
- **Outcomes:**
  - **Failure (0 Hits / ≤10):** Enemy strikes you, GM makes hard move
  - **Conflict (1 Hit / 11-15):** You strike enemy but suffer consequence (counterattack, exposed position, use resource)
  - **Success (2 Hits / 16-20):** You strike enemy cleanly
  - **Triumph (3+ Hits / 21+):** You strike enemy + gain advantage (create opening, position ally, earn Momentum)

**Defy** — Resist harm, avoid danger, act under pressure
- **Trigger:** When you resist an enemy attack, dodge danger, push through obstacles
- **Outcomes:**
  - **Failure:** Danger overtakes you, GM makes hard move
  - **Conflict:** You resist but at cost (mark Stress, worse position, lose resource)
  - **Success:** You avoid danger cleanly
  - **Triumph:** You avoid danger + create opening (gain Momentum, counter-position)

**Sense** — Read enemy, spot weakness, assess battlefield
- **Trigger:** When you study enemy movements, look for openings, assess tactical situation
- **Outcomes:**
  - **Failure:** You misread the situation, GM makes hard move (enemy capitalizes on your distraction)
  - **Conflict:** You learn something but tip your hand or miss something important
  - **Success:** Ask GM questions about enemy (weakness, intent, danger) or gain Edge on next action against them
  - **Triumph:** Ask questions + gain Edge, or grant ally Edge

---

## Combat Flow Example

**GM:** "The bandit captain roars and charges at Kael, greatsword raised. What do you do?"

**Kael (Player):** "I sidestep and try to trip him as he passes."

**GM:** "That's Defy with Grace. Roll it."

**Kael:** *Rolls 3d6 (Approach 2 + Trait), gets 1 Hit* "Conflict."

**GM:** "You dodge the swing but his momentum bowls you over. You're on the ground (Complication: -1d on next roll). He recovers fast — what do you do?"

**Kael:** "I roll to the side and scramble to my feet."

**GM:** "Okay, you're up, but he's already coming at you again. What do you do?"

**Kael:** "I want to Sense his pattern — he's overcommitting on these big swings."

**GM:** "Roll Sense with Cunning."

**Kael:** *Rolls 4d6 (Approach 3), gets 2 Hits* "Success!"

**GM:** "Yeah, he's reckless. Every time he swings, he's wide open for a moment. You have Edge on your next Clash against him."

**Kael:** "Perfect. When he swings again, I duck under and go for his ribs."

**GM:** "That's Clash with Grace. You have Edge from spotting his pattern."

**Kael:** *Rolls 4d6 (Approach 2 + Trait 1d + Edge 1d), gets 3 Hits* "Triumph!"

**GM:** "Your blade slips through his guard and bites deep. He staggers back, clutching his side. You've got him off-balance — gain 1 Momentum. He's still standing but winded. What do you do?"

---

## Design Questions to Answer

### Q1: How Do We Handle Multiple Combatants?

**Option A: Spotlight Rotation**
- GM asks each PC "What do you do?" in turn (or as fiction demands)
- GM describes enemy actions as soft moves between PC actions
- Fast but risks losing sense of simultaneous action

**Option B: Exchange System**
- PCs declare intents (not locked in)
- GM describes what enemies are doing
- Resolve in fictional order (who acts first based on positioning/initiative)
- More structured but slower

**Option C: Hybrid**
- Default to spotlight rotation
- When multiple things happening at once, zoom out: "Okay, Kael you're facing the captain, Mira the archers are targeting you, Ryn the scout is flanking. What are you all doing?"
- Resolve based on urgency/positioning

### Q2: What About Enemy HP/Defeat?

**Option A: HP Tracking**
- Enemies have HP
- Successful Clash deals damage (base + weapon + approach bonus?)
- At 0 HP, enemy is defeated
- Transparent, familiar

**Option B: Clocks (FitD style)**
- Each enemy is a 4-segment, 6-segment, or 8-segment clock
- Successful Clash marks segments (1 for Success, 2 for Triumph?)
- When clock fills, enemy defeated
- More abstract, hides exact "durability"

**Option C: Narrative Milestones**
- No HP/clocks tracked
- GM judges when enemy should fall based on fictional events
- "After taking three solid hits and a critical strike, the captain falls"
- Fastest, most abstract, requires GM judgment

### Q3: How Do Enemies "Attack"?

**Option A: GM Makes Soft Move, PC Rolls Defy**
- GM: "The orc swings at you" (soft move)
- PC: "I dodge" → rolls Defy
- Failure = hard move (you take damage)
- Conflict = cost (mark Stress or worse position)
- Success = clean dodge

**Option B: Enemy Attacks are Hard Moves After PC Failure**
- PC only rolls when taking proactive action
- If PC fails Clash, GM makes hard move ("the enemy counterattacks, dealing damage")
- If PC succeeds Clash, enemy doesn't get to respond
- Risk is baked into PC action

**Option C: Danger Roll (Hybrid)**
- When PC is in danger but not acting, GM calls for "Danger Roll"
- Roll Defy vs. the threat
- Similar to Option A but explicit about when it happens

### Q4: What About Positioning/Range?

**Option A: Zones (FitD/STA2e style)**
- Combat area divided into zones: Close, Near, Far
- Moving zones = action or Defy roll if contested
- Ranged attacks penalized across zones (Bane/Complication)
- Simple, theater-of-mind friendly

**Option B: Narrative Positioning**
- No mechanical zones
- GM tracks position fictionally ("You're pinned behind the pillar," "You're in the thick of melee")
- Position grants Edge or imposes Complications as fiction demands
- Fastest, most abstract

**Option C: Tactical Grid**
- 5-foot squares or hex grid
- Movement speeds, opportunity attacks, flanking bonuses
- Slowest, most tactical, least fitting with narrative-first design

### Q5: How Do We Handle Armor?

**Option A: Passive Damage Reduction (Traditional)**
- Armor provides damage reduction (light/medium/heavy = -1/-2/-3 damage)
- Always on, no decisions

**Option B: Armor as Resource (DW2 style)**
- Armor has uses (1-3 depending on type)
- When you would take damage, spend a use to negate it
- Creates "save it for critical hit" decisions
- Uses restore on rest/repair

**Option C: Armor as Edge**
- Armor grants Edge on Defy rolls against physical attacks
- Light armor = 1 Edge, Heavy armor = 2 Edges
- No damage reduction, just better defense rolls

---

## Initial Recommendations

Based on "heroic fantasy with cost" and "narrative-first" pillars:

### Recommended: Fluid Spotlight + Soft/Hard Moves

**Combat Flow:**
1. GM frames situation, describes threats
2. GM asks PC(s) "What do you do?"
3. PC describes action in fiction
4. If uncertain outcome, trigger appropriate Action (Clash, Defy, Sense)
5. Based on outcome:
   - **Success/Triumph:** PC succeeds, GM describes result
   - **Conflict:** PC succeeds with cost (mark Stress, Complication, enemy counterattack)
   - **Failure:** GM makes hard move (enemy succeeds, PC suffers consequence)
6. GM makes soft move for next threat/enemy, returns to step 2

**Enemy "Attacks":**
- Enemies don't roll
- When enemy attacks, GM makes soft move ("The captain swings at you")
- PC rolls Defy (or Clash if counterattacking)
- Result determines outcome

**Positioning:**
- Use **Zones** (Close/Near/Far)
- Position grants Edge or imposes Complications narratively
- "You have high ground" = Edge
- "You're surrounded" = Complication

**Enemy Defeat:**
- **Clocks for significant foes** (4-6-8 segments)
- **Narrative for mooks** ("You cut down the goblin")
- Success = 1 segment, Triumph = 2 segments
- Or: Use HP for transparency (enemy has 10 HP, your weapon deals 3 damage per hit)

**Armor:**
- **Armor as Resource** (DW2 style) fits "meaningful choices" pillar
- Light/Medium/Heavy = 1/2/3 uses
- Spend use to negate damage from one attack
- Restore uses on rest or downtime

---

---

## Combat System (DRAFT v1)

Based on design answers:
1. Stress common (most Conflicts/Failures), Conditions rare (dramatic). ~2 encounters per short rest (10 min)
2. Tactical positioning matters but narrative flexibility preserved (zones + fiction)
3. Mook=1 hit, Standard=2-3, Elite=4-5, Epic/Boss=6-8
4. Spotlight initiative with Momentum/Threat to seize control
5. Area attacks roll once, affect multiple targets
6. Max Stress = player choice (push through or go down)
7. Help costs something (Stress, Edge, or Momentum)

---

### Combat Structure: Spotlight Initiative

**Starting Combat:**
1. GM frames the situation, describes threats
2. GM asks "Who acts first?" or chooses based on fiction (who's surprised, who's ready, who's aggressive)
3. That PC takes action → roll if needed → resolve
4. GM makes soft move (enemy reacts, new threat emerges) or asks next PC "What do you do?"
5. Repeat

**No Initiative Rolls:** Combat flows as conversation with rolls punctuating action.

**Seizing Initiative:**
- **Player spends 1 Momentum:** "I act before [enemy/ally]" — take spotlight immediately
- **GM spends Threat:** Interrupt spotlight, enemy acts now (requires Threat pool, see GM Tools below)

**When Does Spotlight Pass?**
- After PC completes action (attack resolved, defense rolled, etc.)
- When fiction demands (urgent threat, surprise attack)
- When GM makes soft move between PC actions
- Round-robin when no clear fictional priority

---

### Core Combat Actions

**Clash** — Attack, inflict harm
- **Trigger:** You attack an enemy
- **Outcomes:**
  - **Failure:** Enemy counters, GM makes hard move (you take damage/Stress, worse position)
  - **Conflict:** You strike but suffer consequence (mark Stress, enemy counters, lose position)
  - **Success:** You strike cleanly, deal damage
  - **Triumph:** You strike + advantage (deal damage, gain Momentum, create opening for ally)

**Defy** — Resist, dodge, endure
- **Trigger:** You resist enemy attack, avoid danger, push through obstacles
- **Outcomes:**
  - **Failure:** Danger overtakes you (mark Stress, suffer consequence)
  - **Conflict:** You resist partially (mark Stress OR accept Complication)
  - **Success:** You avoid danger cleanly
  - **Triumph:** You avoid + create opening (gain Momentum, reposition, Edge on next action)

**Sense** — Assess, read enemy, spot weakness
- **Trigger:** You study enemy, assess battlefield, look for openings
- **Outcomes:**
  - **Failure:** Misread situation, enemy capitalizes (GM hard move)
  - **Conflict:** Learn something but tip your hand or miss detail
  - **Success:** Ask GM 1-2 questions about enemy (weakness? intent? danger?) OR gain Edge on next action against them
  - **Triumph:** Ask questions AND gain Edge, OR grant Edge to ally

**Talk** — Distract, intimidate, command, taunt
- **Trigger:** You attempt to influence enemy through words (intimidate, distract, command surrender)
- **Outcomes:**
  - **Failure:** Enemy ignores or uses it against you
  - **Conflict:** Brief effect but backfires (they're distracted but enraged)
  - **Success:** Enemy hesitates, flees, or reacts as you intend
  - **Triumph:** Enemy acts as intended + you gain advantage (Edge, Momentum, create opening)

**Know** — Recall weakness, identify magic, analyze tactics
- **Trigger:** You recall lore about enemy type, identify spell being cast, analyze battle tactics
- **Outcomes:**
  - **Failure:** False information or waste critical time
  - **Conflict:** Information but incomplete or comes with cost
  - **Success:** GM reveals useful information (weakness, resistance, tactic)
  - **Triumph:** Detailed information + tactical advantage (Edge on related actions, negate enemy ability)

---

### Damage & Harm

**Stress & Impact Moves:**
This system uses Stress marking via Impact Moves rather than damage/harm:

- **Soft Impact Move (Conflict):** Mark 1 Stress
- **Hard Impact Move (Setback):** Mark 2 Stress
- **Severe consequences (rare):** Mark 3 Stress or Condition tiers

**Alternative: Harm-Based (if using traditional damage):**
- **Success:** Deal 1 Harm
- **Triumph:** Deal 2 Harm
- Mark Stress equal to Harm suffered
- Light/Medium/Heavy weapons scale Harm (1/1/2)

**Area Attacks:**
- Roll once
- Apply result to all targets in area
- Each target can Defy separately (if they have actions/reactions available)
- Or: Affect all, but each target marks less Harm (1 Harm divided among targets, GM discretion)

---

### Combat Maneuvers

Beyond dealing damage, PCs can attempt tactical maneuvers. These can be implemented as **Opportunity effects** (spend Momentum for effect) or **Talent-gated moves** (requires specific Talent).

**Standard Maneuvers:**

**Disarm** — Remove enemy's weapon
- **Trigger:** Clash or Defy with intent to disarm
- **Effect (on Success/Triumph):** Enemy drops weapon, must spend action to retrieve or draw backup
- **Better as:** Opportunity effect (costs 1 Momentum) or Triumph bonus

**Knockdown** — Put enemy on ground
- **Trigger:** Clash with intent to trip/shove
- **Effect (on Success/Triumph):** Enemy falls prone, gains Complication "Prone" (-1 to relevant actions, must spend movement to stand)
- **Better as:** Triumph bonus or Talent-enhanced Clash

**Pin Down** — Restrict movement
- **Trigger:** Clash or Defy with intent to grapple/entangle
- **Effect (on Success/Triumph):** Enemy can't move zones without Defying (Conflict = breaks free but you gain Edge, Success = breaks free cleanly)
- **Better as:** Sustained action (you're also pinned until one of you breaks free)

**Pull / Push** — Reposition enemy
- **Trigger:** Clash or Defy with intent to shove/pull
- **Effect (on Success/Triumph):** Move enemy one zone (into hazard, off ledge, away from ally)
- **Better as:** Opportunity effect or environmental combo

**Sunder** — Damage gear to reduce effectiveness
- **Trigger:** Clash targeting enemy's weapon/armor/shield
- **Effect (on Triumph):** Reduce enemy armor uses by 1, or impose Complication on their attacks (weapon damaged)
- **Better as:** Talent-gated move (requires weapon expertise)

**Feint / Create Opening** — Set up ally
- **Trigger:** Sense or Clash with intent to create advantage
- **Effect (on Success/Triumph):** Ally gains Edge on next action against that enemy
- **Better as:** Default Triumph option or Sense result

**Design Note:** Don't create separate rolls for each maneuver. Use existing Actions (Clash, Defy, Sense) with declared intent. Success/Triumph produces the maneuver effect based on fiction. Talents can make specific maneuvers more reliable or powerful.

---

### Enemy Durability

**Mooks (1 HP):**
- One successful Clash defeats them
- Fast, disposable threats
- Examples: Goblins, bandits, zombies

**Standard Foes (2-3 HP):**
- Takes 2-3 hits to defeat
- Represent competent opposition
- Examples: Orc warriors, trained soldiers, wolves

**Elite Warriors (4-5 HP):**
- Takes 4-5 hits to defeat
- Dangerous, skilled combatants
- Examples: Knight captain, veteran mercenary, owlbear

**Epic Foes / Bosses (6-8+ HP):**
- Takes 6-8+ hits to defeat
- May have special abilities (see Epic Foe design below)
- Examples: Dragon, demon lord, ancient lich

**Alternative: Clocks Instead of HP**
- Mook = 2-segment clock (1 Success + 1 Success, or 1 Triumph)
- Standard = 4-segment clock
- Elite = 6-segment clock
- Epic = 8+ segment clock
- Success marks 1 segment, Triumph marks 2 segments

---

### Positioning & Zones

**Zone System:**
Combat areas divided into abstract zones:
- **Close:** Same zone, melee range
- **Near:** Adjacent zone, short move or ranged attack
- **Far:** 2+ zones away, long move or distant ranged

**Movement:**
- Move to Near zone = free (part of your action)
- Move to Far zone = costs action OR Defy roll if contested
- Moving through enemy zone = Defy roll (they try to stop you)

**Positioning Benefits:**
- **High ground, cover, flanking, advantageous terrain:** Gain Edge
- **Pinned down, surrounded, disadvantageous terrain:** Suffer Complication (Bane in 2d10 system)
- GM judges based on fiction

**Ranged Attacks:**
- Close range: No penalty
- Near range: No penalty if unobstructed
- Far range: Suffer Complication unless weapon has "Long Range" tag

---

### Armor

**Armor as Resource (Optional):**

Armor has **uses** representing structural integrity:
- **Light armor:** 1 use
- **Medium armor:** 2 uses
- **Heavy armor:** 3 uses

**When You Would Mark Stress from Physical Attack:**
- Spend 1 armor use to **negate the Stress entirely**
- Or take the Stress and preserve armor for later

**Restoring Armor:**
- Short rest: Restore 1 use
- Long rest: Restore all uses

**Design Note:** Creates tactical decision: "Do I burn armor now or save it for the big hit?"

---

### Stress, Conditions & Being Taken Out

**For complete rules**, see [05-resilience.md](05-resilience.md).

**Stress Track:** 5 boxes

**Marking Stress:**
- Soft Impact Move (Conflict) = mark 1 Stress
- Hard Impact Move (Setback) = mark 2 Stress
- Voluntary: Quick Assist (1 Stress), Push Yourself (1 Stress)

**At Maximum Stress:**
When Stress track is full and you would mark more, choose: **take a Burden or be Taken Out**.

**Conditions:**
Named temporary impairments with tiers (1-3):
- Each Condition = 1 Bane to all rolls
- Multiple Conditions stack, maximum 2 Banes from Conditions total
- Tier represents duration: reduces by 1 per relevant action roll
- All Conditions clear on short rest (10-15 minutes)
- Common names: Poisoned, Frightened, Blinded, Stunned, Bleeding, Prone, etc.

**Burdens (Persistent Conditions):**
- Function like Conditions but do NOT clear on short rest
- Most common source: Stress overflow (choose Burden over being Taken Out)
- Tick down through action or require narrative resolution
- Mark clearly: "Wounded 3 (Burden)"

**Gaining Conditions:**
- From Challenge Moves (enemy abilities inflict directly)
- From Impact Moves (GM may inflict tier 1 alongside Stress)
- From Stress Overflow (becomes a Burden if you choose to stay in the fight)

**Taken Out:**
- Stress track full + you choose not to take a Burden
- Unconscious, fleeing, captured (GM narrates based on context)

---

### Helping Allies

**Quick Assist (Mark 1 Stress):**
- Describe how you help ally
- Mark 1 Stress to grant ally 1 Edge on their roll
- Doesn't consume your action

**Use Action to Aid:**
- Use your action to set up ally
- Ally gains Edge on their next roll
- Costs your action but no Stress

**Build Momentum (Trait Special Effect):**
- When you invoke a Trait, choose Build Momentum
- Grant 1 Momentum to yourself or ally
- Ally can spend it on Act with Potency (Edge + ignore Complication + narrative permission)

**Design Note:** Quick Assist is heroic and immediate. Build Momentum enables Act with Potency for big moments.

---

### GM Tools for Combat

**Threat Pool (Optional):**
- GM starts combat with Threat = number of PCs (2-5 Threat)
- **Earn Threat:** When PC rolls Failure, gain 1 Threat
- **Spend Threat:**
  - Seize initiative (1 Threat): Enemy acts immediately, interrupt spotlight
  - Activate enemy ability (1-3 Threat): Trigger special move, area attack, powerful effect
  - Reinforce (2 Threat): Additional enemies arrive

**GM Moves for Combat:**
- Deal damage (mark Stress)
- Put someone in a spot (force hard choice)
- Separate them (split party, isolate PC)
- Reveal unwelcome truth (enemy reinforcements, trap triggers)
- Use up their resources (damage armor, consume item)
- Show signs of threat (telegraph incoming danger)
- Offer opportunity with cost (opening but risky)

**Soft vs. Hard Moves:**
- **Soft move:** Setup, telegraph danger ("The orc raises his axe")
- **Hard move:** Follow-through, consequence ("The axe bites deep, mark 2 Stress")
- Use soft moves on Conflict or to set up danger
- Use hard moves on Failure or when consequences earned

---

### Enemy Roles & Behavior (Grimwild Pattern)

Design enemies with **Role** and **Tier** to create variety:

#### **Roles** (Behavior Patterns)

**Brute:**
- High damage, low defense
- Charges into melee, ignores tactics
- Deals 2 Harm, easy to hit

**Defender:**
- Protects allies, intercepts attacks
- Can impose Complication "Blocked" (must get past defender)
- Moderate Harm (1-2), hard to bypass

**Blaster:**
- Ranged attacks, area effects
- Stays at distance, targets multiple PCs
- Moderate Harm (1-2), fragile up close

**Controller:**
- Inflicts Conditions, manipulates battlefield
- Uses Talk/Know actions to hinder PCs
- Low Harm, high annoyance

**Skirmisher:**
- Mobile, hit-and-run tactics
- Moves between zones freely, hard to pin down
- Low Harm (1), slippery

#### **Tiers** (Power Scaling)

| Tier | HP | Description |
|------|-----|-------------|
| **Mook** | 1 | One hit, done |
| **Tough** | 2-3 | Standard opponent |
| **Elite** | 4-5 | Dangerous individual |
| **Boss** | 6-8+ | Epic encounter |

**Combine Role + Tier:**
- "Orc Brute (Tough)" = 3 HP, charges and deals 2 Harm
- "Goblin Skirmisher (Mook)" = 1 HP, mobile but fragile
- "Dragon (Boss/Blaster)" = 8 HP, breath weapon hits multiple targets

---

### Epic Foe Design (Boss Encounters)

**Epic Foes have special abilities that create tactical depth without adding core rules complexity.**

**Example Abilities:**

**Armored/Defended:**
- Clash without Edge only deals 1 Harm on Triumph, 0 on Success ("you're keeping it busy")
- Must create Opening (Sense to identify weakness, Defy to create advantage) to deal full damage

**Devastating Counterattack:**
- When you Clash and roll Failure, mark 2 Stress and gain Complication "Knocked Back"

**Frightening Presence:**
- When you first engage in combat, roll Defy
- Setback: Gain Frightened 2
- Conflict: Gain Frightened 1

**Legendary Actions:**
- After each PC's turn, epic foe gets a reaction (bite, tail sweep, spell)
- Keeps pressure on PCs, makes combat dynamic

**Multi-Phase:**
- At 50% HP, epic foe changes tactics (becomes enraged, casts major spell, reveals true form)
- Creates distinct combat phases

**Diminishing Threat (Grimwild Pattern):**
- Enemy has Morale pool (starts at 6d6, 5d6, or 4d6 depending on confidence)
- When PCs deal significant blow (Triumph, boss marked for 2+ Harm in one hit), GM rolls Morale
- **6:** Fights ferociously (enemy gains Edge on next action)
- **4-5:** Fights on, no change
- **1-3:** Morale drops, reduce pool by 1d
- **At 0d:** Enemy flees, surrenders, or becomes desperate (last-ditch all-or-nothing attack)

**Design Note:** Give bosses 2-3 special abilities maximum. More than that overwhelms. Use abilities to create the "Sense for weakness → Clash to exploit" pattern naturally.

---

## Example Combat Scene (Full Resolution)

**Setup:** Kael (warrior), Mira (ranger), and Ryn (rogue) face an Orc Warboss (Epic Foe: 8 HP, Armored, Devastating Counterattack) and 4 Orc Mooks (1 HP each).

**GM:** "The Warboss roars and charges toward Kael, dual axes raised. Four orcs fan out behind him, snarling. What do you do?"

**Kael:** "I stand my ground and brace for impact."

**GM:** "That's Defy with Daring. Roll it."

**Kael:** *Rolls Conflict (1 Hit in Xd6, or 11-15 in 2d10)* "Conflict."

**GM:** "You stop his charge, but the impact drives you back. Mark 1 Stress. He's pressing you hard — what do you do?"

**Mira:** "I shoot the Warboss in the shoulder to distract him from Kael."

**GM:** "That's Clash with Grace. He's an Epic Foe with Armored — you need an Opening to hurt him meaningfully."

**Mira:** *Rolls Success* "Success."

**GM:** "Your arrow hits his shoulder guard and bounces off. He barely notices — no damage. But you've got his attention. He turns toward you. Ryn, what do you do?"

**Ryn:** "While he's distracted, I study him for weaknesses." (Sense with Cunning)

**Ryn:** *Rolls Triumph* "Triumph!"

**GM:** "You notice the straps on his left pauldron are loose — his shoulder's exposed. Ask me a question, and you gain Edge on your next action against him."

**Ryn:** "What's the best way to hurt him?"

**GM:** "Target that exposed shoulder with a precise strike. You've identified an Opening. Anyone who acts on this info has Edge."

**Kael:** "I spend 1 Momentum to act next! I charge and go for that shoulder." (Seizing initiative, Clash with Edge from Opening)

**GM:** "Perfect. Roll Clash with Daring, you have Edge from Ryn's scouting."

**Kael:** *Rolls 5d6 (Approach 2, Trait 1, Edge 1, Momentum boost 1), gets Triumph* "Triumph!"

**GM:** "Your blade slices into the exposed shoulder. The Warboss bellows in pain. Deal 2 Harm — he's at 6/8 HP now. Gain 1 Momentum for your Triumph. But now he's enraged. He swings both axes at you wildly — what do you do?"

**Kael:** "I duck and roll away!" (Defy)

*Combat continues...*

---

## Enemy Quick Reference

### **Creating Enemies Fast (Simple Method):**

1. **Choose Role:** Brute, Defender, Blaster, Controller, or Skirmisher
2. **Choose Tier:** Mook (1 HP), Tough (2-3), Elite (4-5), Boss (6-8+)
3. **Add 1-2 descriptive traits:** "Heavily armored," "Bloodthirsty," "Cowardly"
4. **Define damage:** Mook/Tough = 1 Harm, Elite/Boss = 2 Harm, special attacks = 2-3 Harm
5. **For Bosses:** Add 2-3 special abilities

### **Enemy Stat Block Template (Structured Method):**

For more complex enemies or published adventures, use this template:

| Field | Description |
|-------|-------------|
| **Danger** | Threat level (1-3+); informs consequence severity and how many PCs needed |
| **HP / Resolve** | How much punishment before defeated (1 for mooks, 8+ for bosses) |
| **Harm** | Damage dealt on successful attacks (1-3) |
| **Traits** | Passive abilities (e.g., *Thick Hide — Reduce incoming Harm by 1*) |
| **Reactions** | Triggered abilities (e.g., *Regeneration — Recover 1 HP at end of round*) |
| **Weaknesses** | Vulnerabilities PCs can discover with Sense (e.g., "Vulnerable to fire") |

**Example Stat Block:**

> **Cave Troll**
> - **Danger:** 2 (requires 2-3 PCs to engage safely)
> - **HP:** 5
> - **Harm:** 2 (club smash), 1 to all Close (sweep)
> - **Traits:**
>   - *Thick Hide* — Reduce incoming Harm by 1 (minimum 1)
>   - *Dull-witted* — Vulnerable to Cunning approaches (PCs using Cunning gain Edge)
> - **Reactions:**
>   - *Regeneration* — Recover 1 HP at end of each round
>   - *Sweep* — When surrounded, may attack all Close targets for 1 Harm each
> - **Weaknesses:** Fire prevents regeneration for one round; bright light imposes Complication on troll

**Example:**
> **Orc Raider** (Tough, Brute)
> - HP: 3
> - Damage: 2 Harm (greataxe)
> - Traits: Bloodthirsty, Reckless
> - Behavior: Charges directly, ignores defense

> **Ancient Red Dragon** (Boss, Blaster)
> - HP: 8
> - Damage: 3 Harm (breath weapon, area), 2 Harm (bite/claw)
> - Traits: Arrogant, Ancient, Greedy
> - Abilities:
>   - **Frightening Presence:** First engagement triggers Defy roll
>   - **Breath Weapon (Area):** Hits all PCs in Close zone
>   - **Legendary Action:** After each PC turn, tail sweep or wing buffet
>   - **Armored Scales:** Requires Opening to deal full damage

---

## Summary: Key Combat Principles

1. **Spotlight flows based on fiction and player choice** (Momentum to seize initiative)
2. **Stress marked frequently** (Conflicts and Failures), Conditions are rare and dramatic
3. **Enemies scale by HP** (1 for mooks → 8+ for bosses) and **Role** (behavior pattern)
4. **Positioning uses zones** (Close/Near/Far) + Battlegrounds (Features/Threats)
5. **Armor as tactical resource** (spend uses to negate Stress)
6. **Max Stress = player choice** (Taken Out or Push Through with Critical Condition)
7. **Helping costs resources** (mark Stress, use action, or spend Momentum)
8. **Epic Foes have special abilities** that create tactical depth without adding core rules
9. **Telegraph danger** using Vigilance (Hint/Reveal/Strike) from gm-guidance.md
10. **Complex scenes** use Challenges structure (see gm-guidance.md)

---

## Next Steps

- [ ] Design 5-10 sample enemies (mooks, standards, elites, epic)
- [ ] Create weapon/armor tags and properties
- [ ] Write 2-3 full combat examples (mook fight, standard fight, boss fight)
- [ ] Define damage scaling for magic/special attacks
- [ ] Playtest with sample characters
- [ ] Integrate with rest/recovery rules
- [ ] Create GM quick reference sheet for combat
