# WeightTracker

A very simple web project for tracking weight data.

## How it works

Main features:

- Add weight
- Edit entries
- Delete entries
- Export data (CSV)

All data is shown in a list, newest first.

## Technical Details

- Intentionally written as one single `index.html` file — no build step, no framework, no node_modules
- Vanilla JavaScript with Firebase (Firestore + Auth) loaded via CDN
- Google Authentication via Firebase Auth
- Data stored in Firebase Firestore
