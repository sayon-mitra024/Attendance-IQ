# Changelog

All notable changes to **Attendance IQ** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned
- Holiday/exception-date support in the timetable engine
- PWA offline install support
- Multi-semester history

---

## [1.0.0] - 2026-07-18

### Added
- Guided first-run semester setup (start date, end date, minimum attendance %)
- Default weekly timetable pre-loaded with 26 lecture slots across 7 subjects (Mon–Fri)
- Dashboard with animated circular progress ring, present/absent/conducted counters, and overall recovery date
- Per-subject cards with status badges, attendance percentage, and recovery predictions
- Interactive calendar with per-lecture and whole-day attendance marking (Present / Absent / Leave / Cancelled)
- Recovery prediction engine calculating minimum future lectures needed and the exact recovery date
- Safe absence calculator showing how many classes can still be missed while staying on target
- What-if simulator for "miss next lecture" and "attend next N lectures" scenarios
- Full analytics suite via Chart.js: distribution doughnut, subject-wise bar chart, weekly bar chart, monthly bar chart, cumulative trend line chart, and marked-days heatmap
- Editable weekly timetable (add/edit/remove lecture slots) in Settings
- JSON export and import for full data backup/restore
- One-click reset with confirmation prompt
- Dark/light theme toggle with persisted preference
- Fully responsive layout for desktop and mobile
- 100% client-side persistence via `localStorage` — no backend required

### Notes
- Initial public release.
