# Unified Track System (DRAFT — Final)

**This draft would replace Chapter 3, line 183 ("Progress Tracks") and serve as the foundational concept that Stress, Conditions, and Burdens in Chapter 4 all reference.**

---

## Tracks

**Tracks** are the game's core bookkeeping tool. Whether you're wearing down an enemy, racing against a ticking clock, managing exhaustion, or working through poison, you're filling boxes on a Track.

Every Track works the same way:

- **Size** — How many boxes it has
- **Mark trigger** — What causes you to fill a box
- **Completion effect** — What happens when all boxes are full
- **Recovery rule** — How/when boxes clear (if at all)

That's the whole system. Everything else is just which trigger, which effect, and which recovery method applies to a given Track.

**Whether filling a Track is good news or bad news isn't a fixed rule — it's obvious from what the Track represents.** A Harm track filling means the enemy's beaten. A Stress track filling means trouble's caught up with you. Check the fiction, not a table.

---

## GM-Set Tracks

These have their size chosen by the GM per Challenge, scaled to the obstacle's difficulty.

| Track Type | Size | Mark When... | Full Means... | Clears When... |
|------------|------|--------------|---------------|----------------|
| **Harm** | 2/4/6/8+ (GM sets) | Success/Conflict on Clash (physical attack) — Enhanced Effect marks 2 | Enemy defeated or destroyed | N/A — retired on completion |
| **Will** | 2/4/6/8+ (GM sets) | Success/Conflict on Clash (intimidation) or Talk (persuasion) — Enhanced Effect marks 2 | Enemy breaks/flees (Clash) or convinced/allied (Talk) | N/A — retired on completion |
| **Obstacle** | 2/4/6/8+ (GM sets) | Success/Conflict on Defy (overcoming environmental challenge) — Enhanced Effect marks 2 | Obstacle overcome (lock picked, wall climbed, trap disarmed) | N/A — retired on completion |
| **Countdown** | 4/6/8/10+ (GM sets) | Time passes, PC fails a roll, or GM spends Suspense | The threatened event happens (guards arrive, ritual completes, building collapses) | N/A — retired on completion |

## Character Tracks

These have a fixed size, or a size set at the moment they're inflicted on a character.

| Track Type | Size | Mark When... | Full Means... | Clears When... |
|------------|------|--------------|---------------|----------------|
| **Stress** | 5 (fixed) | Consequence lands (1 Minor / 2 Major), or you voluntarily mark 1 (Push Yourself / Assist) | Choose: take a Burden Track, or be Taken Out | Fully on Short Rest or Long Rest |
| **Affliction** | 1-3 (set at infliction) | Any Action Roll where the Affliction applies (poison affects combat, fear affects persuasion) | The Affliction ends — you've worked through it | Automatically on Short Rest (even if not full) |
| **Burden** | 1-3 (set at infliction) | One Long Rest (default) OR a stated narrative condition (curse broken, antivenom administered) | The Burden ends | When track fills (via Long Rest or narrative condition) |

---

## Track Types Explained

### Progress Tracks (Harm, Will, Obstacle)

These measure advancement toward overcoming a Challenge. When you succeed on a relevant Action, mark 1 box. When the track fills, the Challenge is overcome.

- **Harm** tracks physical damage
- **Will** tracks breaking resolve (Clash) or building agreement (Talk)
- **Obstacle** tracks progress against environmental barriers

**Track sizes** represent Challenge difficulty:

| Size | Category | Examples |
|------|----------|----------|
| 0 | Trivial | Untrained guard, simple lock (no track, resolved on any success) |
| 2 | Minion / Quick | Bandit, basic obstacle, skeptical merchant |
| 4 | Standard | Veteran warrior, complex lock, hostile NPC |
| 6 | Elite / Extended | Champion fighter, fortified position, hostile faction |
| 8+ | Boss / Grand | Ancient dragon, legendary obstacle, enemy nation |

**Enhanced Effect** (from Trait invocation, see Chapter 6) marks **1 additional box** on any Progress Track — 2 boxes total instead of 1.

*(Enhanced Effect only applies to Progress Tracks because it comes from succeeding on a roll — the same condition that marks these tracks in the first place.)*

---

### Countdown Track (GM-facing)

The **Countdown Track** represents escalating threats — time pressure the PCs must beat. It's the only Track that works *against* the PCs.

The GM marks a Countdown when:
- Time passes ("You spend an hour searching — the ritual advances")
- A PC fails a roll that should accelerate the threat
- The GM spends Suspense (see Chapter 14) to represent off-screen progress

**When full, the threatened consequence arrives.** The ritual completes, guards arrive, the building collapses — whatever the Countdown represented.

Countdowns create urgency. The longer PCs deliberate or fail, the closer danger gets.

**Example:** "The cultists' ritual is a 6-box Countdown. Every 10 minutes of in-game time, I mark 1 box. When it fills, the demon breaks free."

---

### Stress Track (Your Resilience Buffer)

**Stress** is your primary defensive buffer — it absorbs incoming costs from Consequences. It's also a resource you can spend voluntarily for power.

**Stress is unique among Tracks:** It's the only one you can mark by choice (Push Yourself, Assist) to gain immediate mechanical benefits.

