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
- When your track is full and you would mark more Stress, choose: **take a Burden or be Taken Out**

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
- Clear all Conditions

**Long rest (overnight, safe location):**
- Clear all Stress
- Clear all Conditions

---

## Conditions

Conditions represent temporary impairment — poison coursing through your veins, fear gripping your mind, a wound slowing your movements. They are short-term states that skilled heroes shake off through action and rest.

### How Conditions Work

A Condition has a **name** and a **tier** — both set at the moment of infliction.

- The name describes the fictional state: Poisoned, Frightened, Blinded, Stunned
- The tier (1–3) represents severity and duration

**A Condition applies 1 Bane to all action rolls** while it persists.

**Multiple Conditions stack,** each applying 1 Bane, **up to a maximum of 2 Banes from Conditions total.**

> **GM Guidance:** **Default:** A Condition affects all action rolls — it's simpler and more consistent.
> 
> **Exception:** When a Condition clearly has no bearing on the action fictionally, it doesn't apply (and doesn't tick down). Examples:
> - Blinded doesn't affect recalling lore (Know)
> - Restrained doesn't affect examining your surroundings (Sense)
> - Deafened doesn't affect climbing a wall (Defy)
> 
> When in doubt, apply the Condition.

### Gaining Conditions

Conditions come from three sources:

**Challenge Moves:** Enemy abilities inflict Conditions directly, at a tier determined by the move.

> *The dark elf assassin's Poisoned Blade inflicts Poisoned 2. A dragon's Fearsome Roar inflicts Frightened 3.*

**Impact Moves:** The GM may inflict a Condition (tier 1) instead of or alongside marking Stress as a consequence.

> *"You deflect the blow but the acid splashes your arm — Burned 1."*

> *"The giant's club smashes into your shield, knocking you off your feet. Mark 1 Stress and Prone 1."*

**Stress Overflow:** When your Stress track is full and you would mark more Stress, choose:

- **Take a Burden** — A persistent Condition that won't clear on short rest. Set tier based on amount (1-3 Stress → tier 1-3). Requires narrative resolution to clear. You stay in the fight but carry a lasting consequence.

- **Be Taken Out** — You're unconscious, fleeing, captured, or otherwise removed from the scene. The GM narrates what happens based on context.

This choice creates dramatic "push through at a cost" moments — heroes can stay in the fight but risk lasting harm.

### Condition Tiers

The tier set at infliction is the **maximum severity** of that Condition. It never escalates beyond its initial tier regardless of how many times the same Condition is inflicted — subsequent hits of the same Condition simply refresh it back to its maximum.

| Tier | Bane | Clears After |
|------|------|--------------|
| 1 | 1 Bane | 1 relevant action roll |
| 2 | 1 Bane | 2 relevant action rolls |
| 3 | 1 Bane | 3 relevant action rolls |

Each time you make an action roll where the Condition applies, reduce its tier by 1. When it reaches 0, it clears.

**All Conditions clear on short rest** (10–15 minutes of safety), regardless of remaining tier.

### Multiple Conditions

You can have multiple different Conditions simultaneously. Each tracks independently.

**Bane Stacking:** Multiple Conditions each apply 1 Bane, up to a **maximum of 2 Banes from Conditions total.**

> *You are Poisoned 2 and Frightened 1. On a roll where both apply, you suffer 2 Banes total (capped). If you also become Blinded 1, you're at 3 Conditions but still only 2 Banes from Conditions.*

**Refresh, Not Stack:** The same Condition cannot stack beyond its initial tier. If you are Poisoned 2 and would become Poisoned again, it refreshes to Poisoned 2 — it does not become Poisoned 3 or Poisoned 4.

### Recovering from Conditions

**Through action:** Make action rolls where the Condition applies. Each relevant roll reduces the tier by 1.

**Through short rest:** All Conditions clear after a short rest (10–15 minutes of safety).

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

Reduce the number by 1 each time you act through it. Erase when it reaches 0 or after short rest.

### Example in Play

