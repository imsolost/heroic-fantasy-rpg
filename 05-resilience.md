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

**From Impact Moves (most common):**
- **Soft Impact Move** → Mark 1 Stress
- **Hard Impact Move** → Mark 2 Stress

**Voluntarily (as a resource):**
- **Quick Assist** → Mark 1 Stress to grant an ally 1 Edge on their next roll
- **Push Yourself** → Mark 1 Stress to gain 1 Edge on your roll

### Recovery

**Short rest (10–15 minutes of safety):**
- Clear all Stress
- Clear all Conditions (Burdens do NOT clear)

**Long rest (overnight, safe location):**
- Clear all Stress
- Clear all Conditions (including Burdens)

---

## Conditions

Conditions represent temporary impairment — poison coursing through your veins, fear gripping your mind, a wound slowing your movements. They are short-term states that skilled heroes shake off through action and rest.

### How Conditions Work

A Condition has a **name** and a **tier** — both set at the moment of infliction.

- The name describes the fictional state: Poisoned, Frightened, Blinded, Stunned
- The tier (1–3) represents severity and duration

**A Condition applies 1 Bane to all action rolls** while it persists.

**Multiple Conditions stack** — each applying 1 Bane. You can have 3, 4, or more Conditions simultaneously.

**Pool modifier cap: ±2d (universal rule).** All dice pool modifiers cap at +2d Edge or -2d Bane, regardless of how many sources you have. This applies to everything (Conditions, difficulty, environment, etc.), not just Conditions.

**Edge and Bane cancel 1:1 before applying the cap.** If you have 3 Conditions (3 Banes) and 1 Edge, they cancel to 2 net Banes — within the cap. If you have 3 Conditions (3 Banes) and no Edge, the net is 3 Banes → capped at -2d when applied to your pool.

**Why the ±2d cap?** Even heroes at their worst (or best) retain some capacity for meaningful action. The cap prevents auto-fail or auto-success territory while keeping accumulated harm impactful.

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

- **Take a Burden** — A persistent Condition that won't clear on short rest. Set tier based on amount (1-3 Stress → tier 1-3). **Your Stress track immediately clears to 0**, allowing you to absorb future hits. You stay in the fight but carry a lasting consequence.

- **Be Taken Out** — You're unconscious, fleeing, captured, or otherwise removed from the scene. The GM narrates what happens based on context. Your Stress clears when you recover.

This choice creates dramatic "push through at a cost" moments — heroes can stay in the fight with a second wind, but risk lasting harm. Taking a Burden represents pushing through the pain and finding the will to continue, at the cost of a persistent injury.

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

**Bane Stacking:** Multiple Conditions each apply 1 Bane. You can have 3, 4, or more Conditions.

> *You are Poisoned 2 and Frightened 1. Both apply → 2 Banes. If you also become Blinded 1, you have 3 Conditions → 3 Banes. When you roll, the pool modifier cap (-2d maximum) applies, so 3 Banes are capped at -2d to your dice pool.*

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
- **Stress Overflow:** You would mark Stress while your track is full and cannot or choose not to take a Burden
- **Burden Escalation:** The GM may rule you're Taken Out from overwhelming sources (Death Moves, Disaster, narrative events that would incapacitate you)

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

### Burdens (Persistent Impairments)

Burdens are persistent impairments that represent serious wounds, lasting trauma, powerful curses, and other significant harm that cannot be shaken off with a short rest or a few determined actions. They are rarer and weightier than Conditions — a sign that something has genuinely changed for the character.

**How Burdens Work:**

A Burden has a **name**, a **tier** (1–3), and a **recovery method**. Like Conditions, Burdens apply **1 Bane to all action rolls** while they persist.

- **Multiple Burdens:** A character can have multiple Burdens simultaneously (e.g., Wounded 3 + Cursed 2)
- **Same-name Burdens:** If you gain a Burden with the same name as an existing Burden, refresh to whichever tier is higher
- **Bane Cap:** All Banes (from Conditions, Burdens, and other sources) share the -2d cap. Edge and Bane cancel 1:1 before applying the cap.
- **Narrative Restrictions:** Burdens may carry fictional restrictions (Wounded limits strenuous activity, Cursed causes NPCs to react with fear). These are separate from the mechanical Bane penalty.

**Gaining Burdens:**

**Stress Overflow (most common):**
When your Stress track is full and you'd mark more, choose: take a Burden (Stress clears to 0) or be Taken Out.
- 1 Stress overflow → Burden tier 1
- 2 Stress overflow → Burden tier 2
- 3 Stress overflow → Burden tier 3

> *Example: Finn has 5/5 Stress. The ogre deals 2 Stress. He takes Wounded 2 (Burden) rather than be Taken Out. His Stress clears to 0/5 — a second wind, but now injured.*

**Disaster:**
When a Setback is reduced by Complications, the result is Disaster. The GM may assign a Burden alongside other consequences.

> *Example: Aria rolls Setback on a rooftop jump. A Complication reduces it to Disaster. She marks 2 Stress and gains Sprained Ankle 1 (Burden).*

**Death Moves:**
When significant enemies are defeated, they may trigger a Death Move — a final action that leaves a lasting mark. Death Move Burdens are tier 2 by default.

> *Example: The lich crumbles but whispers a curse. Finn gains Cursed 2 (Burden).*

**Curses, Trauma, Narrative Events:**
The GM may assign Burdens from significant fictional events — divine punishment, psychological trauma, prolonged dark magic exposure. Reserve these for genuinely significant moments.

> *Example: After witnessing her village destroyed, Lyra gains Haunted 2 (Burden).*

**Recovery:**

Burdens do NOT tick down through action like Conditions. They require deliberate recovery, which should be clearly established when the Burden is gained.

**Long Rest (default):**
Most Burdens reduce by 1 tier per long rest (overnight, safe location).

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

> *Example: Wounded 3 (Burden) clears 1 tier per long rest. But magical healing could clear it entirely in one treatment.*

**Mark Recovery Method Clearly:**
When assigning a Burden, immediately clarify how it clears:
- *"That's Wounded 2 (Burden) — it'll reduce 1 tier per long rest."*
- *"That's Cursed 2 (Burden) — rest won't help. You'll need to break the curse."*

**Burdens vs. Conditions:**

| | Conditions | Burdens |
|---|---|---|
| **Source** | Challenge Moves, Impact Moves | Stress overflow, Disaster, Death Moves, narrative events |
| **Frequency** | Common | Rare |
| **Bane** | 1 Bane each | 1 Bane each |
| **Recovery** | Tick down through action; clear on short rest | Long rest (1 tier per) or special recovery |
| **Weight** | Temporary impairment | Lasting consequence |

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
| Multiple Conditions | Each applies 1 Bane (can have 3+); pool modifier cap is ±2d (universal) |
| Same Condition inflicted again | Refreshes to original tier |
| Make a roll where Condition applies | Reduce tier by 1 |
| Condition reaches tier 0 | Clears |
| Short rest (10–15 min) | All Stress and all Conditions clear (Burdens persist) |
| Long rest (overnight) | All Stress and all Conditions clear; Burdens reduce 1 tier |
| Secondary Effect (Trait) | Reduce one relevant Condition by 1 tier |
| Burden | Persistent Condition — recovers via Long Rest (1 tier per rest) or special narrative resolution; does NOT clear on short rest |
| Stress track full | Choose: take a Burden or be Taken Out |
| Mark Stress | 1 (soft Impact Move) or 2 (hard Impact Move) |
| Quick Assist | Mark 1 Stress, grant ally 1 Edge |
| Push Yourself | Mark 1 Stress, gain 1 Edge |
