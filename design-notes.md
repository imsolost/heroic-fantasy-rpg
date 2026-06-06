# Design Notes: Stress & Conditions

This document explains the design rationale behind the Stress & Conditions system.

For the core rules, see [stress-conditions.md](stress-conditions.md).

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

## Why Two Condition Types?

### Considered Alternatives

**Option 1: Many specific Conditions** (Wounded, Exhausted, Frightened, Angry, Poisoned, etc.)
- **Pro:** Granular, evocative, "realistic"
- **Con:** Tracking nightmare — players forget which Condition applies when, reference constantly
- **Con:** Design burden — every Challenge Move needs to specify exact Condition type
- **Con:** Edge cases — "Wait, does Frightened apply to this roll?"

**Option 2: One generic Condition** (just "Hurt" or "Impaired")
- **Pro:** Extremely simple
- **Con:** Loses tactical variety — all threats feel samey
- **Con:** Can't model being wounded AND frightened simultaneously
- **Con:** Limits enemy design — dragon's fear aura is just more "Hurt"

**Option 3: Two broad categories** (Staggered/Shaken) ← **We chose this**
- **Pro:** Simple to track — two checkboxes on the sheet
- **Pro:** Broad application — covers 95% of harm types without granularity
- **Pro:** Tactical variety — different enemies threaten different aspects
- **Pro:** Intuitive — players immediately grasp "am I acting physically or mentally?"

---

## Why Three Tiers?

**Minor → Moderate → Severe** creates a gradual escalation that feels earned rather than arbitrary.

**One tier only:** No deterioration modeling — being hit once vs. five times feels identical.

**Two tiers:** Escalation too steep — Minor → Major feels like falling off a cliff.

**Three tiers:** Sweet spot for heroic play.
- **Minor** = "I'm hurt but pushing through" (clears quickly)
- **Moderate** = "I'm significantly impaired" (need a rest)
- **Severe** = "I'm barely standing" (need real recovery time)

**Four+ tiers:** Tracking becomes fiddly, math becomes tedious (4+ Banes per Condition feels brutal).

---

## Why Cumulative Banes?

Each checked tier adds +1 Bane (maximum 3 per Condition type).

**Alternative: Fixed penalty per tier**
- Minor = 1 Bane, Moderate = 1 Bane, Severe = 1 Bane (never stacking)
- **Problem:** Getting hit repeatedly feels mechanically identical
- **Problem:** No deterioration modeling — first hit = fifth hit

**Alternative: Escalating penalty per tier**
- Minor = 1 Bane, Moderate = 2 Banes, Severe = 4 Banes
- **Problem:** Math gets steep fast — 4 Banes is nearly auto-fail
- **Problem:** Players at Severe feel useless, stop engaging

**Cumulative (+1 per tier)** models deterioration naturally:
- 1 Bane = hurt but functional
- 2 Banes = significantly impaired, need to adapt tactics
- 3 Banes = barely hanging on, need help or creative solutions

**Maximum 3 Banes** keeps it heroic — bad but not impossible. A 3d6 pool with 3 Banes still has a ~16% Success chance. You CAN clutch it out, just risky.

---

## Why Independent Tier Clearing?

Each tier clears according to its own recovery condition:
- Minor → after next relevant action
- Moderate → after short rest
- Severe → after long rest

**Alternative: Clear all tiers together**
- **Problem:** Severe Conditions feel unrecoverable — stuck at 3 Banes forever
- **Problem:** No sense of gradual healing

**Independent clearing** creates satisfying recovery arcs:
1. "I just acted — Minor clears, now I'm down to 2 Banes"
2. "We took a short rest — Moderate clears, now I'm down to 1 Bane"
3. "Long rest — Severe clears, fully recovered"

This models "getting better over time" rather than binary hurt/healed states.

---

## Why Clear Minor After One Roll?

Inspired by **Grimwild's Marks** system — temporary harm that clears through action rather than time.

**Playtesting insight:** Minor Conditions that linger for multiple rolls bog down play. Players become overly cautious, waiting to act until they clear it. But if it clears after one action, they act THROUGH it, creating heroic moments.

**Example:**
> "I charge the orc despite my wounded leg (Staggered Minor, 1 Bane) — rolling Clash with penalty... Success! I cleave through it. And now the wound clears — adrenaline carries me forward."

This encourages **action as recovery** rather than passivity. Very different feel from "wait 3 rounds for it to wear off."

---

## Why Allow Both Staggered and Shaken Simultaneously?

### Narrative Realism

Real dangerous situations can hurt you in multiple ways at once:
- Dragon claws you (Staggered) AND roars to terrify you (Shaken)
- Poisoned dart (Staggered) while witnessing your friend fall (Shaken)
- Exhausted from climbing (Staggered) and afraid of heights (Shaken)

Restricting to one type would force weird choices: "You can be wounded OR frightened, not both."

### Tactical Variety

