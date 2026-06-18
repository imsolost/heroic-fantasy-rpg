# Design Notes: Stress & Conditions

This document explains the design rationale behind the Stress & Conditions system.

For the core rules, see [05-resilience.md](05-resilience.md).

---

## Core Philosophy

The Stress & Conditions system is designed to model **heroic resilience with meaningful deterioration**. Characters can withstand significant punishment (they're heroes, after all), but harm accumulates and becomes harder to ignore.

**Key goals:**
1. **Unified resilience track** — One system handles all harm types (physical, mental, environmental)
2. **Quick recovery for minor harm** — Heroes bounce back from scratches and close calls
3. **Deterioration matters** — Accumulated harm mechanically impacts effectiveness
4. **Pacing tool** — Short and long rests create natural narrative beats

---

## Why 5 Stress Boxes?

**3-4 hits before overflow** — This is the sweet spot for typical combat encounters.

In playtesting, most combats produce:
- 1-2 Conflict outcomes (1 Stress each) = 1-2 Stress
- 0-1 Setback outcomes (2 Stress each) = 0-2 Stress
- **Total:** 1-4 Stress per fight

With 5 boxes, players typically finish a fight with 2-4 Stress marked — hurt but not broken. They *could* push into another fight, but it's risky. This encourages the "take a breather after a tough fight" behavior we want.

**Too few boxes (3):** Players hit Conditions too quickly, every fight feels desperate.

**Too many boxes (7+):** Stress becomes meaningless padding, players never take Conditions in normal play.

---

## Stress as Resource

**Quick Assist** and **Push Yourself** both cost 1 Stress. This creates tactical tension: do you spend your buffer to gain an edge, or preserve it to absorb incoming harm?

In playtesting, this led to interesting choices:
- The rogue marks 1 Stress to give the fighter Edge on a critical save
- The wizard Pushes herself (1 Stress) to gain Edge on a desperate spell
- The fighter refuses to Quick Assist because he's already at 4/5 Stress and doesn't want to take a Condition

These choices make Stress feel valuable beyond just a hit point buffer.

**Why 1 Stress per effect?** It's the smallest meaningful cost. More expensive (2 Stress) made players hoard it; free would remove the tension.

---

## Why Stress Overflow = Take Burden or Be Taken Out?

When your Stress track is full and you would mark more, you choose: **take a Burden (persistent Condition) or be Taken Out**.

### Considered Alternatives

**Option A: Overflow creates regular Condition**
- 1 Stress → tier 1, 2 Stress → tier 2, etc.
- **Problem:** Regular Conditions clear on short rest, so being at max Stress isn't meaningfully dangerous
- **Problem:** No consequence for pushing past your limit — just another Condition that clears in 10 minutes

**Option B: Overflow = immediate Taken Out**
- Simpler: full Stress + more damage = done
- **Problem:** Removes player agency — one more hit and you're automatically out
- **Problem:** Feels arbitrary — "I was fine at 4/5 Stress, now I'm unconscious?"

**Option C: Choose Burden or Taken Out** ← **We chose this**
- **Pro:** Player agency — choose to push through at a cost or accept defeat
- **Pro:** Dramatic moments — "I stay in the fight but this wound won't heal easily"
- **Pro:** Makes max Stress truly dangerous — Burdens persist beyond short rest
- **Pro:** Creates escalation — accumulating Burdens across multiple fights

### How It Works in Play

**Early in adventure:**
- Stress full → take Wounded 1 (Burden) → keep fighting
- Short rest clears Stress, but Wounded 1 (Burden) persists
- Next fight starts with 1 Bane carrying over

**Mid-adventure:**
- Stress full again → take another Burden or be Taken Out?
- Now carrying multiple Burdens (capped at 2 Banes total)
- Need to tick them down through action or seek narrative resolution

**Decision points:**
- "Take this Burden and stay in the fight, or accept being Taken Out?"
- "I already have two Burdens — taking a third won't increase my Banes (capped at 2), but do I want to track three separate Conditions ticking down?"

This creates **escalating risk** across multiple encounters while maintaining **player choice** at critical moments.

---

## Why Named Conditions?

### Considered Alternatives

**Option 1: Two broad categories** (Staggered/Shaken with checkbox tiers)
- **Pro:** Simple to track — two sets of checkboxes
- **Pro:** Broad application — covers most harm types
- **Con:** Feels abstract — "Staggered" doesn't evoke the fiction as well as "Poisoned" or "Burned"
- **Con:** Checkbox escalation complex — players confused about when to check which tier
- **Con:** "Staggered vs Shaken" distinction led to constant "which type is this?" questions

**Option 2: One generic Condition** (just "Hurt" or "Impaired")
- **Pro:** Extremely simple
- **Con:** Loses tactical variety — all threats feel samey
- **Con:** Can't model being wounded AND frightened simultaneously
- **Con:** Limits enemy design — dragon's fear aura is just more "Hurt"

**Option 3: Named Conditions with tiers** ← **We chose this**
- **Pro:** Evocative — "Poisoned 2" or "Frightened 3" immediately communicates fiction
- **Pro:** Flexible — GM names Conditions to fit the situation (Burned, Stunned, Blinded, etc.)
- **Pro:** Simple tracking — just write "Poisoned 2" on sheet, tick down the number
- **Pro:** Clear application — default to "affects all rolls" eliminates constant edge-case questions
- **Con:** Slightly more tracking than one generic Condition (but much simpler than old checkbox system)

---

## Why Three Tiers?

**Tier 1 → Tier 2 → Tier 3** creates a gradual escalation that feels earned rather than arbitrary.

**One tier only:** No duration modeling — fleeting dizziness vs deep poison feels identical.

**Two tiers:** Not enough granularity — tier 1 feels trivial, tier 2 feels too severe.

**Three tiers:** Sweet spot for heroic play.
- **Tier 1** = "I'm impaired but pushing through" (clears after 1 action)
- **Tier 2** = "I'm significantly impaired" (clears after 2 actions)
- **Tier 3** = "I'm barely standing" (clears after 3 actions)

**Four+ tiers:** Tracking becomes fiddly, duration too long (4+ actions to clear feels eternal in combat).

**All tiers apply same penalty (1 Bane)** — tier represents duration, not severity. This keeps math simple while modeling persistence.

---

## Why Each Condition = 1 Bane (Max 2 From Conditions)?

**Each Condition applies 1 Bane, regardless of tier. Multiple Conditions stack, maximum 2 Banes from Conditions total.**

**Alternative: Tier determines penalty**
- Tier 1 = 1 Bane, Tier 2 = 2 Banes, Tier 3 = 3 Banes
- **Problem:** Math escalates too fast — Tier 3 alone = 3 Banes feels crushing
- **Problem:** Players at Tier 3 feel useless, disengage

**Alternative: All Conditions = 1 Bane, unlimited stacking**
- **Problem:** Three Conditions = 3 Banes feels too punishing
- **Problem:** Overlaps with Edge/Bane cap (±2d from all sources), creates confusion

**Flat 1 Bane per Condition, capped at 2 total** models impairment simply:
- 1 Condition = 1 Bane = hurt but functional
- 2+ Conditions = 2 Banes = significantly impaired, need to adapt tactics
- Tier represents duration (how long it lasts), not severity (how bad the penalty is)

**Maximum 2 Banes from Conditions** keeps it heroic while stacking with the Edge/Bane cap (±2d from all sources). You can have 2 Banes from Conditions + 2 Banes from difficulty = 4 total Banes, but Conditions alone cap at 2.

**Why 2 not 3?** Playtesting showed 3 Banes from Conditions alone felt too punishing, especially combined with difficult circumstances. 2 Banes = ~6% Setback rate on 3d6, still challenging but not crushing.

---

## Why Tiers Tick Down Through Action?

Each time you make an action roll where the Condition applies, reduce tier by 1. When tier reaches 0, it clears.

**Alternative: Time-based clearing**
- Tier 1 → clears after 1 round
- Tier 2 → clears after 2 rounds
- Tier 3 → clears after 3 rounds
- **Problem:** Passive waiting feels un-heroic — "I hide and wait for it to wear off"
- **Problem:** Tracking rounds adds overhead

**Alternative: Flat duration regardless of tier**
- All Conditions clear after 3 actions
- **Problem:** Tier becomes meaningless — Tier 1 = Tier 3 in practice

**Ticking down through action** creates satisfying recovery arcs:
1. "I act despite the poison (Tier 3 → Tier 2)"
2. "I push through again (Tier 2 → Tier 1)"
3. "One more action and I'm clear (Tier 1 → clears)"

This models **action as recovery** — heroes fight through adversity rather than passively waiting for it to pass. Very different feel from "wait 3 rounds for it to wear off."

Inspired by **Grimwild's Marks** system.

---

## Why Refresh Instead of Escalate?

**Rule:** If you would gain a Condition you already have, it refreshes to its original tier instead of escalating higher.

**Example:** You have Poisoned 2. You're poisoned again. It refreshes to Poisoned 2, not Poisoned 3 or Poisoned 4.

**Alternative: Escalate tiers**
- Poisoned 2 + Poisoned again = Poisoned 3
- **Problem:** Unlimited escalation leads to death spiral — repeated hits ratchet tier infinitely
- **Problem:** Tracking confusion — "I have Poisoned 2 and Poisoned 3, are those separate?"

**Alternative: Add separate instances**
- Track "Poisoned 2" and "Poisoned 2 (second dose)" separately
- **Problem:** Tracking nightmare — which one ticks down when?
- **Problem:** Each instance = 1 Bane → could exceed 2 Bane cap from Conditions

**Refresh (reset to max tier)** models persistence without escalation:
- First hit: Poisoned 2 (2 actions to clear)
- Act once: Poisoned 1 (1 action to clear)
- Get hit again: Refreshes to Poisoned 2 (back to 2 actions to clear)

This creates **persistence** (hard to shake off when repeatedly applied) without **death spiral** (never gets worse than original tier). The poison keeps you impaired but doesn't compound infinitely.

---

## Why Allow Multiple Different Conditions Simultaneously?

### Narrative Realism

Real dangerous situations can impair you in multiple ways at once:
- Dragon claws you (Wounded) AND roars to terrify you (Frightened)
- Poisoned dart (Poisoned) while witnessing your friend fall (Demoralized)
- Exhausted from climbing (Exhausted) and afraid of heights (Frightened)

Restricting to one Condition would force weird choices: "You can be wounded OR frightened, not both."

### Tactical Variety

Different enemies threaten different aspects:
- **Undead wights:** Necrotic touch (Weakened) + dread aura (Frightened)
- **Fire elementals:** Burns (Burned), no mental effects
- **Mind flayers:** Mental domination (Confused), minimal physical harm
- **Dragons:** BOTH (Wounded + Frightened from claws + fear aura)

This creates varied threat profiles and interesting encounter design.

### Capped at 2 Banes Total

Multiple Conditions stack (each = 1 Bane) but cap at 2 Banes from Conditions total. This prevents:
- **Death spiral:** Three+ Conditions don't compound to 3+ Banes
- **Overwhelming penalties:** Even with many Conditions, max 2 Banes keeps you functional
- **Clear cap:** Players know the worst case (2 Banes from Conditions)

**Example:** You have Poisoned 2, Frightened 1, and Prone 1. That's three Conditions but only 2 Banes total (capped).

---

## Why Short Rests Clear All Conditions?

**10-15 minutes of safety** — This is the "catch your breath after a fight" beat.

**All Conditions clear on short rest** regardless of tier. This creates clean scene boundaries.

In playtesting, we found:
- **Clearing only Stress:** Players still had Conditions from prior fights, felt punished across multiple encounters
- **Tier-based clearing (Tier 1-2 clear, Tier 3 stays):** Tracking burden — "which tier was this again?" — and Tier 3 Conditions dragged across scenes
- **All Conditions clear:** Perfect pacing — one tough fight leaves you with Conditions, short rest resets for next fight

**Design intent:** Conditions are scene-level impairment, not adventure-level. They create tension within a fight or sequence, then clear for the next scene.

**Burdens (rare):** For persistent Conditions that DO carry across scenes, use Burdens — explicitly marked as requiring narrative resolution instead of normal rest.

---

## Why Long Rests Clear Everything?

**Overnight, safe location** — This is the "return to town" or "make camp in secure area" beat.

Long rests represent:
- 8+ hours of sleep
- Medical attention / healing magic
- Safety to truly recover

In heroic fantasy, heroes heal quickly given time and safety. Long rests provide natural narrative breaks:
- Return to town between adventures
- Camp overnight during travel
- Hole up in a safe room in the dungeon

**Why not permanent injuries?** The base system avoids them for accessibility. GMs can add "lingering wounds" for grittier campaigns, but default heroic play assumes full recovery.

---

## Why Two Steps on Resist Success?

**Resist Consequence** costs 1 Momentum, outcomes reduce severity:
- Success → reduce by 2 steps
- Conflict → reduce by 1 step
- Setback → no reduction (wasted Momentum)

**Why 2 steps on Success?** It needs to feel worth the Momentum cost.

In playtesting:
- **1 step on Success:** Felt underwhelming — "I spent Momentum and got... slightly less hurt?"
- **3 steps / full avoidance:** Too strong — Momentum became "ignore all harm" button
- **2 steps on Success:** Felt heroic and worth it — "I twisted aside and avoided the brunt of it!"

**Conflict as middle ground** (1 step) ensures Momentum isn't wasted on bad rolls while keeping Success feel impactful.

---

## Why Named Conditions Instead of Generic Tiers?

**Rule:** GMs name Conditions to fit the fiction (Poisoned, Frightened, Blinded, etc.) rather than using abstract generic tiers.

**Alternative: Generic "Impaired 1/2/3"**
- **Problem:** Loses fiction — "Impaired 2" doesn't evoke anything specific
- **Problem:** Can't model being poisoned AND frightened — both are just "Impaired"

**Alternative: Fixed list of specific Conditions with unique mechanical effects**
- **Problem:** Tracking nightmare — players need to reference what each Condition does
- **Problem:** Design burden — requires extensive list with edge-case rulings

**Named Conditions with simple unified effect (1 Bane)** combines best of both:
- **Evocative:** "Poisoned 2" immediately communicates the fiction
- **Flexible:** GM picks the name that fits the situation
- **Simple:** All Conditions work the same mechanically (1 Bane, tick down through action)
- **Stackable:** Multiple different Conditions can coexist (Poisoned 2 + Frightened 1)

The name serves the fiction, the tier serves the mechanics. Clean separation of concerns.

---

## Why Default to "All Rolls" Instead of Specific Actions?

**Rule:** By default, a Condition affects all action rolls unless clearly inapplicable.

**Example:** Poisoned 2 affects Clash, Defy, Talk, Sense — basically everything. Only clearly inapplicable cases (e.g., recalling lore while poisoned) don't apply.

**Alternative: Specific action restrictions**
- Poisoned affects physical actions only
- Frightened affects mental actions only
- **Problem:** Constant edge-case questions — "Is Defy physical or mental?" "Does poison affect Talk?"
- **Problem:** Tracking burden — "Which Conditions apply to this roll?"

**Alternative: Condition type determines application** (like old Staggered/Shaken)
- Physical Conditions affect physical actions
- Mental Conditions affect mental actions
- **Problem:** Same edge-case questions, plus categorization burden — "Is this Condition physical or mental?"

**Default to "all rolls"** eliminates questions:
- You're Poisoned 2? 1 Bane on all your rolls
- You're Frightened 1? 1 Bane on all your rolls
- Clear exception: Blinded doesn't affect recalling lore, Deafened doesn't affect scanning visually

**GM has final say on exceptions,** but default is simple: Conditions impair you broadly, tick down through any relevant action, clear on short rest.

This trades away some granularity for massive reduction in edge-case rulings.

---

## Why "Taken Out" Instead of "Dead"?

**Taken Out** is deliberately vague — the GM narrates what happens based on context.

**Possible outcomes:**
- Unconscious (can be revived by allies)
- Fleeing in terror (can regroup later)
- Captured (rescue mission!)
- Pinned down (suppressed, can't act)
- Broken (surrender, give up)

**Why not automatic death?** Heroic fantasy default is "heroes don't die from combat mishaps, they die from dramatic choices."

**When does death happen?** 
- Narrative context demands it (fall into lava, beheaded in execution)
- Player chooses heroic sacrifice
- GM explicitly warns "this will kill you" and player proceeds

**Taken Out** keeps stakes high (you're out of the fight, consequences happen without you) without making death a random dice outcome.

---

## Why Maximum 2 Banes from Conditions?

Multiple Conditions stack, but maximum 2 Banes from Conditions total.

**Why stop at 2?** 
- **Math stays manageable** — 2 Banes on 3d6 = ~6% Setback (challenging but not crushing)
- **Heroic feel** — You CAN still succeed when impaired, just harder
- **Stacks with situational Banes** — 2 Banes from Conditions + 2 Banes from Very Hard task = 4 total, keeping Edge/Bane system consistent (max ±2d from any single source)

**Considered higher caps:**
- **3+ Banes from Conditions alone:** Too punishing, especially when combined with situational Banes (Hard task, poor positioning, etc.)
- **Unlimited Banes:** Tracking nightmare, death spiral, math becomes hostile

**Considered lower caps:**
- **1 Bane max:** No deterioration modeling — being hit repeatedly feels mechanically identical

**2 Banes from Conditions** is the "significantly impaired" threshold — bad enough to feel consequences, not so bad that you feel useless. You adapt tactics, seek help, or push through with Momentum.

---

## System Interactions

### Momentum Economy

**Momentum sources:**
- Success on action rolls (gain 1)
- Special moves / playbook abilities

**Momentum sinks:**
- Resist Consequence (1 Momentum)
- Special moves / playbook abilities

Resist competes with other Momentum uses, creating interesting choices:
- "Do I Resist this Condition, or save Momentum for my signature move?"
- "I'm at 2 Momentum, do I Resist now or wait to see if the next hit is worse?"

### Edge/Bane Interaction

Edge and Bane cancel 1:1 before rolling. This creates Condition mitigation through Edge generation:
- "I'm at 2 Banes from Conditions, but I have 2 Edge from setup, so I roll normally"
- "I Quick Assist my wounded ally to cancel some of their Bane penalties"

Edge-generating builds become more valuable when the party is hurt — support characters shine.

### Short Rest Pacing

**When do parties short rest?**
- After each combat (if they have time)
- Between floors in a dungeon
- After a tense negotiation
- While searching a room thoroughly

**When can't they?**
- Chase scenes
- Time pressure ("the ritual completes in 10 minutes!")
- No safe space (surrounded by enemies)
- Resource scarcity (no time to rest, keep moving)

GMs control pacing by controlling short rest opportunities. Want attrition to matter? Deny short rests. Want reset between fights? Provide them.

---

## Influences & Inspirations

**Forged in the Dark (Stress system):**
- Unified resilience track for all harm types
- Stress as voluntary resource (Push Yourself, Assist)
- Overflow triggers harsher consequences

**Blades in the Dark (Harm levels):**
- Tiered harm (Lesser, Moderate, Severe)
- Each tier has different recovery condition
- Multiple tiers stack effect

**Grimwild (Marks):**
- Conditions that clear after one action
- Encourages acting through harm rather than waiting
- Minor Conditions inspired directly by this

**Fate Core (Stress + Consequences):**
- Stress absorbs hits, consequences represent lasting harm
- Different consequence severities clear at different rates
- Our system blends both into one unified track

**13th Age (Escalation Die philosophy):**
- Combat should feel dynamic and escalating
- Mechanical deterioration creates rising tension
- Our cumulative Banes achieve similar escalation feel

---

## Playtesting Notes

### What Changed During Development

**Early version:** 7 Stress boxes
- **Problem:** Never ran out in normal play, felt like padding
- **Fix:** Reduced to 5 boxes

**Early version:** Two Condition types with checkbox tiers (Staggered/Shaken)
- **Problem:** Checkbox escalation complex, "which type?" questions constant
- **Fix:** Named Conditions with simple tier numbers (Poisoned 2, Frightened 1)

**Early version:** Staggered/Shaken applied to specific action types (physical vs mental)
- **Problem:** Constant edge-case questions — "Is Defy physical or mental?"
- **Fix:** Default to "all rolls" unless clearly inapplicable, eliminates most questions

**Early version:** Each tier cleared independently (tier 1 after action, tier 2 after short rest, tier 3 after long rest)
- **Problem:** Tracking burden, tier 3 dragged across scenes
- **Fix:** All tiers tick down through action, all Conditions clear on short rest (scene boundaries)

**Early version:** Cumulative Bane penalties (3 tiers = 3 Banes per Condition)
- **Problem:** Too punishing, especially with multiple Conditions
- **Fix:** Flat 1 Bane per Condition, max 2 Banes from Conditions total

**Early version:** Conditions escalate when refreshed (Poisoned 2 + Poisoned = Poisoned 3)
- **Problem:** Death spiral, unlimited escalation
- **Fix:** Conditions refresh to original tier (Poisoned 2 stays Poisoned 2)

**Early version:** Resist on Success cleared consequence entirely
- **Problem:** Momentum became "immunity button," no risk
- **Fix:** Changed to reduction steps (2 on Success, 1 on Conflict) — still in place

### What Worked Immediately

- Unified Stress track (players loved simplicity)
- Minor clearing after action (created heroic moments)
- Edge/Bane cancellation (felt intuitive)
- Taken Out instead of death (kept stakes without lethality)

---

## Design Alternatives We Rejected

### Alternative: Separate Physical and Mental Stress Tracks

**Idea:** Two 5-box tracks, one for physical harm, one for mental.

**Pros:**
- Clearer separation of harm types
- Can't "use mental resilience to soak physical blows"

**Cons:**
- Double the tracking
- Some harm is ambiguous (environmental exposure, exhaustion — physical or mental?)
- Players need to manage two resources instead of one

**Verdict:** Unified track is simpler and handles edge cases better. If harm type matters, it manifests in Condition type, not Stress track.

---

### Alternative: Condition Cards

**Idea:** Physical cards with Condition name, tier, effect, and fictional description.

**Pros:**
- Evocative and tactile
- Easier to remember what each Condition does
- Can hand them out when inflicted

**Cons:**
- Requires physical components
- Harder to track tiers (multiple cards?)
- Slows play (shuffling through cards)

**Verdict:** Works for some games (e.g. Gloomhaven) but too fiddly for fiction-first play. Checkbox system is faster.

---

### Alternative: Condition Track (One Unified Track for All Conditions)

**Idea:** One track with checkboxes: [  ][  ][  ][  ][  ][  ]  
Mark boxes for ANY Condition, no distinction between types.

**Pros:**
- Extremely simple
- No need to track different Condition names

**Cons:**
- Loses tactical variety (all harm feels same)
- Can't model being wounded AND frightened simultaneously
- Limits enemy design (dragon's fear aura = generic boxes)

**Verdict:** Too reductive. Named Conditions provide fiction while keeping mechanics simple (all = 1 Bane, tick down same way).

---

### Alternative: Narrative Conditions (No Mechanical Effect)

**Idea:** Conditions are purely fictional — "Wounded Leg," "Terrified," "Exhausted" — GM adjudicates when they matter.

**Pros:**
- Maximum flexibility
- Encourages fiction-first play
- No math to track

**Cons:**
- Inconsistent rulings (GM discretion = table variation)
- Players can't plan around penalties
- Opens door for arguments ("Does my wounded leg affect this?")

**Verdict:** Works for very experienced groups but lacks clarity for general play. Mechanical framework (Banes) provides consistency.

---

## Future Considerations

### Possible Expansions

**Armor / Damage Reduction:**
- Armor could reduce incoming Stress (e.g., "mark 1 less Stress from physical hits")
- Keeps Stress/Condition system intact, adds gear differentiation

**Condition Synergies:**
- Certain moves could exploit specific Conditions (e.g., "deal +1d6 damage to Staggered enemies")
- Adds tactical depth without complicating base system

**Variant Condition Types (Optional Rule):**
- Exhausted (clears only after long rest, cannot be cleared with short rest)
- Poisoned (ongoing Stress each round until treated)
- Could be advanced rules for specific campaigns

**Stress Thresholds (Optional Rule):**
- At 3+ Stress, describe visible signs of strain
- At 5/5 Stress, impose fictional penalties (moving slowly, breathing hard)
- Adds fictional weight without mechanical changes

### What We're NOT Adding

**Critical Hits** — Random spikes undermine tactical play, better modeled through Challenge Moves

**Death Spiral** — Negative penalties beyond Banes feel un-heroic and unfun

**Healing Potions as Stress Recovery** — Stress clears quickly naturally, no need for consumable market

**Permanent Injuries** — Base system avoids them, GMs can add for gritty campaigns

---

## GM Advice

### Pacing Attrition

**For high-attrition "dungeon crawl" feel:**
- Limit short rest opportunities (enemies patrol, time pressure)
- Use Challenge Moves to inflict direct Conditions
- Multiple encounters before long rest

**For heroic "bounce-back" feel:**
- Allow short rests between fights
- Use Stress overflow primarily, not direct Conditions
- Encourage Momentum spending on Resist

### Balancing Challenge

**Players feeling too fragile?**
- Offer more short rest opportunities
- Use more Minor Consequences (1 Stress) than Major Consequences (2 Stress)
- Telegraphs before big hits (let players Resist)

**Players feeling invincible?**
- Use Challenge Moves to inflict direct Conditions (bypass Stress buffer)
- Time pressure prevents short rests
- Multiple enemies (more Impact Moves per round)

### Fictional Positioning

**Always tie mechanics to fiction:**
- "Mark 1 Stress" → "The blade grazes your cheek, blood trickling down"
- "Take Staggered (Moderate)" → "The club cracks your ribs — breathing is agony"
- "Shaken (Severe) clears" → "The terror fades. You steady yourself, find your courage again"

Mechanics without fiction feel hollow. Fiction without mechanics lacks stakes. Blend both.

---

## Conclusion

The Stress & Conditions system prioritizes:
1. **Simplicity** — Easy to teach, quick to run
2. **Meaningful deterioration** — Harm accumulates and matters mechanically
3. **Heroic resilience** — Characters can take punishment and keep fighting
4. **Pacing tool** — Recovery triggers create narrative beats

It's not trying to simulate realistic injury or medical accuracy. It's trying to capture the feel of heroic fantasy: heroes who take a beating, push through the pain, and recover quickly given a breather.
