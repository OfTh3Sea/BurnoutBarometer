<img width="4640" height="2640" alt="burnout_barometer_poster" src="https://github.com/user-attachments/assets/340f4d02-24c4-4778-b9aa-418ac189eda5" />
# 🌡️ Burnout Barometer
### Multi-Age Burnout Self-Assessment Tool

> A visually dynamic, age-specific burnout check-in tool that measures how close to the edge you are — and gives you something to do about it. Covers four life stages from ages 10 through adulthood, with interactive results, personalized tips, and built-in recovery activities.

---

## 📖 Overview

**Burnout Barometer** is a browser-based self-assessment tool that helps people across four age groups identify burnout before it becomes a crisis. Unlike a static quiz, the experience responds in real time — as you move the sliders, the thermometer fills, the interface shifts color from calm blue to urgent red, and personalized results appear immediately.

The tool goes beyond just identifying burnout. Each age group gets a tailored interactive recovery activity after their results: a **free-draw mood canvas** for younger users, a **Trash It stress-release board** for teens, and a **goal corkboard** for all ages to pin small, actionable intentions for the week.

Designed for **individuals, schools, counselors, therapists, workplaces, and anyone who suspects they might be closer to empty than they admit.**

---

## 👥 Who This Is For

**Tweens and their caregivers** — a gentle, age-appropriate way to check in on how much pressure a 10–12 year old is carrying from school, activities, and social life.

**Teenagers and school counselors** — a tool teens will actually want to use, with honest language about academic pressure, identity, social media comparison, and sleep deprivation.

**Young adults ages 18–25** — addresses the unique burnout signature of early adulthood: financial stress, career uncertainty, social comparison, and the pressure to have it all figured out.

**Adults 26+** — speaks directly to the chronic overload of career, caregiving, relationships, and the slow erosion of personal identity that characterizes adult burnout.

**Therapists and counselors** looking for a session warm-up or between-session check-in tool that gives clients language for their experience.

**Employers, HR teams, and wellness coordinators** who want a non-clinical, accessible resource for their teams.

**Parents** who want to use the tool alongside their child to normalize conversations about stress and burnout from an early age.

---

## ✨ Features

### 🌡️ Live Thermometer
- A visual thermometer fills in real time as sliders are adjusted
- Displays a burnout percentage and a status label (Feeling Good → Critical Zone)
- Gives an immediate, intuitive read on where you are

### 🎨 Dynamic Color System
- The entire interface shifts color as burnout increases — from calm teal blue at low levels through warm yellow, orange, and deep red at critical levels
- Background gradients, button colors, borders, and text all transition smoothly
- The visual environment mirrors the emotional reality being measured

### 📊 Four Age Groups with Tailored Questions

| Age Group | Focus Areas |
|-----------|------------|
| **Ages 10–12** | Homework load, activities, people-pleasing, lack of downtime |
| **Ages 13–17** | Academic pressure, social media comparison, identity, sleep deprivation |
| **Ages 18–25** | Financial stress, career uncertainty, social comparison, loss of purpose |
| **Ages 26+** | Work demands, caregiving, relationship strain, loss of personal identity |

Each group has 7 questions written specifically for that life stage — not generic burnout questions applied across the board.

### 📋 Instant Personalized Results
- Four result tiers per age group: doing well → some pressure → running on fumes → full burnout
- Each tier has a specific headline and message written for that age group's reality
- Four actionable tip cards with concrete suggestions — not vague wellness advice

### 🎨 Mood Canvas — Ages 10–12
- Free finger or stylus drawing on a full canvas
- 12 colors, 3 brush sizes, emoji stamps (😤 😭 😴 😊 ⭐ 💥 🌈 ❤️)
- "No rules. No wrong answers. Just draw it out."
- For younger users who process emotion better through art than words

### 🗑️ Trash It Board — Ages 13–17
- Type a worry, stressor, or thought you want to release
- It appears in the trash bin as a crumpled paper note with a random rotation
- Tap any note to shred it with an animation
- A concrete, physical-feeling release mechanic designed for the teen brain

### 📌 Goal Corkboard — All Ages
- Pin up to 3 intentions for the week
- Goals appear as sticky notes on a corkboard, color-coded by age group
- Small, achievable framing: "I will..." — not overwhelming goals
- Removes individual notes with an X; board resets between sessions

### 👀 Age Group Comparison
- A collapsible drawer shows the top stressors for every age group side by side
- Useful for parents, counselors, and educators who want to understand the full picture
- Opens context for conversations across generations

---

## 🚀 Getting Started

### Requirements
- Any modern browser (Chrome, Safari, Firefox, Edge)
- Works on phone, tablet, or desktop
- No installation, server, or accounts required

### Installation

```bash
git clone https://github.com/OfTh3Sea/burnout-barometer.git
cd burnout-barometer
open burnout-barometer.html
```

Or download `burnout-barometer.html` and open it directly in any browser.

---

## 📱 Recommended Contexts

| Context | Notes |
|---------|-------|
| **School counseling session opener** | Student completes before session; counselor uses results as starting point |
| **Homeroom or advisory period** | Students self-assess; teacher notes who might need check-in |
| **Therapy session warm-up** | Client arrives with a number and specific stressors already named |
| **Workplace wellness program** | Team members self-assess privately; HR uses tool as a conversation opener |
| **Family check-in** | Parent and child complete their respective age groups and compare stressors |
| **Personal daily or weekly practice** | Track burnout level over time as a self-awareness habit |

---

## 🗂️ File Structure

```
burnout-barometer.html    ← Complete application (single file, no dependencies)
README.md                 ← This file
```

---

## 💾 Privacy

- No data is stored — the Burnout Barometer uses no `localStorage`, cookies, or backend
- Each session is completely fresh; nothing persists between visits
- No accounts, logins, or tracking of any kind
- Results are entirely private to the person completing the assessment

---

## ⚠️ Disclaimer

**The Burnout Barometer is a self-reflection and awareness tool — not a clinical diagnostic instrument.** It is not a substitute for professional mental health assessment, therapy, or medical advice.

If results indicate critical burnout, the tool encourages users to speak with a therapist, counselor, or doctor. For teens in serious distress, a crisis line reference is included in the results messaging.

---

## ♿ Accessibility

- All sliders are keyboard accessible
- Color is never the sole differentiator — all results include text labels and written messages
- Large touch targets for mobile and tablet use
- No time-limited interactions anywhere in the flow
- Drawing canvas supports both mouse and touch input

---

## 🧩 Part of the OfTh3Sea Emotional Wellness Suite

| Tool | Ages | Description |
|------|------|-------------|
| **Feelings Friends** | 1–5 | Illustrated faces, color picker, sticker canvas, caregiver dashboard |
| **Feelings Explorer** | 5–10 | Flip cards with definitions, intensity sliders, drawing canvas |
| **Teen Check-in** | 11–17 | Body map, triggers, journal, counselor view, student privacy controls |
| **Emotion Wheel** | Adults | Plutchik wheel, mood journal, guided discovery |
| **Burnout Barometer** *(this tool)* | 10+ | Age-specific burnout assessment, live thermometer, recovery activities |

---

## 📄 License

MIT License — free to use, modify, and distribute with attribution.

---

*Created By OfTh3Sea.*