> **GM:** The dark elf assassin was disguised as the butler. At the last second you notice as they draw their poisoned blade. Defy with 1 Bane — you were caught off guard.
>
> **Player:** A 3 and a 5 — Conflict. I'll invoke Blademaster to Build Momentum.
>
> **GM:** You partially parry the blow but the blade nicks you. You feel the poison begin to work. Poisoned 2. What do you do?
>
> **Player:** I Clash — drive them back against the wall.
>
> **GM:** The poison affects your movement. 1 Bane. Roll it.
>
> **Player:** A 4 and a 2 — Conflict again. I use my Blademaster Trait for Greater Effect. Poisoned drops to 1.
>
> **GM:** You slam them hard into the wall — mark two ticks on their track. They snarl and strike back — Poisoned Blade triggers. You're already Poisoned 1, so it refreshes to Poisoned 2. Mark 1 Stress.
>
> **Player:** Still Poisoned 2. I spend my Momentum to Act with Potency and Clash again.
>
> **GM:** Edge from Potency offsets the Bane — roll clean.
>
> **Player:** Two 5s and a 6 — Success. Poisoned drops to 1 again.
>
> **GM:** Another solid hit — mark a third tick. They're in trouble now. What do you do?
>
> **Player:** I invoke my Blademaster Trait — Secondary Effect to reduce Poisoned by 1. Fictionally, I'm fighting through the pain with trained discipline.
>
> **GM:** The poison clears. You're clean. The assassin is one tick from done.

---

## Resist Consequence

**Cost:** 1 Momentum

When you would suffer a consequence (Stress, Condition, or narrative setback), spend 1 Momentum and roll Defy to reduce or avoid it.

| Outcome | Effect |
|---------|--------|
| **Success** | Mechanical: Reduce by 2 steps (2 Stress → 0, tier 3 → tier 1, tier 2 → clear) / Narrative: Avoid entirely |
| **Conflict** | Mechanical: Reduce by 1 step (2 Stress → 1, tier 3 → tier 2, tier 2 → tier 1) / Narrative: Reduce severity |
| **Setback** | Take the full consequence — Momentum is spent, nothing reduced |

---

## Taken Out

You are **Taken Out** when:
- You would mark Stress while your track is full and cannot or choose not to take a Condition

**The GM narrates what happens** based on context — unconscious, fleeing, captured, broken. Taken Out is not automatically death.

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

**Short rests** (10-15 minutes) should happen:
- After each significant combat
- During travel when the party takes a breather
- When players explicitly seek safety to catch their breath

This ensures Conditions don't carry over from scene to scene, while still making them relevant within a scene.

**Long rests** (overnight) should happen:
- After returning to town or safe haven
- During extended downtime between adventures
- When the party explicitly makes camp in a secure location

### Burdens (Persistent Conditions)

Some Conditions persist beyond normal recovery. These are **Burdens** — lasting consequences that require narrative resolution.

**Sources of Burdens:**
- **Stress Overflow** — When Stress track is full and you'd mark more, you can take a Burden instead of being Taken Out (most common source)
- **Boss Death Moves** — Signature abilities from major enemies
- **Catastrophic events** — Fell from tower, soul-touched by demon, witnessed horror
- **Curses and afflictions** — Supernatural hexes, magical diseases, binding oaths

**Burden mechanics:**
- Functions like a Condition: has name + tier, applies 1 Bane
- Tiers tick down through relevant action rolls (same as regular Conditions)
- **Does NOT clear on short rest** — persists until tier reaches 0 OR narrative resolution
- Counts toward 2 Bane cap from Conditions

**Burden recovery:**
- **Through action:** Tick down tier by 1 per relevant action roll (slow but steady)
- **Through narrative resolution:** Quest to lift curse, powerful healing magic, extended treatment with specialist, meaningful character moment
- **Through long rest:** Burdens tick down 1 tier on long rest (optional rule for less gritty games)

**Mark Burdens clearly:** When inflicting a Burden, say "This is a Burden — it won't clear on short rest." Players need to know the stakes.

**Stress Overflow Burdens are common** — whenever players push past their Stress limit to stay in the fight. Other Burdens should be rare and narratively significant.

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
| Multiple Conditions | Each applies 1 Bane, maximum 2 Banes from Conditions total |
| Same Condition inflicted again | Refreshes to original tier |
| Make a roll where Condition applies | Reduce tier by 1 |
| Condition reaches tier 0 | Clears |
| Short rest (10–15 min) | All Conditions clear |
| Secondary Effect (Trait) | Reduce one relevant Condition by 1 tier |
| Burden | Persistent Condition — ticks down through action, does NOT clear on short rest |
| Stress track full | Choose: take a Burden or be Taken Out |
| Mark Stress | 1 (soft Impact Move) or 2 (hard Impact Move) |
| Quick Assist | Mark 1 Stress, grant ally 1 Edge |
| Push Yourself | Mark 1 Stress, gain 1 Edge |
