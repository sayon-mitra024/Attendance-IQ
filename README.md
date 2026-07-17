<div align="center">


# ATTENDANCE IQ

### Predictive Attendance Engine for Students

A premium, offline-first attendance intelligence system with calendar-based tracking, subject-wise analytics, and mathematically-driven recovery predictions.

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Responsive](https://img.shields.io/badge/Responsive-Design-9645c9?style=for-the-badge)](#)
[![Offline](https://img.shields.io/badge/Offline-First-2ecc71?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-6A1B9A?style=for-the-badge)](LICENSE)

[![Stars](https://img.shields.io/github/stars/sayon-mitra024/Attendance-IQ?style=for-the-badge&color=FFD700)](https://github.com/sayon-mitra024/Attendance-IQ/stargazers)
[![Forks](https://img.shields.io/github/forks/sayon-mitra024/Attendance-IQ?style=for-the-badge&color=9645c9)](https://github.com/sayon-mitra024/Attendance-IQ/network/members)
[![Issues](https://img.shields.io/github/issues/sayon-mitra024/Attendance-IQ?style=for-the-badge&color=e74c3c)](https://github.com/sayon-mitra024/Attendance-IQ/issues)

<br/>

[Live Preview](#live-preview) &nbsp;·&nbsp; [Report Bug](https://github.com/sayon-mitra024/Attendance-IQ/issues) &nbsp;·&nbsp; [Request Feature](https://github.com/sayon-mitra024/Attendance-IQ/issues)

</div>

<br/>

---

## Table of Contents

- [About the Project](#about-the-project)
- [Live Preview](#live-preview)
- [Screenshots](#screenshots)
- [Features](#features)
- [Key Highlights](#key-highlights)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Mathematical Attendance Formula](#mathematical-attendance-formula)
- [Recovery Prediction Algorithm](#recovery-prediction-algorithm)
- [Safe Absence Prediction](#safe-absence-prediction)
- [Calendar Attendance Logic](#calendar-attendance-logic)
- [Dashboard Features](#dashboard-features)
- [Analytics](#analytics)
- [Local Storage and Data Privacy](#local-storage-and-data-privacy)
- [Installation](#installation)
- [Running Locally](#running-locally)
- [Folder Structure](#folder-structure)
- [Customization](#customization)
- [Future Improvements](#future-improvements)
- [Known Limitations](#known-limitations)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About the Project

**Attendance IQ** is a fully client-side, single-file web application that helps students track lecture-by-lecture attendance against a configurable semester timetable and predicts exactly what is required to hit a target attendance percentage — down to the specific date the threshold will be crossed.

Unlike a basic attendance percentage calculator, Attendance IQ runs a genuine **recovery simulation** against the actual remaining lectures in the semester, per subject, using the live weekly timetable — so every prediction reflects reality rather than a generic average.

**The problem it solves.** Most students only discover they have fallen below the attendance cutoff when it is too late to correct it. Attendance IQ converts raw daily marks into a forward-looking plan — for example, attending the next four lectures of a subject to reach 75 percent by a specific date — rather than a static, backward-looking percentage.

**Why it was built.** As a working system for tracking attendance against a real weekly timetable spanning Database Management Systems, Data Structures, Python Programming, Computer Organization and Architecture, Discrete Mathematics, Environmental Studies, and Soft Skills, with zero backend dependency and zero data leaving the browser.

**Target users.** College and university students required to maintain a minimum attendance percentage, most commonly seventy-five percent, who want a proactive and visual way to plan around it.

**Key benefits.**
- Per-subject and overall recovery dates calculated from the actual upcoming timetable
- A unified dashboard, calendar, and analytics workspace
- A fully editable timetable and semester configuration
- One-click JSON backup and restore
- Complete data privacy — nothing is transmitted anywhere

**Real-world use case.** A student opens the application once a day after class, marks each lecture as Present, Absent, Leave, or Cancelled from the Calendar view, and checks the Dashboard to see which subjects are at risk and what the fastest path back to the safe zone looks like.

---

## Live Preview

```
https://sayon-mitra024.github.io/Attendance-IQ/
```

---

## Screenshots

<table>
<tr>
<td align="center" width="33%"><strong>Dashboard</strong></td>
<td align="center" width="33%"><strong>Calendar</strong></td>
<td align="center" width="33%"><strong>Analytics</strong></td>
</tr>
<tr>
<td><img src="assets/screenshots/dashboard.png" alt="Attendance IQ Dashboard view showing overall percentage, mini-stats, and subject cards" width="100%"/></td>
<td><img src="assets/screenshots/calendar.png" alt="Attendance IQ Calendar view showing monthly lecture chips" width="100%"/></td>
<td><img src="assets/screenshots/analytics.png" alt="Attendance IQ Analytics view showing distribution, weekly, monthly, and trend charts" width="100%"/></td>
</tr>
</table>

**Dashboard** — a live overview with an animated progress ring, present and absent counters, a recovery-date indicator, and color-coded subject cards showing individual attendance percentages and target status.

**Calendar** — a full month grid where every date's lectures are derived from the weekly timetable, with color-coded chips summarizing each day's marked attendance at a glance.

**Analytics** — a complete Chart.js suite covering attendance distribution, weekly and monthly trends, and a cumulative attendance curve across the semester.

---

## Features

- **Guided Semester Setup** — a one-time wizard to configure semester start and end dates and the minimum required attendance percentage
- **Live Dashboard** — an animated circular progress ring, present, absent, and conducted counters, and an overall recovery date
- **Per-Subject Cards** — status badges, attendance percentage, a mini progress bar, and a plain-language recovery line for every subject
- **Interactive Calendar** — click any date to mark individual lectures or the entire day at once
- **Recovery Prediction Engine** — calculates the minimum number of future lectures required and the exact calendar date the target will be reached
- **Safe Absence Counter** — reports how many additional classes can be missed without dropping below target
- **What-If Simulator** — instantly models the effect of missing the next class, or attending the next several classes
- **Full Analytics Suite** — a distribution chart, subject-wise bar chart, weekly and monthly percentage charts, a cumulative trend line, and a marked-days heatmap
- **Editable Weekly Timetable** — add, edit, or remove lecture slots directly from Settings
- **Export and Import Backup** — download the full attendance state as JSON, or restore it on another device
- **One-Click Reset** — clear all stored data with a confirmation prompt
- **Dark and Light Theme** — a toggle that persists across sessions
- **Fully Responsive** — adapts from desktop to mobile using CSS Grid breakpoints
- **Offline-Capable** — runs without an internet connection once loaded, aside from the Chart.js CDN reference

---

## Key Highlights

- Zero backend and zero build step — a single `index.html` file runs the entire application
- Genuine recovery mathematics rather than a rough estimate — the algorithm walks the actual future timetable, subject by subject
- Privacy by design — all data remains in the browser's `localStorage`, never transmitted anywhere
- Portable data — JSON export and import mean attendance history is never locked to a single device

---

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure and single-page application shell |
| CSS3 — Custom Properties, Grid, Flexbox, backdrop-filter | Royal purple and gold glassmorphism theme, dark and light modes, responsive layout |
| Vanilla JavaScript, ES6+, IIFE module pattern | Application state, mathematics, rendering, and event handling |
| [Chart.js 4.4.0](https://www.chartjs.org/) via CDN | Doughnut, bar, and line charts within the Analytics view |
| Web `localStorage` API | Client-side persistence of semester configuration, timetable, and attendance records |
| Blob and File APIs | JSON export and import of the full application state |

No frameworks, bundlers, or package managers are used — the application is intentionally dependency-light.

---

## How It Works

1. **Setup** — On first run, a semester start date, end date, and minimum attendance percentage are configured. A default weekly timetable of twenty-six lecture slots across seven subjects is preloaded and remains editable at any time.
2. **Mark Attendance** — In the Calendar view, any date within the semester can be opened to mark each scheduled lecture, or the entire day at once.
3. **Track** — The Dashboard recalculates in real time: overall percentage, per-subject percentage, status badges, and recovery predictions.
4. **Analyze** — The Analytics view visualizes distribution, trends, and weekly and monthly performance.
5. **Back Up** — Data can be exported as JSON at any time and imported back on any device.

---

## Mathematical Attendance Formula

For any subject, or overall, attendance percentage is calculated only from lectures that actually took place. Leave and Cancelled marks are excluded from the denominator.

```
Conducted   = Present + Absent
Attendance% = (Present / Conducted) x 100
```

If no lectures have been conducted yet for a subject, the display defaults to one hundred percent with a "no data yet" state rather than dividing by zero.

**Status thresholds**

| Range | Status |
|---|---|
| 85% and above | Excellent |
| 75% to 84.9% | Good |
| 70% to 74.9% | Warning |
| Below 70% | Critical |

---

## Recovery Prediction Algorithm

Given a subject's current present and conducted counts and a target percentage, Attendance IQ solves for the minimum number of consecutive future lectures, k, that must be attended to reach the target.

```
k = ceil( (target x conducted - present) / (1 - target) )
```

The algorithm then walks the subject's actual remaining timetable for the rest of the configured semester — respecting real weekdays and lecture slots rather than a generic estimate — to find the calendar date on which the k-th such lecture occurs. If there are not enough future lectures remaining in the semester to mathematically reach the target, the subject is flagged as not recoverable within the current semester.

The same logic powers:

- **Per-subject recovery**, shown as a highlighted line on each subject card
- **Overall recovery**, simulated by assuming every remaining lecture across all subjects is attended
- **What-If: Miss Next Lecture**, which recomputes the recovery plan assuming the next class is an absence
- **What-If: Attend Next N Lectures**, which recomputes the new percentage and recovery plan after a hypothetical attendance streak

---

## Safe Absence Prediction

For any subject with at least one conducted lecture, Attendance IQ calculates how many additional lectures could be missed while remaining at or above the target percentage.

```
Max Conducted Allowed   = floor(Present / Target%)
Safe Absences Remaining = Max Conducted Allowed - Current Conducted
```

This provides a real-time buffer figure rather than requiring the student to calculate it manually before deciding whether to skip a class.

---

## Calendar Attendance Logic

- The calendar renders a full month grid, with dates outside the configured semester range visually disabled.
- Each date's lectures are derived live from the weekly timetable, matched against that date's day of week, so there is no need to duplicate entries for every week of the semester.
- Selecting a date opens a panel listing every scheduled lecture for that day, each with independent status controls: Present, Absent, Leave, and Cancelled.
- A "Mark Entire Day" shortcut applies a single status to every lecture scheduled that day in one action.
- Marked lectures appear as color-coded chips directly on the calendar grid for immediate review.

---

## Dashboard Features

- An animated circular progress ring displaying the live overall attendance percentage
- Mini-stat cards for Present, Absent, Conducted, and the next Overall Recovery Date
- A status indicator reading On Track, Below Target, or No Data Yet
- A per-subject grid with color-coded status strips, attendance percentage, mini progress bars, and a plain-language recovery prediction for each subject

---

## Analytics

The Analytics view, powered by Chart.js, includes the following visualizations.

- **Distribution Chart** — Present, Absent, Leave, and Cancelled proportions across the semester
- **Subject-Wise Bar Chart** — attendance percentage per subject, color-matched to subject cards
- **Weekly Attendance Bar Chart** — percentage bucketed by semester week number
- **Monthly Attendance Bar Chart** — percentage bucketed by calendar month
- **Cumulative Trend Line Chart** — running attendance percentage over time
- **Marked-Days Heatmap** — a color-graded grid, capped at one hundred forty days for rendering performance, showing daily present-to-absent ratio at a glance

---

## Local Storage and Data Privacy

Attendance IQ stores all application state — semester configuration, the weekly timetable, and every attendance mark — in a single `localStorage` key, `attendanceIQ_state_v1`, within the user's browser.

- No backend server
- No account or authentication
- No analytics or third-party tracking
- No data ever leaves the browser
- Fully portable through JSON export and import
- Fully erasable through the Reset All Data action, which requires confirmation

---

## Installation

Attendance IQ has no dependencies to install and no build step.

**Option 1 — Open Directly**

Download or clone the repository and open `index.html` in any modern browser.

**Option 2 — Clone via Git**

```bash
git clone https://github.com/sayon-mitra024/Attendance-IQ.git
cd Attendance-IQ
```

Then open `index.html` in a browser.

---

## Running Locally

As a static single-page application, any local static server is sufficient.

```bash
# Python 3
python -m http.server 8000

# Node.js (http-server)
npx http-server .
```

Then visit `http://localhost:8000` in a browser.

**Note.** Chart.js is loaded from a CDN (`cdnjs.cloudflare.com`). An internet connection is required on first load to fetch this script; the application otherwise runs entirely offline.

---

## Folder Structure

```text
Attendance-IQ/
|
|-- index.html              Entire application: markup, styles, and logic
|-- README.md                Project documentation
|-- CHANGELOG.md              Version history
|-- CONTRIBUTING.md            Contribution guidelines
|-- CODE_OF_CONDUCT.md          Community standards
|-- SECURITY.md                  Security policy
|-- LICENSE                       MIT License
|-- .gitignore                     Ignored files and folders
|-- assets/
|   |-- screenshots/                Dashboard, Calendar, and Analytics previews
|   `-- logo/                        Project logo and branding assets
`-- docs/                              Additional documentation
```

---

## Customization

- **Timetable** — edit the `DEFAULT_TIMETABLE` array at the top of the script in `index.html`, or use the in-app Settings, Weekly Timetable editor after first load.
- **Theme colors** — all colors are defined as CSS custom properties under `:root`, with overrides under `body.light`. Update the purple, gold, and status color variables to re-theme the application.
- **Status thresholds** — adjust the percentage breakpoints inside `statusColorForPct()`.
- **Minimum attendance target** — configurable per user at setup time and editable at any time in Settings, with no code changes required.

---

## Future Improvements

- Local notification reminders for at-risk subjects
- Progressive Web App support with a service worker for true offline installation
- Multi-semester history and archiving
- Holiday and exception-date support within the timetable engine
- Shareable and printable attendance reports in PDF format
- Optional, opt-in cloud sync across devices

---

## Known Limitations

- Data is stored per browser through `localStorage`. Clearing browser data or switching browsers or devices without exporting first will result in the loss of attendance history.
- The timetable engine assumes a fixed, recurring weekly schedule and does not currently account for holidays or one-off schedule changes without a manual Cancelled mark.
- The heatmap view is capped at one hundred forty days for rendering performance on longer semesters.
- Chart.js is loaded from a CDN, so the first page load requires an internet connection.

---

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidance on forking, branching, commit conventions, and opening a pull request.

---

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

## Contact

**Sayon Mitra**

Email: [sayonmitracode@gmail.com](mailto:sayonmitracode@gmail.com)
Email: [sayon@sayonedu.in](mailto:sayon@sayonedu.in)

Project Link: [https://github.com/sayon-mitra024/Attendance-IQ](https://github.com/sayon-mitra024/Attendance-IQ)

<br/>

<div align="center">

Developed by **Sayon Mitra**

[sayonmitracode@gmail.com](mailto:sayonmitracode@gmail.com) &nbsp;·&nbsp; [sayon@sayonedu.in](mailto:sayon@sayonedu.in)

</div>
