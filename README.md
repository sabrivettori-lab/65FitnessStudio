# 65 Fitness Studio — 12-Week Plan

Personal workout tracker for the 12-week block. One self-contained `index.html`
with the CSS and JavaScript inside it. Nothing to install, nothing to build.

Live at **https://sabrivettori-lab.github.io/65FitnessStudio/**

---

## The plan (block from 15 November 2026)

| Day | Session |
|---|---|
| Sunday | Rest |
| Monday | Day A · glutes, chest and back |
| Tuesday | HIIT in the Nike Training Club app, low impact, 20–25 min |
| Wednesday | Day B · legs, back and shoulder health |
| Thursday | Mobility / yoga, about 30 min |
| Friday | Day C · hamstrings, back and arms |
| Saturday | HIIT in the NTC app, 20–25 min |

Every day: 6,000 steps.

**Strength.** Three full-body sessions, each with a lower-body lead lift, a
push, a pull, a shoulder or arm exercise and a two-exercise core superset. The
exercises stay the same for all twelve weeks so the weight can go up. Two
exceptions: the squat (goblet, then back squat) and the hinge (dumbbell RDL,
then barbell RDL) move to the barbell from week 5, and the core pair changes
each phase.

| Phase | Weeks | Main lift | Other compound lifts |
|---|---|---|---|
| 1 · Base | 1–4 | 3 × 10–12 | 3 × 10–12 |
| 2 · Strength | 5–8 | 4 × 6–8 | 3 × 8–10 |
| 3 · Heavy | 9–12 | 4 × 5–6 | 3 × 10–15 |

**Session order.** Three full-body sessions a week, so glutes are trained about
three times a week and every other muscle at least twice. Every session has the
same five groups: main lift 1 and main lift 2 (straight sets, full rest), a
free-weight superset, a machine superset, then core. Both cable columns and the
bar are set once at the start of the session (the Machine box on the card), so
nothing is reconfigured inside a superset; equipment changes only between
groups. Supersets pair opposing or unrelated muscles, never two for the same
muscle (Zhang, Weakley et al. 2025: same-muscle pairs lowered volume load;
opposing pairs raised reps). This follows the research checked on 16 November 2026: training
frequency matters little once each muscle gets two or more sessions
(Schoenfeld, Grgic & Krieger 2019; ACSM 2026), full-body and split routines gave
the same results in women (Pedersen et al. 2022), strength gains are largest for
exercises done first (Nunes et al. 2021), and supersets save time without losing
volume (Weakley et al.).

**Shoulders.** No overhead pressing for now (shoulder press removed; the phase 3
Pallof press stays at chest height), until the stabilisers are stronger and the
physio agrees. Stabiliser work: cable external rotation (A), bench Y raise and
side-lying dumbbell external rotation (B), push-up plus (C), plus band
pull-aparts and wall slides in every warm-up. Lateral raises and face pulls stay.

**Core.** Crunches limited on physio advice (November 2026): only a slow bicycle
(criss-cross) crunch, 2 sets, at the end of A and C.
Two exercises as a superset, 3 sets: A side-focused (side plank with hip dips,
Copenhagen plank, Pallof variations), B front-focused (RKC plank, bear crawl,
body saw, renegade row, ab wheel, plank pull-through), C loaded carries and the
weighted dead bug. Body saw, ab wheel and world's greatest stretch are to be
cleared with the physio before they come up.

**Hips.** Every warm-up includes hip circles, 90/90 switches and adductor
rock-backs. Thursday is a hip mobility session of eight exercises. New exercises
without a chosen video show a *Find a video* box that opens a YouTube search.

**Videos play in the app.** Tapping a thumbnail opens the video in a player on
the page (via youtube-nocookie.com). "Open in YouTube instead" under the player
leaves the app only when tapped. Every video in the plan was checked on 16
November 2026 with YouTube's embed check, so it exists and allows playback
inside another page.

Weeks 4 and 8 are lighter: same exercises and weights, about half the sets. The
app halves the sets on screen in those weeks. A 30-minute **Short session
(travel)** sits in the day dropdown and counts as strength.

The plan was reviewed on 16 November 2026 by a separate Claude agent briefed as
a women's-health coach (not a qualified coach or clinician). Its changes are
built in: lighter weeks, the short session, a warm-up and progression rule,
low-impact HIIT the day after A, core cut to 2 sets, and a leg curl on day A for
hamstrings (in place of the back extension, which needs equipment not available).

## What it does

**The week is the unit.** It runs Sunday to Saturday. The page opens on this
week with today's card already open. The 12-week strip, the training rules, the
exercise library and the backup buttons are folded underneath.

**Weekly targets.** Strength 3, HIIT 2, mobility 1, and days at 6,000 steps out
of 7. Each turns green when met. Session targets follow whatever the week is set
to, so a rest day lowers the target rather than leaving you short.

