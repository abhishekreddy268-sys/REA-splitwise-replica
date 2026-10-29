# REA Splitwise Replica

A responsive, independent Splitwise-style application, reconstructed after inspecting Splitwise's public website with REA.

## Run locally

Open `index.html` in a browser, or run:

```sh
python -m http.server 8000
```

Then visit http://localhost:8000. No build step or package installation is required.

## Features

- Groups and friends
- Shared expenses with equal or exact splits, calculated in integer cents
- Friend balances and settlement recording
- Edit and delete expenses
- Expense search, filters, and activity history
- Responsive desktop and mobile layouts
- Browser-local persistence

All amounts use USD. The app includes fictional sample expenses. It does not connect to Splitwise accounts, sync between devices, invite friends, or transfer money.

## Files

- `index.html` — application interface
- `style.css` — responsive styles
- `app.js` — application logic and local storage

## Reconstruction scope

REA inspected the public Splitwise site using Chromium. Authenticated screens and backend behavior were unavailable; this dashboard and local implementation are a reconstruction, not verified source equivalence. This project is independent of Splitwise.

Validated in desktop and mobile browser sessions for adding, editing, deleting, searching expenses, and recording payments.
