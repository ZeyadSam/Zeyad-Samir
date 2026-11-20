# AttendanceOS — Sinai University Edition

A weekly attendance tracker for Level 4, Semester 1, Faculty of Dentistry.

## Launch

Open [the AttendanceOS app](./index.html) in a modern browser.

## Included behavior

- 15-week semester with Week 08 excluded as the examination week.
- The final two Monday sessions are omitted.
- Course names are shown without course codes.
- Only **Absent · instructor recorded** contributes to the official absence-rate numerator.
- Weeks with no attendance entries are excluded from the rate; pending sessions are excluded.
- The maximum permitted official absence rate is 25%.
- Local autosave, JSON backup/restore, weekly and semester PDF/XLSX exports.

## Data and privacy

Attendance records are stored locally in the browser. They are not uploaded to GitHub. Use the in-app JSON backup before changing browsers or clearing browser data.

## Hosting

This folder is kept separate from the repository's existing root website. When GitHub Pages is configured to publish the repository root from the default branch, the app is available at:

`https://zeyadsam.github.io/Zeyad-Samir/attendanceos/`
