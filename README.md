# Chronos MBA — Schedule & Mess Menu Planner

A modern, responsive web application for MBA students (PGDM Term-05) designed to align course timetables strictly to enrolled electives and provide instant access to the daily campus mess menu and **Bowld Over** specials.

Live on GitHub Pages: `https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/`

---

## 🎯 Features

- **Strict Subject Filtering**: Pre-configured and filtered exclusively for 6 subjects:
  1. *Scaling New Ventures*
  2. *Designing Employer Branding Campaigns*
  3. *Marketing Analytics*
  4. *Marketing Metrics*
  5. *Managing Global Teams*
  6. *Negotiation and Bargaining*
- **Dynamic Weekly Timetable**: View by day or filter by subject with instructor, room/venue, and session details.
- **Excel & CSV File Upload**: Drag-and-drop raw campus timetables (`.xlsx`, `.csv`) to auto-extract only your 6 subjects using client-side SheetJS.
- **7-Day Mess & Bowld Over Menu**: Full breakdown for Breakfast, Lunch, Evening Snacks, and Dinner (Monday–Sunday) with special callouts for Bowld Over and Delhicious dinners.
- **Prep Tasks & Reminders**: Track case prep, assignment submissions, and deadlines.
- **100% Client-Side & Zero-Config**: Runs directly in the browser using HTML5, Tailwind CSS CDN, Font Awesome, and LocalStorage for persistence. No build steps required.

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/<YOUR-USERNAME>/my-schedule-app.git

# Open the directory
cd my-schedule-app

# Run with any static server (or double click index.html)
npx serve .
# Or with Python
python3 -m http.server 3000
```
Then visit `http://localhost:3000`.

---

## 🌐 Deploy to GitHub Pages (Free Hosting)

1. Go to your repository on GitHub.
2. Click **Settings** (tab at the top).
3. In the left sidebar, click **Pages**.
4. Under **Build and deployment > Branch**, select `main` (or `master`) branch and folder `/ (root)`.
5. Click **Save**.
6. Wait 1-2 minutes. Your live link will appear at the top:
   `https://<YOUR-USERNAME>.github.io/my-schedule-app/`
