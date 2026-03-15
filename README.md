# YBF Club Finance

A club finance management web app built with HTML + Firebase Firestore.

## Features
- Admin login — manage balance, expenses, members
- Member login — add personal expenses, view by month/year
- Firebase Firestore — real-time cloud database
- Export to Excel and PDF
- Password reset via phone number

## Default Login
- **Username:** admin
- **Password:** admin2024

> Change the admin password from inside the app after first login (coming soon) or edit directly in Firebase Console → club → config document.

## Tech Stack
- Plain HTML + CSS + JavaScript
- Firebase Firestore (database)
- Hosted on Vercel

## Project Structure
```
club-finance/
├── public/
│   └── index.html      ← entire app
├── vercel.json         ← vercel routing config
├── .gitignore
└── README.md
```

## Deploy
1. Push to GitHub
2. Import repo on vercel.com
3. Set root directory to `public`
4. Deploy!
