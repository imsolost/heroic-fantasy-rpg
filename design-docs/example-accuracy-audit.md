# Example Accuracy Audit — September 2026

## Purpose
Identify all outdated examples and references following the September 2026 simplification:
- **Removed:** Baseline Push Yourself, Assist mechanic, Resist Consequence
- **Changed:** Create an Opening (replaces Assist), Momentum spending (now 2 ways not 3), session reset
- **Enemy modeling:** Consequences ARE enemy actions (not separate turns)

---

## Critical Findings (High Priority)

### 1. **Quick Start Guide** — Multiple outdated mechanics ✅ FIXED
**File:** `reorganized/quick-start-guide.md`

**Line 218:** Battleborn talent reference
```markdown
- **Battleborn** — Gain Edge in battle; mark to Push Yourself without cost
```
✅ **Fixed:** Removed "or Resist" reference

**Line 228:** Stress Track description
```markdown
- **Stress Track:** 5 boxes (mark when you suffer harm or via Talent effects)
```
✅ **Fixed:** Changed from "or Push Yourself" to "or via Talent effects"

**Line 470-471:** Action options
```markdown
**Mark Stress when you:**
- Suffer physical harm
- Endure exhausting or stressful situations
- Some Talents let you mark Stress for benefits (Push Yourself)

**Stress is your defensive buffer.** It protects you from harm and Conditions. Some Talents let you voluntarily mark it to Push Yourself (gain Boons or other benefits), but baseline Stress is about absorbing consequences.
```
✅ **Fixed:** Removed "Use Stress to" section with baseline Push Yourself and Assist. Replaced with explanation that Stress is primarily defensive, with Talent-based voluntary marking.

**Status:** ✅ COMPLETE

---

### 2. **Chapter 12 (GM Moves)** — Enemy turn reference ✅ FIXED
**File:** `reorganized/part-3-running-the-game/12-gm-moves.md`

**Line 247:** Move selection table
```markdown
| Enemy acts in combat | Impact Move (spend Suspense) | Use Challenge Moves if available; enemies act through Consequences (PC rolls Conflict/Setback) or by spending Suspense to interrupt |
```
✅ **Fixed:** Changed "Enemy's turn in combat" to "Enemy acts in combat" with explicit clarification that enemies act through Consequences or by spending Suspense

**Line 305:** Interrupting flow
```markdown
**When urgent:** Interrupt with enemy action (spend Suspense), then ask "What do you do?"
```
✅ **Verified Correct:** This correctly shows that interrupting requires spending Suspense

**Status:** ✅ COMPLETE

---

### 3. **Assist References** — Fully removed mechanic
**Files with "Assist" references:**

**Draft/Archive Files (Low Priority):**
- `reorganized/talents-draft.md` (line 81, 381) — Draft talents referencing Assist
- `reorganized/unified-track-draft.md` (multiple) — Draft file, not canonical
- `reorganized/chapter-4-restructured-draft.md` (multiple) — Draft file, explicitly notes removal
- `reorganized/archive/MIGRATION-PLAN.md` — Archive, expected

**Documentation Files:**
- `reorganized/IMPLEMENTATION-SUMMARY.md` (lines 33, 115) — Summary doc
- `reorganized/README.md` (line 52) — Chapter completion checklist

**Status:** 🟢 LOW PRIORITY — Mostly draft/archive files, not player-facing

---

### 4. **Baseline Push Yourself References**
**Files referencing Push Yourself outside Talents:**

**Quick Start Guide:** (already flagged above)

**Draft Files:**
- `reorganized/talents-draft.md` — Multiple Talents with "Push Yourself to..." patterns
  - ⚠️ **Needs Review:** Are these Talents correctly structured? Each should mark this Talent, not baseline Stress.
  
**Chapter 4 Restructured Draft:**
- `reorganized/chapter-4-restructured-draft.md` — Extensive Push Yourself sections
  - ❌ **Issue:** This is a DRAFT that wasn't integrated. Canonical Ch. 4 is `part-1-the-rules/04-resilience.md`

**Status:** 🟡 MEDIUM — Talent structure needs verification

---

### 5. **Resist Consequence References**
**Only found in archive files** — ✅ Already cleaned from canonical chapters

**Files:**
- `reorganized/archive/MIGRATION-PLAN.md`
- `reorganized/archive/DRIFT-ANALYSIS.md`

**Status:** ✅ RESOLVED — No action needed

---

## Systematic Review by Chapter

### Part 1: The Rules (Canonical Files)

| Chapter | File | Status | Issues Found |
|---------|------|--------|--------------|
| Ch. 1 | `01-the-action-roll.md` | 🟡 Needs Review | Count inline examples |
| Ch. 2 | `02-taking-action.md` | 🟡 Needs Review | Count inline examples |
| Ch. 3 | `03-consequences.md` | ✅ Recently Updated | Resist Consequence removed |
| Ch. 4 | `04-resilience.md` | ✅ Recently Updated | Push Yourself/Assist removed |
| Ch. 5 | `05-momentum.md` | ✅ Recently Updated | Session reset added |
| Ch. 6 | `06-traits.md` | 🟡 Needs Review | Check Special Effect examples |

---

### Part 2: Your Character

| Chapter | File | Status | Issues Found |
|---------|------|--------|--------------|
| Ch. 7 | `07-*.md` (character creation) | 🟡 Needs Review | Not yet checked |
| Ch. 8 | `08-*.md` (approaches) | 🟡 Needs Review | Not yet checked |
| Ch. 9 | `09-callings.md` | ✅ Recently Updated | Three Talents updated for Create Opening |
| Ch. 10 | `10-spellcasting.md` | ✅ Recently Updated | Potent Actions consolidated |

