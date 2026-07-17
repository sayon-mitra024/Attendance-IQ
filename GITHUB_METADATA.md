# GitHub Repository Metadata Reference

Copy-paste reference for fields that live in the GitHub UI rather than in a tracked file (repo description, topics, About section, social preview, release notes, etc.).

---

## 1. Repository Description (max 350 characters)

```
Offline, single-file smart attendance predictor for students. Track lecture-wise attendance on an interactive calendar, get subject-wise recovery date predictions, safe-absence limits, and full Chart.js analytics — all stored privately in your browser via localStorage. No backend, no sign-up.
```
*(268 characters)*

---

## 2. Repository Topics (20)

```
attendance
javascript
calendar
student
tracker
education
prediction
dashboard
analytics
html
css
offline-app
localstorage
attendance-calculator
college
semester
planner
progress
visualization
productivity
```

---

## 3. About Section

**Short tagline:**
```
🎓 Predict your attendance recovery date before it's too late.
```

**Website:** `https://sayon-mitra024.github.io/Attendance-IQ/` *(update once deployed)*

**Documentation:** `README.md` *(placeholder — link to a docs site if one is added later)*

---

## 4. GitHub Release Notes — v1.0.0

```markdown
## 🎉 Attendance IQ v1.0.0 — Initial Release

### ✨ New Features
- Guided semester setup wizard (dates + minimum attendance target)
- Default weekly timetable (26 lecture slots, 7 subjects, Mon–Fri) — fully editable
- Interactive calendar with per-lecture and whole-day attendance marking
- Dashboard with animated progress ring, live stats, and status badges
- JSON export/import for full data backup and restore
- One-click data reset with confirmation

### 🎨 UI Improvements
- Royal Purple / Gold glassmorphism theme with dark & light modes
- Fully responsive layout (desktop → mobile)
- Toast notifications for user actions
- Color-coded status badges (Excellent / Good / Warning / Critical)

### 🧮 Algorithms
- Recovery prediction engine: minimum future lectures + exact recovery date, per subject and overall
- Safe absence calculator: how many more classes can be missed while staying on target
- What-if simulator: "miss next lecture" and "attend next N lectures" projections

### ⚡ Performance
- Semester date enumeration is cached and invalidated only on config changes
- Heatmap rendering capped at 140 days for smooth performance on long semesters

### 🐛 Known Issues
- No holiday/exception-date support yet — cancelled classes must be marked manually
- Data is per-browser (localStorage); export before switching browsers/devices

### 🔮 Upcoming Features
- Holiday/exception-date support in the timetable engine
- PWA offline installability
- Multi-semester history and archiving
- PDF report export
```

---

## 5. SEO-Friendly Description

```
Attendance IQ is a free, offline-first attendance tracker and predictor for college students. Mark lecture-wise attendance on an interactive calendar, view subject-wise analytics, and get exact recovery dates showing how many classes you need to attend to hit your minimum attendance percentage — all running in your browser with no sign-up and no data leaving your device.
```

---

## 6. GitHub Social Preview

**Social preview title:**
```
Attendance IQ — Smart Attendance Predictor
```

**Social preview subtitle:**
```
Calendar-based tracking. Real recovery dates. 100% offline.
```

**Open Graph description:**
```
An offline, single-file web app that tracks lecture-wise attendance and predicts exactly when you'll hit your target percentage — with full analytics and zero data leaving your browser.
```

---

## 7. Portfolio Description (LinkedIn / personal site / GitHub profile)

```
Attendance IQ — a fully offline, single-file web app I built to solve a real problem college students face: not knowing whether they'll clear the minimum attendance cutoff until it's too late. It tracks lecture-level attendance against a live weekly timetable and runs a recovery simulation to tell students the exact date they'll hit their target — plus full Chart.js analytics, a safe-absence calculator, and JSON backup/restore. Built with vanilla HTML/CSS/JS, zero backend, 100% client-side data via localStorage.
```

---

## 8. Repository Tree

```text
Attendance-IQ/
│
├── index.html
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── LICENSE
├── .gitignore
├── assets/
│   ├── screenshots/
│   └── logo/
└── docs/
```

---

## 9. License Recommendation

**Recommended: MIT License** *(already included as `LICENSE`)*

**Why MIT:**
- Maximally permissive — encourages adoption, forking, and educational reuse, which fits a student-built, portfolio-facing project
- Minimal legal overhead for contributors
- Widely recognized and trusted by recruiters and the broader open-source community
- Compatible with nearly any downstream use, commercial or otherwise
