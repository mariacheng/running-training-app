# Running Training App

## Stride Block (`stride-block.html`)

A phone-first half marathon and marathon training planner. It follows the same setup flow as Crux Block.

**Setup (8 steps):** Timeline → Goal → Running now → Body check → Schedule & cross-training → Pace test → AI coach → Review

**How plans are built (conventional guidance):**
- About 80% of running is easy (80/20 intensity split).
- Cutback weeks cut volume about 25%. They come every 3rd week for beginners (Higdon-style) and every 4th for runners already doing 3+ runs a week (Pfitzinger-style).
- The long run grows by at most about 1.6 km a week for a half and 2.4 km for a full, or 25% slower on the gentle setting. It peaks around 16–18 km for a half and 32 km for a full.
- Weekly distance grows about 10–15% at most.
- Taper: 2 weeks for a half, 3 for a full, both including race week.
- Phases: Base → Build (tempo/intervals) → Peak (race pace) → Taper → Race week.
- Run/walk intervals for runners who can't yet run 30 minutes, progressing to continuous running.
- Strength and prehab circuit, with extra moves for the areas flagged in setup.
- Paces come from a recent race time (Riegel formula) or by effort, with optional re-tests in cutback weeks.

**Tabs:** Plan, Calendar, Library (paces, rules, workouts, strength moves), Progress (weekly distance chart, log), Setup.

Data is saved in the browser (localStorage). The AI coach uses the artifact `sample` capability when the page is opened on claude.ai.
