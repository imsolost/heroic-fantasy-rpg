# Stress & Conditions

This document defines how Stress and Conditions work — the primary resilience system for handling harm, consequences, and adversity.

For core mechanics (Actions, Approaches, Momentum), see [core-foundations.md](core-foundations.md).  
For extended examples, see [examples-stress-conditions.md](examples-stress-conditions.md).  
For design rationale, see [design-notes.md](design-notes.md).

---

## Stress

**Stress is the primary resilience track** — a unified buffer absorbing all incoming costs: physical blows, emotional strain, exertion, fear, and any other consequence the fiction demands.

Stress represents getting tired or rattled, taking a superficial wound, narrowly avoiding injury, or pushing yourself beyond normal limits. It recovers quickly and is not meant to represent lasting harm.

**Example:** "The knight's sword glances off your armor — mark 1 Stress as you feel the impact jar your shoulder."

### Stress Track

- **5 boxes** (all characters start with 5)
- Mark boxes left to right
- When your track is full and you would mark more Stress, you must take a Condition instead or be Taken Out

### Marking Stress

**From Impact Moves (most common):**
- **Soft Impact Move** → Mark 1 Stress
- **Hard Impact Move** → Mark 2 Stress

**Voluntarily (as a resource):**
- **Quick Assist** → Mark 1 Stress to grant an ally 1 Edge on their next roll
- **Push Yourself** → Mark 1 Stress to gain 1 Edge on your roll (GM discretion)

### Recovery

**Short rest (10–15 minutes of safety):**
- Clear all Stress
- Clear all Minor and Moderate Conditions

**Long rest (overnight, safe location):**
- Clear all Stress
- Clear all Conditions

---

## Conditions

**Conditions represent lasting physical or mental impairment** beyond the quick recovery of Stress. They impose Banes on relevant rolls and persist until recovered.

### Two Types

**Staggered** — Physical impairment (injury, exhaustion, poison)
- Applies Bane to physical action rolls

**Shaken** — Mental or emotional impairment (fear, anger, confusion, despair)
- Applies Bane to mental and social action rolls

**You can have both Staggered and Shaken simultaneously.** Each tracks independently.

### Condition Tiers

Each Condition type has three tiers. **Track each tier with a checkbox on your character sheet.** Each checked tier adds 1 Bane to relevant rolls.

| Tier | Bane | Clears |
|------|------|--------|
| **Minor** | +1 | After next relevant action roll |
| **Moderate** | +1 | After short rest |
| **Severe** | +1 | After long rest |

**Your total Bane equals however many tiers are currently checked.**

| Checked Tiers | Total Bane |
|---------------|------------|
| Minor only | 1 Bane |
| Moderate only | 1 Bane |
| Minor + Moderate | 2 Banes |
| Minor + Moderate + Severe | 3 Banes |

### Gaining Conditions

**From Challenge Moves:**
Some enemy or environmental moves impose Conditions directly regardless of your Stress track. These cannot be absorbed as Stress.

**Example:** A dragon's Fearsome Roar imposes Shaken (Moderate) on all characters in the scene.

**From Stress Overflow:**
When your Stress track is full and you would mark more Stress, take a Condition instead. Choose Staggered or Shaken based on the source of harm — the GM determines if it's unclear.

- 1 Stress → **Minor** Condition
- 2 Stress → **Moderate** Condition
- 3 Stress → **Severe** Condition

### Escalation

When you would gain a Condition tier you already have checked, it escalates to the next unchecked tier instead.

- Gain **Minor** while Minor is checked → Check **Moderate**
- Gain **Moderate** while Moderate is checked → Check **Severe**
- Gain **Severe** while Severe is checked → **Taken Out**

Taking a higher tier Condition directly checks that tier without affecting lower tiers.

**Example — escalation from repeated hits:**
1. You take Staggered (Minor). Minor checked. **1 Bane.**
2. You take Staggered (Minor) again. Minor already checked — escalates to Moderate. Now Minor + Moderate checked. **2 Banes.**
3. You take Staggered (Moderate) again. Moderate already checked — escalates to Severe. Now Minor + Moderate + Severe checked. **3 Banes.**

**Example — direct higher tier:**
1. You have Staggered (Minor) checked. **1 Bane.**
2. You take a devastating blow — Staggered (Severe) directly. Severe checked. Now Minor + Severe checked. **2 Banes.**

### Recovery

Each tier clears independently according to its recovery condition.

- **Minor** clears after your next relevant action roll
- **Moderate** clears after a short rest
- **Severe** clears after a long rest

**Example:**
1. You have Staggered (Minor + Moderate + Severe). **3 Banes** on physical rolls.
2. You make a physical action roll — Minor clears. Now Staggered (Moderate + Severe). **2 Banes.**
3. The party takes a short rest — Moderate clears. Now Staggered (Severe). **1 Bane.**
4. The party takes a long rest — Severe clears. No Conditions remaining.

### Relevant Rolls