**Confirming a session** is the tick box on the right of each day. HIIT days
have no exercises, only the tick, because the session itself is in NTC.

**Steps** are typed into the box on each day. A day counts once it reaches
6,000.

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

**Form videos.** Every exercise shows a thumbnail of a specific YouTube video on
the right. Tap it and the video opens.

How they were chosen: each was scored on view count, whether the channel is an
established strength, rehab or equipment source, whether the title is actually
about that movement, and whether the length suits a form check. 91 of the first 125 are
from recognised channels (Jeff Nippard, ATHLEAN-X, Squat University, E3 Rehab,
Bodybuilding.com, Rogue, Concept2, Physiotutors and similar), 114 have over
100,000 views and 70 over a million. Twelve were corrected by hand — five where
the popular result was the wrong movement or a duplicate, seven where it was an
eight-to-twelve minute lecture when a one-minute demo was what the moment called
for.

Length: the median is two minutes, 47% are under two and 70% under five. The
dozen that run over ten minutes are the ones where length is the point — the HIIT
circuits, the Tabata session, the mobility routine, the foam-rolling routine.
Those are sessions to follow, not form checks.

Two caveats, both worth knowing. **Nobody watched them** — they were judged on
title, channel, length and audience, not on content. And a handful of niche
exercises (Thomas hip flexor eccentrics, cable sissy squat, staggered stance
deadlift) simply have no popular video, so those picks are exact but
little-watched; exactness seemed more useful than popularity there.

Every thumbnail was fetched to confirm the video exists. If one turns out to be
unhelpful, replace the `v:"..."` for that exercise in `index.html`.

**The interval timer.** HIIT sessions have an *Open the timer* button. It runs a
five-minute warm-up, then the rounds from the prescription (8 × 30s/90s in the
12-week plan, 8 × 30s/60s in the old bodyweight circuit), then a five-minute
cool-down. It beeps and vibrates on every change and for the last three seconds
of each phase, and it keeps the screen awake. Three routines: Rotate 4, Variety 8
and Sprints. It works from a clock deadline rather than counting ticks, so it
stays accurate even if the phone sleeps through a round.

---

## The exercise library

133 exercises in three parts:

| Part | Grouped by | Count |
|---|---|---|
| Strength | Muscle group — glutes, hamstrings, quads, calves, back, chest, shoulders, biceps, triceps, core | 83 |
| HIIT and conditioning | Type — interval formats, full-body explosive, lower body power, upper body and core under fatigue, machines and sprints | 46 |
| Mobility and recovery | — | 4 |

Each exercise carries a tag saying where it came from:

- **Plan** — in the current 12-week plan
- **Previous** — from the earlier version of this app, kept so nothing is lost
- **Added** — in neither plan: a suggestion, or picked up from another sheet

Search the library by name or by muscle group. Every entry has a video thumbnail.

---

## One thing that leaves this page

Thumbnails are loaded from `i.ytimg.com`, so YouTube sees a request from your
phone each time the app draws. Nothing about your logs goes with it. If you would
rather it did not, the thumbnails can be dropped for plain text links.

## Where your data lives

**In your phone's browser, not on GitHub.** GitHub Pages only serves fixed
files; it has no database. Everything you type is stored locally under the key
`r2-65:block-v3`. The previous block (13 Sep – 5 Dec 2026) stays untouched under
`r2-65:block-v2`; the new block reads only its last weight per exercise, so
"Last time" carries over, marked *(last block)*. A backup from the previous
block cannot be imported into this one.

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

**To change which session lands on which day by default**, edit `defaultWeek()`.
Sunday first; `p` is the phase number:

```js
return ["rest", "s-a" + p, "ntc-low", "s-b" + p, "mobility-yoga", "s-c" + p, "ntc"];
```

**To change the strength sessions**, edit `STRENGTH` (the exercises and fixed
doses), `PHASES` (sets and reps per phase), `CORE` (the core pair per phase) and
`DELOAD_WEEKS`. The nine phase sessions are built from these.

**To change a session's exercises or sets and reps**, edit that session in
`SESSIONS`. Each line points at a library `id` and gives a dose:

```js
{ex:"hip-thrust", d:"4 × 8–10"}
```

**To add an exercise to the library**, add it to the right muscle group in
`LIBRARY`. Give it an `id` that is not already taken, a name, a YouTube search
string, and `v:` set to a video id — the eleven characters after `watch?v=` in a
YouTube URL. Without `v:` the app falls back to a search link with no thumbnail.

**To change the timer** for an interval session, edit its `timer:` block:

```js
timer:{work:30, rest:90, rounds:8, warmup:300, cooldown:300}   // seconds
```

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