Different enemies threaten different aspects:
- **Undead wights:** Physical necrotic touch + mental dread aura
- **Fire elementals:** Physical burns, no mental effects
- **Mind flayers:** Mental domination, minimal physical harm
- **Dragons:** BOTH (claws + fear aura)

This creates varied threat profiles and interesting encounter design.

### Player Choice

When you have limited Momentum to Resist, which Condition matters more right now?
- "I'll Resist the Shaken because I need to use Talk next turn"
- "I'll Resist the Staggered because there's a big physical challenge coming"

This choice only exists if both types can coexist.

---

## Why Short Rests Clear Moderate?

**10-15 minutes of safety** — This is the "catch your breath after a fight" beat.

In playtesting, we found:
- **Clearing only Stress:** Players still had 2-3 Banes from accumulated Moderate Conditions, felt punished for multiple encounters
- **Clearing all Conditions:** No consequence from taking Moderate Conditions, too forgiving
- **Clearing Stress + Moderate:** Perfect pacing — one tough fight puts you at Moderate Conditions, short rest resets for next fight

**Severe stays** — This is the "you need real rest, not just a breather" tier. Keeps Severe feeling meaningful.

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

## Why Escalate Duplicate Tiers?

**Rule:** When you gain a Condition tier you already have checked, it escalates to the next tier.

**Alternative: Ignore duplicates**
- **Problem:** Taking Staggered (Minor) five times has same effect as taking it once — repeated hits meaningless
- **Problem:** Encourages degenerate tactics — "Just spam Minor Conditions, they don't stack"

**Alternative: Add another instance of same tier**
- **Problem:** Tracking nightmare — "I have Staggered (Minor) three times, when do they each clear?"
- **Problem:** Too punishing — three instances of Minor = 3 Banes without ever escalating

**Escalation** models accumulation naturally:
1. First hit → Minor (1 Bane)
2. Second hit → Moderate added (2 Banes)
3. Third hit → Severe added (3 Banes)
4. Fourth hit → Taken Out

Deterioration feels earned and mechanically visible.

---

## Why Allow Gaps in Tiers?

**Rule:** Taking a higher tier directly checks that tier without affecting lower tiers.

**Example:** You have Staggered (Minor) checked. You take Staggered (Severe) directly. Now you have Minor + Severe (not Minor + Moderate + Severe).

**Why allow this?** It creates interesting "spiked damage" scenarios:
- Minor wound from earlier fight (Minor checked)
- Massive dragon breath attack (Severe checked)
- Result: Minor + Severe = 2 Banes, but Moderate not checked

**Recovery arc:**
- Make one physical action → Minor clears (down to 1 Bane from Severe)
- Take short rest → nothing happens (no Moderate to clear)
- Take long rest → Severe clears (fully recovered)

This models "lots of little cuts PLUS one big wound" differently from "gradual escalation through medium hits."

**Considered auto-filling:** Direct Severe could automatically check Minor + Moderate too.
- **Problem:** Removes the distinction above
- **Problem:** Makes Severe + Severe escalation (to Taken Out) happen unintentionally when taking direct Severe hit while already having Minor/Moderate

Gaps are edge cases (uncommon in play) but create interesting tactical space when they occur.

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

## Why Maximum 3 Banes?

With three tiers per Condition type, maximum Banes per type = 3.

**Why stop at 3?** 
- **Math stays manageable** — 3 Banes on 3d6 = 0% Success, ~16% on 4d6 (low but not impossible)
- **Heroic feel** — You CAN still succeed when badly hurt, just risky
- **Taken Out triggers** — Further escalation beyond 3 Banes = Taken Out

**Considered higher caps:**
- **4+ Banes:** Auto-fail territory, feels like "you're already out, why are you still acting?"
- **Unlimited Banes:** Tracking nightmare, math becomes hostile

**3 Banes** is the "barely hanging on" threshold — bad enough to feel desperate, not so bad that acting is pointless.

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

**Early version:** Four Condition tiers (Trivial, Minor, Moderate, Severe)
- **Problem:** Trivial was forgettable, players ignored it
- **Fix:** Collapsed to three tiers, made Minor clear after one action

**Early version:** Five Condition types (Wounded, Exhausted, Frightened, Angry, Confused)
- **Problem:** Players constantly asked "which one applies to this roll?"
- **Fix:** Collapsed to two broad categories (Staggered/Shaken)

**Early version:** Resist on Success cleared consequence entirely
- **Problem:** Momentum became "immunity button," no risk
- **Fix:** Changed to reduction steps (2 on Success, 1 on Conflict)

**Early version:** All Conditions cleared on short rest
- **Problem:** No consequence to taking Severe Conditions
- **Fix:** Short rest only clears Minor/Moderate, Severe needs long rest

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
- No need to track Staggered vs Shaken separately

**Cons:**
- Loses tactical variety (all harm feels same)
- Can't model being wounded AND frightened
- Limits enemy design

**Verdict:** Too reductive. Two-type system hits sweet spot of simplicity + variety.

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
- Use more Soft Impact Moves (1 Stress) than Hard (2 Stress)
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
