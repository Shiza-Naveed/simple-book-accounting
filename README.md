# Simple Books – Accounting Website

A single-page web app that helps small businesses record transactions and automatically generate financial statements.

## Features

- **Accounts:** create parties such as lenders, customers and suppliers (e.g. "ABC Company")
- **Transactions:** record loans received, liability payments, service income, expenses, invoices and owner investment in organized tables
- **Financial statements:** balance sheet and income statement, generated automatically every month and every year
- **T-accounts:** ledger view with debits and credits for Cash, Receivables, Liabilities, Capital, Revenue and Expenses
- **Admin notifications:** in-app alerts (plus optional browser notifications) when a report is ready
- **Autosave:** all data is saved automatically in the browser's local storage
- **Login:** password-protected access with salted and hashed passwords (Web Crypto API)
- **Backup:** export and import data as a JSON file
- **Responsive:** works on desktop and mobile, with light and dark mode

## Tech Stack

HTML, CSS, JavaScript (no frameworks or dependencies)

## How to Run

1. Download or clone this repository.
2. Open `index.html` in any modern browser. No installation or server is needed.

## Limitations

- Data is stored in the browser's local storage, so it stays on one device and browser. Use the export feature to back it up.
- The login is client-side only. It locks the interface but does not encrypt stored data. A backend would be needed for full security.
- Reports are generated when the site is opened after a month or year ends.

## Future Improvements

- Backend and database for cloud sync and multi-user access
- Real email notifications
- Encrypted data storage
