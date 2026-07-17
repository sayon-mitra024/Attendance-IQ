# Contributing to Attendance IQ

First off, thank you for considering contributing to **Attendance IQ**! This project is a single-file, dependency-light web app, which keeps the contribution bar low — no build tooling to set up, no package installs required.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Fork & Clone](#fork--clone)
- [Branch Naming](#branch-naming)
- [Commit Style](#commit-style)
- [Pull Requests](#pull-requests)
- [Reporting Issues](#reporting-issues)
- [Feature Requests](#feature-requests)

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold it.

## How to Contribute

1. Fork the repository
2. Clone your fork locally
3. Create a feature/fix branch
4. Make your changes to `index.html`
5. Test manually in the browser (open `index.html`, or serve it locally)
6. Commit with a clear message
7. Push your branch and open a Pull Request

## Fork & Clone

```bash
# Fork the repo on GitHub first, then:
git clone https://github.com/sayon-mitra024/Attendance-IQ.git
cd Attendance-IQ
git remote add upstream https://github.com/sayon-mitra024/Attendance-IQ.git
```

## Branch Naming

Use a short, descriptive prefix:

| Prefix | Use case |
|---|---|
| `feature/` | New functionality |
| `fix/` | Bug fixes |
| `docs/` | Documentation-only changes |
| `refactor/` | Code changes with no behavior change |
| `style/` | UI/CSS/visual changes |

Example: `feature/holiday-support`, `fix/calendar-month-boundary`

## Commit Style

Follow [Conventional Commits](https://www.conventionalcommits.org/) where possible:

```
feat: add holiday exclusion to timetable engine
fix: correct recovery date calculation off-by-one
docs: update README installation section
style: adjust dark mode contrast on subject cards
refactor: extract date helpers into a separate section
```

## Pull Requests

Before opening a PR:

- [ ] Test the app manually in at least one browser (Chrome/Firefox/Edge)
- [ ] Verify existing functionality (setup, calendar marking, dashboard, analytics, settings) still works
- [ ] Keep changes focused — one feature/fix per PR
- [ ] Update `README.md` and/or `CHANGELOG.md` if behavior or features change
- [ ] Write a clear PR description: what changed, why, and how it was tested

## Reporting Issues

When filing a bug report, please include:

- Steps to reproduce
- Expected vs. actual behavior
- Browser and OS
- Screenshots, if applicable

## Feature Requests

Feature requests are welcome! Please open an issue describing:

- The problem you're trying to solve
- Your proposed solution (if you have one)
- Any alternatives you've considered

---

Thanks again for helping improve Attendance IQ! 🎓
