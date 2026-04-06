# Life Timeline — Visualize Your Life

A clean, minimalist visualization of your life from birth to expected lifespan, highlighting milestones and showing **“You are here.”**  
Designed to be personal, emotional, and shareable.

---

## Highlights

- ⚡ Instant visualization of your life progress  
- 🧠 Shows milestones and “You are here” marker  
- 🌙 Minimalist design, mobile responsive  
- 📸 Screenshot-ready / shareable output  

---

## What it does

Life Timeline takes your birth year, expected lifespan, and key milestones, then generates a visual timeline showing:

- How many years you’ve lived  
- How many remain (based on your lifespan)  
- Major milestones marked along the timeline  

This makes the abstract concept of life tangible, and encourages reflection.

---

## Current Features (v1.0)

| Feature | Status |
|--------|--------|
| Horizontal timeline / dot grid | building |
| “You are here” marker | building |
| Milestone markers | building |
| Animated reveal of timeline | building |
| Mobile responsive design | building |

---

## Planned Enhancements (v1.1+)

| Feature | Status |
|--------|--------|
| Toggle years / weeks view | planned |
| Hover for milestone details | planned |
| Dark mode toggle | planned |
| Shareable image / GIF export | planned |
| Optional backend to save timelines | planned |

---

## Tech Stack

- **HTML5** — structure  
- **CSS3** — layout, styling, animations  
- **JavaScript ES6+** — state + rendering  
- Optional: **localStorage** to persist inputs  

No frameworks. No build tools. Open `index.html` and go.

---

## Project Structure

```text
LifeTimeline/
├── index.html        landing + app page
├── style.css         timeline styles, responsive, animation
├── script.js         timeline rendering logic
└── assets/
    └── milestone-icons/ (optional)
```

---

## Data Model

```js
{
  birthYear: 2005,
  lifespan: 90,
  milestones: [
    { label: "School", year: 2010 },
    { label: "College", year: 2023 },
    { label: "First Job", year: 2025 }
  ]
}
```

---

## Rendering Flow

```text
user input → calculate age → generate timeline array → render dots/bars → highlight current → add milestones
```

Single source of truth. Every UI update re-renders from the input state.

---

## Run Locally

```bash
git clone <repo-url>
cd LifeTimeline

# Mac
open index.html

# Windows
start index.html
```

No setup required.

---

## What I Learned Building This

- State-driven rendering without a framework  
- Dynamic timeline calculation  
- Minimalist and emotional UI design  
- Making personal data visual and shareable  

---

## Roadmap (Post v1.0)

- Weeks granularity view  
- Animated milestone reveals  
- Dark mode toggle  
- Shareable GIF / image output  
- Optional backend to save multiple timelines  

---

Part of an ongoing frontend learning journey. Built for **shareable, emotional, and minimalist experiences**.
