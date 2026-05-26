# Gohan Protocol — 16-Week Lean Bulk App

A fully self-contained mobile web app built for a 65kg lean bulk targeting the Beast Gohan physique — wide shoulders, thick back, visible arms, shredded core. Designed to be installed on Android and used at the gym.

**Live app:** `https://kingsleypai.github.io/GohanProtocol` *(set up your own GitHub Pages repo)*

---

## Who This Is For

- Starting weight: **65kg**
- Goal: **Lean bulk** — controlled caloric surplus to build muscle while minimising fat gain
- Target physique: **Beast Gohan** — wide back, boulder shoulders, defined arms, athletic core
- Target end weight: **~72–74kg** at ~10% body fat
- Timeline: **16 weeks**

---

## How It Differs From Apex Physique (100kg Recomp)

| | Apex Physique | Gohan Protocol |
|--|--|--|
| Starting weight | 100kg | 65kg |
| Strategy | Recomposition (deficit) | Lean bulk (surplus) |
| Calories | ~2,800 training / 2,400 rest | ~2,900 training / 2,500 rest |
| Protein | 230g/day | 160g/day |
| Carbs | 270g/day | 370g/day |
| Phases | 3 (12 weeks) | 4 (16 weeks) |
| Scale direction | Down | Up (slowly) |
| Accent colour | Red `#c8102e` | Purple `#7c3aed` |

---

## 4-Phase Programme (16 Weeks)

| Phase | Weeks | Focus | Sets × Reps |
|-------|-------|-------|-------------|
| **Foundation** | 1–4 | Form + volume | 4×10–12 |
| **Hypertrophy** | 5–8 | Maximum muscle growth | 4–5×8–12 + drop sets |
| **Strength** | 9–12 | Heavy loads, raw power | 5×4–6 |
| **Definition** | 13–16 | Reveal Beast Gohan | Maintain + cardio |

**Deload weeks:** 4, 8, 12 (reduce weight 20%, cut sets, recover)

---

## Nutrition (65kg Lean Bulk)

| Macro | Training Day | Rest Day |
|-------|-------------|---------|
| Calories | ~2,900 kcal | ~2,500 kcal |
| Protein | 160g | 160g |
| Carbs | 370g | 270g |
| Fats | 80g | 80g |

**Key difference from a recomp:** Carbs are much higher. Rice, oats, bananas, and whole milk are your best friends at 65kg. The scale should go up ~0.25–0.5kg per week. If it's not moving, eat more.

---

## Files

| File | Purpose |
|------|---------|
| `gohan.html` | The entire app |
| `sw.js` | Service worker (shared with Apex app) |
| `gohan_manifest.json` | PWA manifest — purple theme |
| `icon-gohan-192.png` | App icon (192×192) purple |
| `icon-gohan-512.png` | App icon (512×512) purple |

---

## Installing on Android

1. Open the URL in Chrome
2. Wait for the **ADD TO HOME SCREEN** banner (purple) or tap three-dot menu → **Install app**
3. Opens full screen as a standalone app

**Note:** If you also have the Apex Physique app installed, these are completely separate — different localStorage keys (`ghn_` prefix), different manifest, different icons. They won't interfere with each other.

---

## Physique Targets (Beast Gohan)

| Benchmark | Week 4 | Week 8 | Week 16 |
|-----------|--------|--------|---------|
| Bodyweight | +2–3kg | +4–6kg | +7–9kg |
| Bench press | ~60kg | ~80kg | ~100kg |
| Barbell squat | ~80kg | ~100kg | ~120kg |
| Weighted pull-ups | BW | +5kg | +15kg |
| Body fat | ~15% | ~14% | ~10% |

---

*Built with Claude — Anthropic*
