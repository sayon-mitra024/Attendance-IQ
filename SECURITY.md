# Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| 1.0.x | ✅ |
| < 1.0 | ❌ |

## Reporting a Vulnerability

Attendance IQ is a client-side, offline-first application with no backend server, no user accounts, and no data transmission — the primary attack surface is limited to the front-end code itself and its single third-party dependency (Chart.js, loaded via CDN).

If you discover a security vulnerability, please report it responsibly:

1. **Do not** open a public GitHub issue for security vulnerabilities.
2. Email **[sayonmitracode@gmail.com](mailto:sayonmitracode@gmail.com)** or **[sayon@sayonedu.in](mailto:sayon@sayonedu.in)** with:
   - A description of the vulnerability
   - Steps to reproduce
   - Potential impact
3. You can expect an initial response within **5 business days**.
4. Once confirmed, a fix will be prioritized and a new release published. You will be credited (unless you prefer to remain anonymous) once the fix ships.

## Scope

In scope:
- Cross-site scripting (XSS) via user-supplied timetable/subject input rendered into the DOM
- Insecure handling of imported JSON backup files
- Any vulnerability introduced by the Chart.js CDN dependency

Out of scope:
- Issues requiring physical/local access to a user's already-unlocked device (data is stored in browser `localStorage` by design)
- Social engineering attacks unrelated to the application code

## Data Handling

Attendance IQ does not transmit, log, or store user data on any server. All attendance records, timetable data, and settings remain in the user's browser `localStorage` unless the user explicitly exports them.

Thank you for helping keep Attendance IQ and its users safe.