**Staggered** applies to:
- Clash
- Defy (physical — dodging, athletic feats, endurance)
- Any action involving strength, speed, or physical exertion

**Shaken** applies to:
- Talk
- Know
- Sense
- Defy (mental — resisting fear, compulsion, emotional pressure)

When it's ambiguous, the GM determines based on how the player describes their action. A player who describes charging boldly is acting physically; one who carefully analyzes a situation is acting mentally.

---

## Resist Consequence

**Cost:** 1 Momentum

When you would mark Stress or gain a Condition, spend 1 Momentum and roll Defy to reduce or avoid the consequence.

| Outcome | Effect |
|---------|--------|
| **Success** | Reduce by 2 steps — 2 Stress → 0, Moderate → clear, Severe → Minor |
| **Conflict** | Reduce by 1 step — 2 Stress → 1, Moderate → Minor, Severe → Moderate |
| **Setback** | Take the full consequence — Momentum is spent, nothing reduced |

## Taken Out

You are **Taken Out** when:
- You would mark Stress while your track is full and cannot or choose not to take a Condition, or
- You would escalate a Severe Condition that is already checked

**The GM narrates what happens** based on context — unconscious, fleeing, captured, broken. Taken Out is not automatically death.

---

## GM Reference

### Determining Condition Type

**Staggered (physical impairment):**
- Direct physical harm: cuts, blunt force, burns
- Exhaustion from physical exertion
- Poison, disease, environmental exposure
- Any harm to the body itself

**Shaken (mental/emotional impairment):**
- Fear, terror, intimidation
- Anger, rage, loss of composure
- Confusion, disorientation, mental strain
- Despair, hopelessness, emotional trauma

**When ambiguous:**
- Ask how the player describes their action
- "I charge boldly through the flames!" → Physical (body withstanding heat) → Staggered
- "I steel my nerves against the horror!" → Mental (composure vs fear) → Shaken
- Default to the source: physical attack → Staggered, mental attack → Shaken

### When to Use Direct Conditions vs Stress

**Use Stress for:**
- Normal combat exchanges (sword hits, dodging traps)
- Minor setbacks that can be shrugged off
- Anything the players can mitigate by having buffer capacity

**Use direct Conditions for:**
- Overwhelming attacks (dragon breath, siege weapon)
- Environmental hazards (blizzard exposure, toxic fumes)
- Special enemy abilities (fear auras, mind control attempts)
- Narrative moments (fall from great height, witness traumatic event)

Direct Conditions bypass the Stress buffer — they represent harm too significant or pervasive to simply "take on the chin."

### Pacing Recovery

**Short rests** (10-15 minutes) should happen:
- After each significant combat
- During travel when the party takes a breather
- When players explicitly seek safety to catch their breath

This keeps Minor and Moderate Conditions from accumulating across multiple encounters while still making them relevant within a scene.

**Long rests** (overnight) should happen:
- After returning to town or safe haven
- During extended downtime between adventures
- When the party explicitly makes camp in a secure location

Severe Conditions should feel meaningful — they represent serious harm that takes real time to recover from.

### Condition Fiction Examples

**Staggered (Minor):**
- "Your shoulder aches where the club struck it"
- "You're breathing hard, sweat stinging your eyes"
- "A shallow cut on your arm bleeds steadily"

**Staggered (Moderate):**
- "Your ribs are cracked — each breath is agony"
- "Your leg buckles when you put weight on it"
- "The poison courses through you, making you dizzy"

**Staggered (Severe):**
- "The sword has run you through — you're losing blood fast"
- "Your arm hangs useless, bone clearly broken"
- "Fever racks your body, barely conscious"

**Shaken (Minor):**
- "Your hands tremble slightly"
- "You can't quite catch your breath, heart racing"
- "Anger clouds your judgment momentarily"

**Shaken (Moderate):**
- "The dragon's roar echoes in your mind — you want to flee"
- "Rage overwhelms you — all you see is red"
- "Your friend's death replays in your mind on loop"

**Shaken (Severe):**
- "You're paralyzed with terror, unable to think clearly"
- "Despair crushes you — what's the point of fighting?"
- "Reality feels distant, fragmented — you can't tell what's real"

---

## Quick Reference

| Situation | Result |
|-----------|--------|
| Soft Impact Move | Mark 1 Stress |
| Hard Impact Move | Mark 2 Stress |
| Quick Assist | Mark 1 Stress, grant ally 1 Edge |
| Push Yourself | Mark 1 Stress, gain 1 Edge |
| Stress track full + hit | Take Condition or Taken Out |
| Challenge Move | Take named Condition directly |
| Gain Condition tier already checked | Escalate to next tier |
| Severe already checked + escalate | Taken Out |
| Short rest | Clear all Stress, Minor, and Moderate Conditions |
| Long rest | Clear all Stress and all Conditions |

**Condition Banes:**
- Each checked tier = 1 Bane on relevant rolls
- Maximum 3 Banes per Condition type (all three tiers checked)

**Relevant rolls:**
- **Staggered** → physical actions
- **Shaken** → mental and social actions
