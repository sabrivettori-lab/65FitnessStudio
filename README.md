# 65 Fitness Studio — 12-Week Plan

Personal workout tracker for the 12-week block. One self-contained `index.html`
with the CSS and JavaScript inside it. Nothing to install, nothing to build.

Live at **https://sabrivettori-lab.github.io/65FitnessStudio/**

---

## What it does

**The week is the unit.** It runs Sunday to Saturday. You see one week at a
time, you tick off what you did, and on Sunday the next week starts clean.
Finished weeks stay readable — tap any number in the 12-week strip to look back.

**You pick the workout per day.** Every day has a *What I'm doing* dropdown.
It starts on the planned session, but you can change it to any other session, to
one of the workouts from the previous plan, or to a rest day. A day set to rest
stops counting towards that week's target.

**One weight per exercise.** Log the heaviest set you managed — a single number,
not a row per set. Last time's number for that exercise shows underneath, so you
know what to beat.

**You can swap any exercise.** Tap *Swap this exercise* and choose a replacement
from the full library. The card remembers what it replaced and offers to put the
original back.

**Form videos.** Every exercise has a Watch button that opens a YouTube search
for that movement.

---

## The exercise library

125 exercises in three parts:

| Part | Grouped by | Count |
|---|---|---|
| Strength | Muscle group — glutes, hamstrings, quads, calves, back, chest, shoulders, biceps, triceps, core | 75 |
| HIIT and conditioning | Type — interval formats, full-body explosive, lower body power, upper body and core under fatigue, machines and sprints | 46 |
| Mobility and recovery | — | 4 |

Each exercise carries a tag saying where it came from:

- **Plan** — in the current 12-week plan
- **Previous** — from the earlier version of this app, kept so nothing is lost
- **Added** — a suggestion, in neither plan

Search the library by name or by muscle group.

---

## Where your data lives

**In your phone's browser, not on GitHub.** GitHub Pages only serves fixed
files; it has no database. Everything you type is stored locally under the key
`r2-65:block-v2`.

This means:

- Clear Safari's website data and your history is gone.
- A new phone starts empty.
- Nothing syncs between devices.

So **tap Export about once a week** and keep the file (AirDrop it to yourself,
save it to iCloud, email it). Import restores it on any device.

---

## Editing the plan

Everything you would want to change sits at the top of the `<script>` block in
`index.html`.

**To change which session lands on which day by default**, edit `DEFAULT_WEEK`.
Sunday first:

```js
const DEFAULT_WEEK = ["lower-glutes","upper","hiit-core","lower-legs","upper-shape","full-body","recovery"];
```

**To change a session's exercises or sets and reps**, edit that session in
`SESSIONS`. Each line points at a library `id` and gives a dose:

```js
{ex:"hip-thrust", d:"4 × 8–10"}
```

**To add an exercise to the library**, add it to the right muscle group in
`LIBRARY`. Give it an `id` that is not already taken, a name, and a YouTube
search string.

**To make the 12 weeks differ from each other.** Right now the same week repeats
for all twelve, and only the weight you lift changes. If a week should differ,
add it to `WEEK_OVERRIDES` — nothing else needs rewriting:

```js
const WEEK_OVERRIDES = {
  5: { days:["recovery","upper","hiit-core","lower-legs","upper-shape","full-body","recovery"] },
  9: { dose:{ "back-squat":"5 × 5", "hip-thrust":"4 × 6" } }
};
```

`days` replaces which session lands on which weekday that week.
`dose` replaces the sets and reps for those exercise ids that week.

**Never change an `id` that already has weights logged against it** — the saved
history is keyed on the id, and renaming it orphans the data. Change the `n`
(the displayed name) instead.

---

## History

The previous version of this app was a 6-week block spread over six files
(`index.html`, `sunday.html`, `wednesday.html`, `friday.html`, `saturday.html`,
`hiit.html`), with the exercises typed directly into the markup and a row of
inputs for every set. Those files were removed when this version replaced them.
All five of their workouts and all of their exercises are preserved here — the
workouts under *Previous plan* in the day dropdown, the exercises tagged
**Previous** in the library. The old files remain in the git history if you ever
need them.

Logs from that version used different storage keys (`r2-65:logs`,
`r2-65:completed`, `r2-65:swaps`) and are not read by this version. If you want
that history, export it from the old app before this one replaces it.

---

## Not medical advice

The training rules and any nutrition figures here come from your own plan, not
from a qualified professional. At a large calorie deficit, one session with a
registered dietitian is worth having.