---

### Part 3: Running the Game

| Chapter | File | Status | Issues Found |
|---------|------|--------|--------------|
| Ch. 12 | `12-gm-moves.md` | 🔴 CRITICAL | "Enemy's turn" reference |
| Ch. 13 | `13-*.md` (challenges) | 🟡 Needs Review | Not yet checked |
| Ch. 14 | `14-*.md` | 🟡 Needs Review | Not yet checked |
| Ch. 15 | `15-*.md` | 🟡 Needs Review | Not yet checked |

---

## Example Count by Section

| Section | Example Count | Review Status |
|---------|---------------|---------------|
| Part 1 (6 chapters) | ~87 instances | ⏳ In Progress |
| Part 2 | TBD | ⏳ Pending |
| Part 3 | TBD | ⏳ Pending |
| Quick Start | ~15 instances | 🔴 Issues Found |

---

## Recommended Fix Priority

### Phase 1: Critical (Player-Facing First-Read) ✅ COMPLETE
1. ✅ **Quick Start Guide** — Fixed all Assist/baseline Push Yourself/Resist references
2. ✅ **Chapter 12 (GM Moves)** — Fixed "enemy's turn" language

### Phase 2: Important (Core Rules) ✅ COMPLETE

**Phase 2 Complete (Chapters 1, 2, 4, 6):**
- ✅ **Chapter 1 (The Action Roll)** — All examples correct. References to Create an Opening (Momentum) and Talent-based Push Yourself are accurate.
- ✅ **Chapter 2 (Taking Action)** — All examples correct. Potent Actions section correctly references Talent activation.
- ✅ **Chapter 4 (Resilience)** — Push Yourself section correct. Rule "You can only Push Yourself once per Action Roll" already in place (line 53).
- ✅ **Chapter 6 (Traits)** — All examples correct. Special Effects examples use correct mechanics.

**Status:** No outdated mechanics found in core rules chapters. Push Yourself is correctly defined as a formal game term limited to once per action roll.

---

### Phase 2.5: Talents Draft Review ✅ CORRECT AS-IS

**File:** `reorganized/talents-draft.md`

**Previous assessment was incorrect.** The draft terminology is accurate:

- "Push Yourself to..." is the correct pattern for Talents that use the Push Yourself mechanic
- Chapter 4 line 53 already limits Push Yourself to once per action roll
- Some Talents use "Push Yourself" (most common pattern)
- Other Talents are checkbox abilities with unique activation conditions (Beast Master, Bodyguard, Inspire Greatness)

**No changes needed to talents-draft.md terminology.**

---

### Phase 3: Completeness (Later Chapters) — PENDING
6. **Part 2 (Ch. 7-10)** — Already partially updated, verify remaining chapters
7. **Part 3 (Ch. 13-15)** — Full review of GM-facing examples

### Phase 4: Cleanup (Documentation)
8. **README.md** — Update chapter completion notes
9. **IMPLEMENTATION-SUMMARY.md** — Update to reflect September changes

---

## Draft vs. Canonical Files

**These DRAFT files are NOT canonical and should be ignored or archived:**
- `reorganized/unified-track-draft.md`
- `reorganized/chapter-4-restructured-draft.md`
- `reorganized/talents-draft.md` (unless this is being integrated soon)

**Canonical locations:**
- Ch. 3: `part-1-the-rules/03-consequences.md`
- Ch. 4: `part-1-the-rules/04-resilience.md`
- Ch. 5: `part-1-the-rules/05-momentum.md`
- Talents: `part-2-your-character/09-callings.md` (partial, Talents section)

---

## September 14, 2026: Assist Reintroduction

### Changes

Reintroduced **Assist** as subsection of Create an Opening with constraints:
- **Fictional positioning** required (close enough, relevant capability)
- **Shared risk** required (helper faces same consequence as roller)

### Files Updated
- `part-1-the-rules/05-momentum.md` — Restructured Create an Opening with "For Yourself" and "Assist (For an Ally)" subsections
- `part-1-the-rules/04-resilience.md` — Updated Teamwork section to reference Assist rules
- `quick-start-guide.md` — Updated Create an Opening to show two modes

### Design Examples Needing Updates

**File:** `design-docs/mixed-party-composition-example.md`

**Issues:**
- Line 86: Lyra Assists Kael's dodge — needs position verification under new rules
- Line 100: Lyra "creates distraction" with thrown dagger — may not qualify as Assist (not directly helping Kael's action)
- **Line 110: RULE VIOLATION** — Shows Kael using Create an Opening (self) + Lyra's Create an Opening stacking on same roll. Rule says "Only one character can Create an Opening for a given roll"

**Status:** Needs full rewrite to comply with new Assist rules + fix stacking violation

---

## Next Steps

1. ✅ **Phase 1 Complete** — Quick Start Guide and Chapter 12 fixed
2. ✅ **Phase 2 Complete** — Core rules chapters (1, 2, 4, 6) verified accurate
3. **Phase 3 Pending** — Review Part 2 (Ch. 7-10) and Part 3 (Ch. 13-15) for any remaining outdated examples

---

## Notes

- **Push Yourself** is correctly defined as a formal game term (like Grimwild's approach)
- Chapter 4 line 53 already limits Push Yourself to once per action roll
- Different Talent types: some use "Push Yourself," others are checkbox abilities with unique conditions
- **Enemy modeling:** Correctly clarified in Ch. 12 - enemies act through Consequences or by spending Suspense, not separate turns
