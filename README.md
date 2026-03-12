# Blood Pressure Tracker

A lightweight, privacy-first web app to track blood pressure throughout the day with reminders. Now with **multi-user support** for families!

## Features

- **Multi-User Accounts** — Create separate accounts for family members, each with private readings and reminders
- **Quick Login/Registration** — Sign up with just a name, email, and password (no cloud account needed)
- **Easy User Switching** — Switch between family members instantly without logging out
- **Log readings** — Record systolic, diastolic, pulse, arm, date/time, and notes
- **Dashboard** — View latest stats, 7-day averages, and interactive trend chart
- **History** — Full reading history with filters by date range and BP category
- **Reminders** — Schedule up to 10 daily reminders per user with browser notifications and optional alarm sound
- **Export** — Download personal readings as CSV
- **Privacy** — All data stored locally in browser localStorage — nothing sent to servers

## Multi-User Features

✅ **Family Accounts**: Each family member creates their own account  
✅ **Isolated Data**: Each user's readings, reminders, and settings are completely separate  
✅ **Quick Switch**: Dropdown menu in header to instantly switch users  
✅ **Password Protected**: Each account secured with password hashing  
✅ **Local Storage Only**: All user accounts and data stay on your device  

## BP Categories (AHA)

| Category | Range |
|----------|-------|
| Normal | < 120 / < 80 |
| Elevated | 120–129 / < 80 |
| High Stage 1 | 130–139 / 80–89 |
| High Stage 2 | ≥ 140 / ≥ 90 |
| Crisis | > 180 / > 120 |

## Usage

1. **Open** `index.html` in any modern web browser
2. **Sign Up** — Create an account with your name, email, and password
3. **Dashboard** — View your BP trends
4. **Add Reading** — Log a new blood pressure measurement
5. **Family Accounts** — Each family member signs up separately (click "+" next to your name to switch)
6. **Reminders** — Set personalized daily reminders
7. **Export** — Download your reading history as CSV

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge).

**Note:** Notifications require browser permission.

## Installation

No installation needed — just open the HTML file in your browser. All accounts and data are stored locally.

## Security Notes

- Passwords are hashed using SHA256 before storage
- All accounts and data remain on your device – never uploaded anywhere
- No cloud sync, no cloud backup (use browser history export for backups)
- Each browser/device has separate accounts

## License

MIT

