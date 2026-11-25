# FitZonee Studio

A responsive, self-contained fitness-studio management project with separate front-desk and member experiences.

## Run the project
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, or another modern browser.

No installation, server, or internet connection is required.

## Main features
- Separate Admin and Client portals on the responsive sign-in screen
- Optional browser-local “remember me” session and sign out control
- Admin-only member management, including persistent add and remove actions
- Client-only private dashboard with weekly workouts, active minutes, monthly goals, and optional reflections
- Weekly and monthly client progress tracking stored per email address in the current browser
- Client trainer directory with browser-local session requests and cancellation
- Goal-based weekly workout schedules with four fixed routines: general fitness, strength, muscle building, and fat loss
- INR membership comparison: ₹1,500 monthly, with savings for 3-month, 6-month, and annual plans
- Reliable admin attendance selector that stores one check-in per active member per day
- Dashboard with summary cards and attendance chart
- Members list and Add Member form
- Attendance check-in demo
- Trainer cards
- Payments page clearly marked as simulated (no real payments)
- Reports page with print option
- Custom page-not-found screen with a 3-step wellness quest
- Responsive mobile navigation

## Notes
This is a front-end demonstration. Member and personal-progress records are stored in the browser on the device being used. The sign-in screen validates the entered email and password format but does not send or retain passwords. The Admin/Client role boundary is enforced in the visible interface and navigation, but secure authentication and authorization for a real deployment require a server-side database and backend. It does not include a real payment system.