Mark Stress when:
- A Consequence lands (1 for Minor, 2 for Major)
- You **Push Yourself** — mark 1 Stress to gain +1 Boon before your Action Roll
- You **Assist** an ally — mark 1 Stress to grant them +1 Boon before their roll

**When your Stress track is full and you'd mark more:**
1. Calculate overflow (how much Stress couldn't fit)
2. Choose: **Take a Burden Track** or **be Taken Out**
3. If you take a Burden, clear 3 Stress (always flat) — you have breathing room again

**Recovery:** Stress clears fully on Short Rest (1 hour, safe location) or Long Rest (overnight, safe location).

**See Chapter 4 for complete Stress rules, Push Yourself, Assist, and Stress Overflow.**

---

### Affliction Tracks (Temporary Conditions)

**Afflictions** are temporary impairments — poison, fear, blindness, exhaustion. They're short-term states heroes shake off through action and rest.

An Affliction has a **name** (Poisoned, Frightened, Blinded) and a **size** (1–3 boxes), both set at infliction.

**Each Affliction applies 1 Bane to relevant Action Rolls.** When an Affliction applies, mark 1 box on its track. When the track fills, the Affliction clears — you've fought through it.

**"Relevant" means the Affliction would fictionally affect the action.** Poisoned affects combat and physical exertion. Frightened affects rolls involving the source of fear. Blinded affects sight-dependent actions. When in doubt, apply it — that's how Afflictions clear.

| Size | How It Works |
|------|--------------|
| **1-box** | Apply 1 Bane on first relevant roll, mark 1 box, Affliction clears |
| **2-box** | Apply 1 Bane on first relevant roll, mark 1 box. Apply 1 Bane on second relevant roll, mark 1 box, Affliction clears |
| **3-box** | Apply 1 Bane on first three relevant rolls (mark 1 box each time). After the third, Affliction clears |

**Think of it as "progress toward recovery."** Each time you act through the Affliction, you're closer to shaking it off. When the track fills, you've worked through it.

**Multiple Afflictions stack** — each applying its own 1 Bane (subject to the ±2 pool modifier cap).

**Refresh, not stack:** The same Affliction cannot stack. If you're Poisoned 2 and would become Poisoned again, it refreshes to Poisoned 2 — it doesn't become Poisoned 3 or 4.

**Afflictions always clear on Short Rest**, regardless of how many boxes remain. Fighting through poison accelerates recovery, but resting for an hour always works.

**See Chapter 4 for complete Affliction rules and common Affliction names.**

---

### Burden Tracks (Lasting Harm)

**Burdens** are persistent impairments — serious wounds, lasting trauma, powerful curses. They represent harm too significant to shake off quickly.

A Burden has a **name** (Wounded, Cursed, Haunted), a **size** (1–3 boxes), and a **recovery method** (Long Rest or narrative condition).

**Each Burden applies 1 Bane to relevant actions** (same as Afflictions — subject to ±2 cap). Multiple Burdens stack.

**Unlike Afflictions, Burdens don't tick down through action.** They persist until their specific recovery condition is met.

**Two recovery types:**

**Long Rest Recovery (default):** Mark 1 box per Long Rest. When the track fills, the Burden clears.
- Wounded 3: Takes 3 Long Rests to clear (mark 1 box each night)
- Wounded 1: Takes 1 Long Rest to clear

**Narrative Recovery:** The Burden persists until a specific fictional condition is met — rest alone won't help.
- *Cursed 2* — Requires finding a priest or breaking the ritual (2 boxes, but marks only when curse-breaking actions succeed)
- *Poisoned 3 (Wyvern Venom)* — Requires antivenom (rest does nothing; when antivenom is administered, mark all 3 boxes and clear immediately)

**The GM always tells you which recovery type applies** when you gain a Burden.

**Gaining Burdens:**
- **Stress Overflow (most common):** When your Stress track is full and you'd mark more, choose to take a Burden instead of being Taken Out. Overflow amount determines size (1 overflow = 1-box Burden, 2 = 2-box, 3+ = 3-box).
- **Severe Consequences (Disaster):** GM may assign a Burden alongside other catastrophic effects.
- **Death Moves:** When significant enemies are defeated, they may leave a lasting mark (tier 2 by default).

**See Chapter 4 for complete Burden rules and recovery examples.**

---

## Track Design Summary

**Progress Tracks (Harm/Will/Obstacle)** fill as you succeed → completion means victory.

**Countdown Tracks** fill as time passes or you fail → completion means danger arrives.

**Stress** fills as you take hits or spend it → completion means Burden-or-Taken-Out.

**Affliction Tracks** fill as you act through them → completion means recovery.

**Burden Tracks** fill as recovery conditions are met → completion means recovery.

One rule. Five applications. That's the system.

---

## What's Next

Now that you understand how Tracks work:

- **Chapter 4: Resilience** covers Stress, Afflictions, and Burdens in detail — including Push Yourself, Assist, Taken Out, and recovery timing
- **Chapter 13: Challenges** covers designing Harm/Will/Obstacle/Countdown Tracks for enemies and obstacles
- **Chapter 14: GM Tools** covers when and how to advance Countdown Tracks

**For how Consequences interact with Tracks, see "Consequence Tiers" earlier in this chapter.**
