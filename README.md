# dreytools-scheduling

Full calendar / event scheduler for drey tools.

**Live:** https://scheduling.dreytools.com
**CF project:** `dreytools-scheduling`

## Features

- Month grid view (7-col, prev/next nav, today button)
- List view (upcoming events grouped by day)
- Sidebar mini-calendar with event dots + calendar filters (Work/1BB/Clients/Personal/Health)
- New event modal: title, date, time, duration (15/30/45/60/90/120), color picker, notes
- View/edit event modal with delete
- 5 color categories (cyan/amber/pink/violet/green)
- localStorage persistence (dreytools-scheduling-events-v1)
- Seeded with realistic events on first load (Kevin sync, Amanda client call, Luis pair session, gym, etc.)
- Mobile-responsive (sidebar hides, touch-first)
- Safe-area insets for notch/home bar

## Future

Wire to Dottie phone AI for voice-triggered event creation, and/or Google Calendar sync via OAuth.

## Stack

Pure HTML + CSS + vanilla JS. Single file. Zero dependencies.

## Deploy

```bash
wrangler pages deploy . --project-name dreytools-scheduling --branch main
```
