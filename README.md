# E-RDV (erdv)

Static **HTML mockups** for an appointment-booking portal (Tailwind CSS via CDN, Font Awesome, Google Fonts). There is no build step: open `index.html` or deploy the repo root to any static host.

## Run locally

- Double-click `index.html`, or serve the folder (e.g. `npx serve .`) so all paths behave like production.

## Layout

| Path | Purpose |
|------|---------|
| `index.html` | Public entry (same as `home/landing.html`) |
| `home/landing.html` | Landing / marketing home |
| `booking/select-timeslot.html` | Branch, date, and time slot selection |
| `booking/personal-info.html` | Visitor details capture |
| `booking/confirmation.html` | Booking confirmation |
| `booking/feedback.html` | Post-appointment feedback |
| `dashboards/day.html` | Day-of appointments view |
| `dashboards/helpdesk.html` | Help desk dashboard |
| `dashboards/branch-manager.html` | Branch manager dashboard |
| `dashboards/it-admin.html` | IT administrator dashboard |
| `management/appointments.html` | Appointment management / back office |

## Deploy

Publish this directory as the site root so `/` resolves to `index.html`. All assets load from CDNs; no secret keys are required.