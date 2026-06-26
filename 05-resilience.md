# Stress & Conditions

This document defines how Stress and Conditions work — the primary resilience system for handling harm, consequences, and adversity.

For core mechanics (Actions, Approaches, Momentum), see [02-core-mechanics.md](02-core-mechanics.md).  
For extended examples, see [appendix-b-examples.md](appendix-b-examples.md).  
For design rationale, see [appendix-a-design-notes.md](appendix-a-design-notes.md).

---

## Stress

**Stress is the primary resilience track** — a unified buffer absorbing all incoming costs: physical blows, emotional strain, exertion, fear, and any other consequence the fiction demands.

Stress represents getting tired or rattled, taking a superficial wound, narrowly avoiding injury, or pushing yourself beyond normal limits. It recovers quickly and is not meant to represent lasting harm.

**Example:** "The knight's sword glances off your armor — mark 1 Stress as you feel the impact jar your shoulder."

### Stress Track

- **5 boxes** (all characters start with 5)
- Mark boxes left to right
- When your track is full and you would mark more Stress, choose: **take a Burden or be Taken Out**

### Marking Stress

**From Consequences (most common):**
- **Minor Consequence** (Conflict outcome) → Mark 1 Stress
- **Major Consequence** (Setback outcome) → Mark 2 Stress
- **Severe Consequence** (Disaster outcome) → May inflict Stress + Burden, or result in Taken Out

See **Chapter 4: Action Resolution** for complete Consequence framework.

**Voluntarily (as a resource):**
- **Assist** → Mark 1 Stress to grant an ally 1 Boon on their roll (see Chapter 2: Working Together)
- **Push Yourself** → At any time before or during a roll, mark 1 Stress to gain 1 Boon on that roll. This represents digging deep, pushing past your limits, or taking risks to succeed.

### Recovery

**Short rest (1 hour, safe location):**
- Clear all Stress
- Clear all Conditions (Burdens do NOT clear)

**Long rest (overnight, safe location):**
- Clear all Stress
- Clear all Conditions
- Burdens reduce by 1 tier

---

## Conditions

Conditions represent temporary impairment — poison coursing through your veins, fear gripping your mind, a wound slowing your movements. They are short-term states that skilled heroes shake off through action and rest.

### How Conditions Work

A Condition has a **name** and a **tier** — both set at the moment of infliction.

- The name describes the fictional state: Poisoned, Frightened, Blinded, Stunned
- The tier (1–3) represents severity and duration

**Each Condition applies 1 Bane to all action rolls.** Multiple Conditions stack — each applying 1 Bane. You can have 3, 4, or more Conditions simultaneously. (Pool modifier cap: ±2d applies — see Chapter 2.)

