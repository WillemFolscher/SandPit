# Work Hours Clock

A single-file web app for tracking working hours with a clock-in system.

Open `index.html` in any browser (desktop or phone) — no install or server needed.

## Features
- **Clock in / clock out** with a live running timer
- **Breaks** — start/end breaks; break time is subtracted from worked hours
- **Summary** — today, this week, this month, with progress bars against daily/weekly targets
- **Week balance** — overtime (+) or hours still to go (−) against your weekly target
- **Earnings** — set an hourly rate to see this week's pay
- **History** — grouped by day, filter by this week / last week / this month / all
- **Edit, add or delete** entries (e.g. if you forgot to clock in)
- **Export CSV** for timesheets
- **Backup / restore** your data as a JSON file

## Syncing across devices
The same page is published on claude.ai. Opened from that link while signed in, entries are
saved to your Claude account and sync between your phone and computer.

Opened directly (this `index.html` from GitHub or your disk), there is no server, so entries are
saved in that browser only. Use **Download backup** / **Restore backup** to move them.

## TimeFlow (`timeflow.html`)
A second single-file app: an hours & earnings logger with a live GPS timer.
- Log hours manually (date, project, hours, category, notes) or with the live timer
- Captures GPS coordinates and tags entries with named **geofences** (name, lat/lng, radius)
- Hourly rate + currency symbol; totals for all time, this week and this month
- Search / project / date filters, edit & delete, CSV export of the filtered rows
- Data is stored in the browser's localStorage; a running timer survives a page reload
