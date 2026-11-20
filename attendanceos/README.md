# AttendanceOS — Sinai University

A standalone attendance tracker for Level 4 · Semester 1, Sinai University Faculty of Dentistry.

## Open the app
Visit the `attendanceos/` directory in this repository or use the deployed GitHub Pages route after Pages deployment has completed.

## Included
- 15-week weekly register, with Week 08 excluded as the exam week.
- Official absence rate counts only **Absent · instructor recorded**.
- Weeks with no entered attendance are excluded from the rate.
- Absent-not-recorded and absent-marked-present remain visible but do not increase the official absence numerator.
- Local browser persistence and JSON backup/restore.
- Weekly and semester PDF / Excel exports.
- Sinai University logo embedded in the standalone app.

## Privacy
Attendance records are stored in the browser on the user's device. They are not uploaded to this repository or a remote database.

## GitHub Pages
The workflow at `.github/workflows/deploy-pages.yml` publishes the existing profile homepage together with this app under `/attendanceos/`.
