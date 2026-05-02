# 65 Fitness Studio — Workout App

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

You've created a dedicated repo at `github.com/sabrivettori-lab/65FitnessStudio`. To turn it into a live website:

### Step 1 — Upload the files

1. Go to https://github.com/sabrivettori-lab/65FitnessStudio
2. Click **Add file → Upload files**
3. Drag in all 6 HTML files (`index.html`, `sunday.html`, `wednesday.html`, `friday.html`, `saturday.html`, `hiit.html`)
4. Add a commit message like "Initial upload"
5. Click **Commit changes**

### Step 2 — Turn on GitHub Pages

1. In the repo, click **Settings** (top right)
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Branch: `main` · Folder: `/ (root)` · click **Save**
5. Wait 1–2 minutes for the green checkmark

### Step 3 — Visit & install

1. Your live URL will be: **`https://sabrivettori-lab.github.io/65FitnessStudio/`**
2. Open it on your phone in Safari
3. Tap the share icon (square with arrow up)
4. Scroll down → **Add to Home Screen**
5. Name it "65 Studio" or whatever feels right
6. The icon now sits on your home screen like a native app

### Future updates

To change a workout later: edit the file on github.com (or push from your laptop), wait a minute, and refresh on your phone. Your logged data is on your phone — file updates won't touch it.

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
