# Asset & Data Brief — Peter M portfolio

Work through this in tiers. Tier 1 alone gets a publishable site live.
Send things in batches — I'll build each case study as its assets arrive.

---

## Tier 1 — Site goes live (do this first)

**Details**
- [ ] Full name as you want it displayed (currently "Peter M.")
- [x] Email — petermould2002@hotmail.com
- [x] LinkedIn / GitHub — petermould
- [ ] CV as PDF → `assets/cv.pdf`
- [ ] Domain name, if you're buying one
- [ ] Headshot, optional but recommended → `assets/peter.jpg`, 800×800 min

**Four hero images** — one per project. 16:9 unless noted, at least 1600px wide.
PNG for anything with text or UI, JPG for video frames.

| File | What it should show |
|---|---|
| `assets/wc-dashboard.png` | Predictor dashboard, full width, mid-tournament state |
| `assets/football-frame.jpg` | Annotated match frame — boxes, team colours, possession bar |
| `assets/tennis-minicourt.jpg` | Mini-court overlay + broadcast stats panel |
| `assets/scouting-chart.png` | Your single best scouting chart — **4:3**, not 16:9 |

**Repos** — confirmed: `world_cup_model_2026`, `tennis_vision`, `football_analysis`. Still needed: a repo for the scouting database, and the live predictor dashboard URL.

---

## Tier 2 — Real numbers replace placeholders

Every case study currently has blanks marked `—`. These fill them.

### World Cup 2026 Predictor
- [ ] Predictions file: pre-tournament probability per team per stage
- [ ] Per-matchday snapshots if you saved them (for the probability-over-time chart)
- [ ] Final actual results
- [ ] Model parameters: which fixtures fed the ratings, recency weighting / half-life, any home-advantage term
- [ ] Anything you remember it calling well or badly

→ From the predictions + results I can compute hit rate, Brier score, log loss, and generate the calibration plot and probability-over-time chart in the site's palette.

### football_analysis
- [ ] Per-player output CSV: speed, distance, possession share
- [ ] Detection model + weights used, and mAP if you logged it
- [ ] Input video source, resolution, FPS
- [ ] Processing time per minute of footage
- [ ] One thing that broke and how you fixed it

### tennis-vision
- [ ] Ball detector mAP; court keypoint error if measured
- [ ] Sample stats output — shot speeds, distance covered
- [ ] Same runtime + video spec details
- [ ] One thing that broke and how you fixed it

### Second-Tier Scouting Database
- [ ] Exact player and GK counts, per league
- [ ] Season(s) covered, and data sources per league
- [ ] Full metric list, and the six position group definitions
- [ ] The dataset itself (or a 200-row sample) so I can regenerate charts on-brand
- [ ] **One worked example**: a player the tool surfaced who you'd actually recommend, and why. This is the strongest single thing you can give me for that page.

### Live Board to PGN — parked, listed under "Also building" for now
- [ ] Colab training output: `results.png`, confusion matrix, mAP50, mAP50-95
- [ ] Dataset size, class list, train/val split
- [ ] Current accuracy at board level — how often the full position is read correctly
- [ ] Known failure modes, honestly listed

---

## Tier 3 — Depth

- [ ] 10–15s clips: `football-clip.mp4`, `tennis-clip.mp4`, `chess-clip.mp4` (H.264, ≤5MB each). Side-by-side raw/annotated is ideal.
- [ ] 2–3 extra stills per CV project showing intermediate stages
- [ ] Architecture diagram sketches — rough is fine, I'll redraw them
- [ ] Photo of the goal-line setup or your matchday workstation, if you're permitted to share one

---

## Notes

- Anything under NDA from the GLT work, leave out. Describe the role generically instead.
- Screenshots: hide personal info, close browser tabs, use a clean window.
- Don't resize or compress before sending — send the largest version you have.
