# EyeReminder

A lightweight Windows tray application that reminds you to follow the 20-20-20 rule.

Every 20 minutes, look at something about 20 feet (6 meters) away for 20 seconds to reduce eye strain.

---

## Features

- Lightweight and low memory usage
- Runs quietly in the system tray
- Configurable reminder interval
- Configurable notification message
- Auto-reload configuration
- Snooze +5 minutes
- Snooze +20 minutes
- Cancel snooze
- Countdown tooltip on tray icon
- Start with Windows
- Portable EXE build
- Open source

---

## Default Rule

20-20-20:

- Every 20 minutes
- Look at something ~6 meters away
- For 20 seconds

---

## Configuration

Edit `config.json`

Example:

```json
{
    "work_minutes": 20,
    "break_seconds": 20,
    "message": "Look at something about 6 meters away for 20 seconds."
}
```
