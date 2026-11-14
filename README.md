# Pak Rose Enterprises — Offline Attendance (starter APK project)

This is a starter native Android project. It stores employee and attendance data locally in SQLite on one Android phone and does not require internet during normal use.

## Build APK from GitHub on a phone
1. Create a GitHub repository named `Pak-Rose-Attendance`.
2. Upload the **contents** of this folder to the repository root (not the enclosing folder).
3. Open the repository's **Actions** tab and enable Actions if prompted.
4. Select **Build Pak Rose APK** and tap **Run workflow** (or push to `main`).
5. When the workflow completes, open its run, scroll to **Artifacts**, and download `Pak-Rose-Attendance-APK`.
6. Extract the ZIP and install `app-debug.apk`. Android may ask permission to install unknown apps for the browser/files app.

## Included in this starter
- Add/delete employees and monthly salary
- Daily attendance: Present, Absent, Paid Leave, Unpaid Leave
- Basic monthly salary estimate with calendar-day per-day deductions for Absent and Unpaid Leave
- CSV export of employee list

## Important limitations
This is an initial starter build, not the complete payroll system previously discussed. It does not yet include check-in/check-out, late/early deductions, salary advances, salary slips, full attendance CSV export/import, app PIN, or database restore. Export currently backs up the employee list only. Keep the phone secure and export backups; uninstalling the app or losing the phone can lose locally stored data. Test calculations before using them for actual payroll.
