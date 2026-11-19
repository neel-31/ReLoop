# ReLoop — E-Waste Passport ♻️

ReLoop is a campus-focused e-waste management prototype that gives discarded or unused electronic devices a digital passport and helps route them toward reuse, repair assessment, or authorized recycling.

## Problem
Unused and discarded electronics are often difficult to track, and people may not know whether a device should be reused, repaired, or sent to an authorized e-waste handler.

## Proposed solution
ReLoop lets a user register an electronic item, record its category and condition, and track its lifecycle using a unique passport ID. The suggested pathway is an initial recommendation only; damaged devices and batteries should be assessed and handled by trained or authorized personnel.

## Current prototype features
- Dashboard with item counters
- Register an electronic item
- Generate a passport ID
- Suggest a pathway based on the reported condition
- Search and filter records
- Update item lifecycle status
- Responsive interface

## Project structure
```text
ReLoop-GitHub-Project/
├── README.md
├── src/
│   └── index.html        # Current standalone prototype
└── docs/
    └── ReLoop_Project_Report.pdf
```

## Run locally
1. Clone or download this repository.
2. Open `src/index.html` in a browser.

The current prototype stores records in browser memory only. Refreshing the page resets prototype data. Firebase/Firestore persistence and authentication are planned/in progress and are not yet connected in this version.

## Planned improvements
- Firebase Firestore database
- Authentication and role-based access for students/coordinators
- Persistent item records and real-time updates
- Authorized recycler/repair partner workflow
- QR code for each digital passport
- Admin dashboard and audit trail

## Safety note
The pathway suggestions are not a safety assessment. Do not dismantle electronic devices or damaged batteries. Use trained personnel and authorized e-waste collection channels.

## Project report
See [`docs/ReLoop_Project_Report.pdf`](docs/ReLoop_Project_Report.pdf).

## Status
Prototype / development in progress.