**Conditions only apply (and tick down) when fictionally relevant.** If a Condition clearly has no bearing on the action (Blinded doesn't affect recalling lore), it doesn't apply and doesn't tick down. When in doubt, apply the Condition.

### Gaining Conditions

Conditions come from three sources:

**Challenge Moves:** Enemy abilities inflict Conditions directly, at a tier determined by the move.

**Consequences:** The GM may inflict a Condition (tier 1 for Minor, tier 2-3 for Major/Severe) instead of or alongside marking Stress.

**Stress Overflow:** When your Stress track is full and you would mark more Stress, you may choose to take a Burden or be Taken Out (see Stress Track section above for full procedure). The Burden tier is determined by overflow amount:
   - 1 overflow → tier 1
   - 2 overflow → tier 2
   - 3+ overflow → tier 3
   
   *Example: At 4/5 Stress, you take 2 Stress. Mark the 5th box + 1 overflow = Tier 1 Burden if you choose to take it.*

### Condition Tiers

The tier set at infliction is the **maximum severity** of that Condition. It never escalates beyond its initial tier regardless of how many times the same Condition is inflicted — subsequent hits of the same Condition simply refresh it back to its maximum.

| Tier | Bane | Ticks Down After* |
|------|------|-------------------|
| 1 | 1 Bane | 1 relevant action roll |
| 2 | 1 Bane | 2 relevant action rolls |
| 3 | 1 Bane | 3 relevant action rolls |

*Or on Short Rest, whichever comes first.

Each time you make an action roll where the Condition applies, reduce its tier by 1. When it reaches 0, it clears.

**All Conditions clear on Short Rest** (1 hour, safe location), regardless of remaining tier.

**Refresh, Not Stack:** The same Condition cannot stack beyond its initial tier. If you are Poisoned 2 and would become Poisoned again, it refreshes to Poisoned 2 — it does not become Poisoned 3 or Poisoned 4.

> *Example: You are Poisoned 2 and Frightened 1. Both apply → 2 Banes. If you also become Blinded 1, you have 3 Conditions → 3 Banes (capped at -2d to your pool).*

### Recovering from Conditions

**Through action:** Make action rolls where the Condition applies. Each relevant roll reduces the tier by 1.

**Through Trait Special Effects:** When you invoke a Trait and choose Secondary Effect, you may reduce any one Condition by 1 tier — provided the Trait is fictionally relevant to shaking off that Condition.

> *A warrior with the Ironborn Trait shaking off Poisoned through sheer physical resilience. A rogue with Shadow Step reducing Frightened by moving decisively through the darkness.*

### Common Condition Names

Use these as guidance when inflicting Conditions. The list is not exhaustive — name Conditions to fit the fiction.

**Physical:** Poisoned, Burned, Blinded, Deafened, Restrained, Stunned, Bleeding, Weakened, Slowed, Exhausted

**Mental/Emotional:** Frightened, Enraged, Confused, Charmed, Taunted, Demoralized, Distracted

**Positional/Tactical:** Prone, Disarmed, Grappled, Pinned, Exposed, Off-Balance

### Character Sheet Tracking

**Simple format:**
```
CONDITIONS:
Poisoned 2
Frightened 1
```

Reduce the number by 1 each time you act through it. Erase when it reaches 0 or after Short Rest.

### Example in Play

> **GM:** The assassin's poisoned blade nicks you. You feel the poison begin to work. Poisoned 2. What do you do?
>
> **Player:** I Clash — drive them back.
>
> **GM:** The poison affects your movement. 1 Bane. Roll it.
>
> **Player:** Conflict. Poisoned drops to 1.
>
> **GM:** You slam them against the wall. They strike back — Poisoned Blade triggers. You're already Poisoned 1, so it refreshes to Poisoned 2. Mark 1 Stress.
>
> **Player:** I attack again.
>
> **GM:** Still 1 Bane from Poisoned 2. Roll it.
>
> **Player:** Success. Poisoned drops to 1 again.
>
> **GM:** Solid hit. The assassin is badly hurt now.
>
> (After combat, the party takes a Short Rest. Poisoned clears entirely.)

---

## Resist Consequence

**Cost:** 1 Momentum

When you would suffer a consequence (Stress, Condition, or narrative setback), spend 1 Momentum to automatically reduce the Consequence Tier by 1.

**No roll required** — the reduction is immediate and guaranteed.

### What This Reduces

**Stress Consequences:**
- Major Consequence (2 Stress) → Minor Consequence (1 Stress)
- Minor Consequence (1 Stress) → No Stress
- Severe Consequence (3 Stress) → Major Consequence (2 Stress)

**Condition Consequences:**
- Condition tier 3 → Condition tier 2
- Condition tier 2 → Condition tier 1
- Condition tier 1 → No Condition

**Narrative Consequences:**
- GM reduces severity (lose footing → keep position, weapon knocked away → weapon stays, separated from party → stay together)

### When to Use

- **After consequence announced:** The GM announces a consequence, you declare "I Resist" and spend 1 Momentum
- **Before Stress Overflow:** When full Stress and would mark more, Resist reduces the overflow amount (possibly avoiding Burden choice entirely)
- **Your choice:** Decide whether the Momentum is worth avoiding/reducing this specific consequence

### Example in Play

> **GM:** "The knight's mace slams into your shield. Mark 2 Stress."
> **PC:** "I spend Momentum to Resist—I roll with the blow, reducing it to 1 Stress."
> **GM:** "The impact jars your arm but you stay firm."

> **GM:** "The dragon's roar fills you with terror. Frightened 3."
> **PC:** "I Resist—I've faced worse. Reduce it to Frightened 2."
> **GM:** "You grit your teeth and hold your ground, though fear still grips you."

---

## Taken Out

You are **Taken Out** when:
- **Stress Overflow:** You would mark Stress while your track is full and cannot or choose not to take a Burden
- **Burden Escalation:** The GM may rule you're Taken Out from overwhelming sources (Death Moves, Disaster, narrative events that would incapacitate you)

**The GM narrates what happens** based on context — unconscious, fleeing, captured, broken. Taken Out is not automatically death.

**Re-entering the Scene:** A Taken Out character may re-enter the scene when it's dramatically appropriate — rescued by allies, the threat passes, or the GM decides the fiction allows recovery. Their Stress clears when they recover.

---

## GM Reference

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

**Short rests** (1 hour, safe location) should happen after significant combat, during travel breaks, or when players seek safety. This ensures Conditions don't carry over from scene to scene while remaining relevant within a scene.

**Long rests** (overnight) should happen after returning to safety, during extended downtime, or when camping in a secure location.

### Inflicting Conditions: Examples

**Challenge Moves:**
> *The dark elf assassin's Poisoned Blade inflicts Poisoned 2. A dragon's Fearsome Roar inflicts Frightened 3.*

**Consequences:**
> *Minor Consequence: "You deflect the blow but the acid splashes your arm — Burned 1."*
>
> *Major Consequence: "The giant's club smashes into your shield, knocking you off your feet. Mark 2 Stress and Prone 1."*

### Assigning Burdens

**Reserve Curse/Trauma Burdens for genuinely significant moments** — divine punishment, witnessing tragedy, prolonged dark magic exposure. Don't overuse them.

**Mark Recovery Method Clearly:**
When assigning a Burden, immediately clarify how it clears:
- *"That's Wounded 2 (Burden) — it'll reduce 1 tier per Long Rest."*
- *"That's Cursed 2 (Burden) — rest won't help. You'll need to break the curse."*

### Burdens (Persistent Impairments)

Burdens are persistent impairments that represent serious wounds, lasting trauma, powerful curses, and other significant harm that cannot be shaken off with a Short Rest or a few determined actions. They are rarer and weightier than Conditions — a sign that something has genuinely changed for the character.

**How Burdens Work:**

A Burden has a **name**, a **tier** (1–3), and a **recovery method**. Like Conditions, Burdens apply **1 Bane to all action rolls** while they persist.

- **Multiple Burdens:** A character can have multiple Burdens simultaneously (e.g., Wounded 3 + Cursed 2)
- **Same-name Burdens:** If you gain a Burden with the same name as an existing Burden, refresh to whichever tier is higher
- **Narrative Restrictions:** Burdens may carry fictional restrictions (Wounded limits strenuous activity, Cursed causes NPCs to react with fear). These are separate from the mechanical Bane penalty.

**Gaining Burdens:**

**Stress Overflow (most common):**
When your Stress track is full and you'd mark more, choose: take a Burden (Stress clears to 0) or be Taken Out.
- 1 Stress overflow → Burden tier 1
- 2 Stress overflow → Burden tier 2
- 3 Stress overflow → Burden tier 3

> *Example: Finn has 5/5 Stress. The ogre deals 2 Stress. He takes Wounded 1 (Burden) rather than be Taken Out. His Stress clears to 0/5 — a second wind, but now injured.*

**Severe Consequences (Disaster):**
When Complications reduce an outcome to Disaster, you suffer a Severe Consequence. The GM may assign a Burden alongside other catastrophic effects (Taken Out, objective fails, etc.).

> *Example: Aria rolls Setback on a rooftop jump. A Complication reduces it to Disaster (Severe Consequence). She's Taken Out — she crashes through the roof, unconscious and at the mercy of the guards below.*

**Death Moves:**
When significant enemies are defeated, they may trigger a Death Move — a final action that leaves a lasting mark. Death Move Burdens are tier 2 by default.

> *Example: The lich crumbles but whispers a curse. Finn gains Cursed 2 (Burden).*

**Curses, Trauma, Narrative Events:**
The GM may assign Burdens from significant fictional events — divine punishment, psychological trauma, prolonged dark magic exposure.

> *Example: After witnessing her village destroyed, Lyra gains Haunted 2 (Burden).*

**Recovery:**

Burdens do NOT tick down through action like Conditions. They require deliberate recovery, which should be clearly established when the Burden is gained.

**Long Rest (default):**
Most Burdens reduce by 1 tier per Long Rest (overnight, safe location).

| After | Tier Reduction |
|---|---|
| 1 Long Rest | Tier 3 → Tier 2 |
| 2 Long Rests | Tier 2 → Tier 1 |
| 3 Long Rests | Tier 1 → Clears |

Long rest recovery represents natural healing, gradual fading of fear, recovery over time. This is the default unless specified otherwise.

**Special Recovery:**
Some Burdens require specific narrative resolution — treatment, magic, items, or story events. The GM establishes this when assigning the Burden.

Common special recovery methods:
- **Medical treatment:** Healer/surgeon/extended care clears or reduces by 1 tier
- **Magical healing:** Spell/ritual/item removes entirely or reduces tier
- **Narrative resolution:** The condition must be resolved through story (curse lifted, quest completed, emotional wound addressed)

> *Example: Cursed 2 (Burden) cannot clear by rest. The party must find a high priest or ritual to break it.*

> *Example: Wounded 3 (Burden) clears 1 tier per Long Rest. But magical healing could clear it entirely in one treatment.*

### Condition Fiction Examples

**Physical Conditions:**
- **Poisoned:** "The toxin courses through your veins, making every movement sluggish"
- **Burned:** "The acid has seared your flesh, every touch sends jolts of pain"
- **Blinded:** "Your vision swims, you can barely make out shapes"
- **Stunned:** "Your head rings from the blow, thoughts scattered"
- **Bleeding:** "Blood flows freely from the wound, weakening you"

**Mental/Emotional Conditions:**
- **Frightened:** "The dragon's roar echoes in your mind — you want to flee"
- **Enraged:** "Rage overwhelms you — all you see is red"
- **Confused:** "The illusion magic has you disoriented, reality bends"
- **Demoralized:** "Their words cut deep, doubt creeps into your resolve"

**Positional/Tactical Conditions:**
- **Prone:** "You're on the ground, vulnerable"
- **Disarmed:** "Your weapon clatters away across the stones"
- **Grappled:** "Their arms lock around you, restricting your movement"
- **Exposed:** "You've lost your cover, fully visible to archers"

---

## Quick Reference

| Situation | Result |
|-----------|--------|
| Gain a Condition | Named + tier set at infliction (1–3) |
| Condition applies | 1 Bane to affected rolls |
| Multiple Conditions | Each applies 1 Bane (can have 3+); pool modifier cap is ±2d (±2 Boons/Banes) |
| Same Condition inflicted again | Refreshes to original tier |
| Make a roll where Condition applies | Reduce tier by 1 |
| Condition reaches tier 0 | Clears |
| Short rest (1 hour, safe location) | All Stress and all Conditions clear (Burdens persist) |
| Long rest (overnight) | All Stress and all Conditions clear; Burdens reduce 1 tier |
| Secondary Effect (Trait) | Reduce one relevant Condition by 1 tier |
| Burden | Persistent Condition — recovers via Long Rest (1 tier per rest) or special narrative resolution; does NOT clear on Short Rest |
| Stress track full | Choose: take a Burden or be Taken Out |
| Mark Stress | 1 (Minor Consequence) or 2 (Major Consequence) |
| Resist Consequence | Spend 1 Momentum, reduce Consequence Tier by 1 (automatic, no roll) |
| Assist | Mark 1 Stress, grant ally 1 Boon (see Chapter 2: Working Together) |
| Push Yourself | Mark 1 Stress, gain 1 Boon |
