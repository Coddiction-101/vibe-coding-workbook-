# Milestone — Your Life, Visualized

A minimalist, emotional, and interactive life visualization tool that tracks your progress, moods, milestones, and personal reflections — with an optional AI companion to motivate and comfort you. 

---

## Preview

N/A

---

## Highlights

- ⚡ Instant life timeline visualization (years/months lived vs remaining)  
- 🧠 Milestones and “You are here” marker  
- 🌙 Daily mood tracker + reflection streaks  
- 💖 Record happiest moments and personal notes  
- 🤖 Optional AI companion for nightly reflection and motivation  
- 📸 Screenshot-ready / shareable insights  

---

## What it Does

LifeDots helps you:

- Visualize your life progress and milestones  
- Track daily mood and emotional trends  
- Maintain daily streaks and receive rewards for reflection  
- Record happiest past moments and personal notes  
- Reflect on your life and plan for future growth  
- Interact with a motivational AI companion (optional)  

---

## Current Features (v1.0 – v1.1)

| Feature | Status |
|--------|--------|
| Life timeline / dot grid | building |
| “You are here” marker | building |
| Milestones (school, college, jobs, custom) | building |
| Daily mood check | building |
| Daily streak tracker & rewards | building |
| Mobile responsive design | building |

---

## Planned Features (v1.2 – v1.3)

| Feature | Status |
|--------|--------|
| Happiest moments diary | planned |
| Personal notes | planned |
| AI companion / motivational life partner | planned |
| Activity-triggered AI interactions | planned |
| Screenshots / GIF export | planned |
| Weeks or days granularity view | planned |
| Life goals projection | planned |

---

## Tech Stack

- **HTML5** — structure  
- **CSS3** — layout, timeline, mood visualization, streaks  
- **JavaScript ES6+** — state-driven rendering, daily reflection logic  
- **localStorage / IndexedDB** — persistence  
- **Optional:** AI integration with OpenAI API  

No frameworks. No build tools. Open `index.html` and go.

---

## Project Structure

```text
LifeDots/
├── index.html          landing + app page
├── style.css           timeline, streaks, diary, AI companion
├── script.js           rendering logic, daily reflection, AI interactions
└── assets/
    ├── milestone-icons/
    ├── mood-icons/
    └── screenshots/    optional export
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
  ],
  moods: [
    { date: "2026-04-06", mood: "happy" },
    { date: "2026-04-07", mood: "neutral" }
  ],
  happiestMoments: [
    { date: "2024-08-15", note: "Beach vacation", imageUrl: "" }
  ],
  personalNotes: [
    { date: "2026-04-06", note: "Sat in the park, read a book" }
  ],
  dailyStreaks: {
    reflection: 7,
    habits: 5
  },
  aiCompanion: {
    active: false,
    lastInteraction: "2026-04-06",
    triggeredBy: null
  }
}
```

---

## Rendering Flow

```text
user input → update timeline → update moods/notes → check streaks → render visual dots/bars → AI triggers if activity completed → update UI
```

---

## Run Locally

```bash
git clone <repo-url>
cd LifeDots

# Mac
open index.html

# Windows
start index.html
```

No setup required.

---

## What You’ll Learn

- State-driven UI rendering without frameworks  
- Dynamic timeline and mood visualization  
- Habit and streak tracking with rewards  
- Emotional and reflective UX design  
- Integrating AI interactions for personal motivation  

---

## Roadmap

- Weeks / days granularity view  
- Animated milestone reveals  
- Dark mode toggle  
- Shareable GIF / image output  
- Optional backend to save multiple timelines  
- Advanced AI companion features (motivational chats, reflections, reminders)  

---

LifeDots is part of an ongoing journey to build **shareable, emotional, and motivational experiences**. It’s **your life, visualized and celebrated**.
