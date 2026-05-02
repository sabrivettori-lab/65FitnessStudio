# Road to 65 — Workout App

Personal fitness tracker for the 6-week strength block. Self-contained HTML files with embedded CSS and JavaScript. Logs save locally on your phone via browser storage.

## What's in this folder

| File | What it does |
|---|---|
| `index.html` | Weekly overview — start here. 7 day cards, swap menu (⋯), weekly counter, backup buttons. |
| `sunday.html` | Back & Chest strength session |
| `wednesday.html` | Glutes & Hips strength session (primary glute day) |
| `friday.html` | Legs strength session (heavy back squat) |
| `saturday.html` | Shoulders & Arms (trimmed polish session) |
| `hiit.html` | HIIT bodyweight routine with built-in 25-min timer |

---

## How to deploy (15 min, one-time)

### Option 1 — GitHub Pages (recommended, syncs across devices)

1. Go to your `sabrivettori-lab.github.io` repo on github.com
2. Click **Add file → Create new file**
3. Name it `road-to-65/index.html` (the `/` creates the folder)
4. Open `index.html` from this zip on your laptop, copy ALL contents, paste into GitHub
5. Scroll down, click **Commit changes**
6. Repeat steps 2–5 for each of the other 5 files (saving them in the same `road-to-65/` folder)
7. Wait 1–2 minutes for GitHub to publish
8. Visit `https://sabrivettori-lab.github.io/road-to-65/` on your phone
9. **Add to Home Screen** in Safari (share icon → Add to Home Screen)

Your URL will be: `https://sabrivettori-lab.github.io/road-to-65/`

### Option 2 — iCloud Drive (simpler, single device only)

1. Drop the whole folder into iCloud Drive
2. On your phone, open Files app → iCloud Drive → road-to-65 → tap `index.html`
3. Opens in Safari. Tap share → Add to Home Screen.

⚠️ This option means data is locked to whichever device you use. The links between pages still work.

---

## How to use

### First time
1. Open `index.html` (the home screen icon)
2. Tap any day with a strength badge to see the workout
3. Log your weights and reps as you go — saves automatically
4. Tap **Mark complete** at the top when you finish
5. Return to home — see the day-pip turn green

### Daily flow
- Open the page for today's workout from the index
- Last week's weights show as faint placeholders ("last: 12.5") — try to beat them
- Tap **▶ Watch** under any exercise to see a YouTube tutorial
- Tap **View history** to see your past 6 sessions for that lift

### Swapping days
- On the index page, tap **⋯** in the top-right of any day card
- Choose **Move to another day**, **Add a strength workout here**, or **Skip this week**
- Changes apply only to the current week — resets every Sunday

### HIIT timer
1. Open `hiit.html`
2. Pick your routine: Rotate 4 / Tabata 8 / Sprints
3. Tap **Start** — timer auto-progresses through warmup, 8 rounds, cooldown
4. Beeps and vibrates between phases
5. Tap **Mark complete** when done

### Weekly backup
- Once a week, tap **Export** at the bottom of the index page
- Saves a `road-to-65-backup-YYYY-MM-DD.json` file
- AirDrop to yourself, save to iCloud, or email it
- If you ever switch phones, tap **Import** and pick the backup file

---

## Important notes

**Data is stored locally** in your phone's browser. If you clear Safari data, history is gone. Use the Export button weekly as a backup.

**No accounts, no cloud.** Just local files. Your data stays on your phone.

**To update the workout content** (change exercises, rep ranges, etc.) you'd need to edit the HTML files. Let me know what you want to change and I'll generate updated files.

---

## Quick reference — the program

**Mon–Sat schedule:**
- **Sunday**: Back & Chest strength
- **Monday**: HIIT 25 min
- **Tuesday**: Padel · HIIT · Rest (your choice)
- **Wednesday**: Glutes & Hips strength
- **Thursday**: HIIT 25 min
- **Friday**: Legs strength
- **Saturday**: Shoulders & Arms strength OR long run

**Targets:**
- Weight: 68 → 65 kg over ~8 weeks
- Daily intake: 1,450–1,600 kcal (350–400 kcal deficit)
- Protein: 130g/day non-negotiable
- Add weight any session you hit the top of the rep range with clean form

**Block C is always optional** — skip if recovery is poor or session running long.

---

Built with Anthropic's Claude. Personal use only.
