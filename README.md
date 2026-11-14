# Simple Books – Accounting Website

🔗 **Live demo:** https://shiza-naveed.github.io/simple-book-accounting/

A single-page web app that helps small businesses record transactions and automatically generate financial statements.

## Screenshots
<img width="1897" height="891" alt="Screenshot 2026-11-14 105006" src="https://github.com/user-attachments/assets/e3c984de-be6b-4318-9a3a-dd630d2dadc0" />
<img width="1172" height="507" alt="Screenshot 2026-11-14 110510" src="https://github.com/user-attachments/assets/ee010b84-0f04-4e5a-b33b-11afb681760d" />
<img width="1895" height="901" alt="Screenshot 2026-11-14 111127" src="https://github.com/user-attachments/assets/ed4857f7-8b9a-47ee-8a18-e88092cea44f" />
<img width="1915" height="911" alt="Screenshot 2026-11-14 111138" src="https://github.com/user-attachments/assets/5ced31ba-b49b-4c87-88f1-cc9906f85afc" />
<img width="1892" height="912" alt="Screenshot 2026-11-14 111152" src="https://github.com/user-attachments/assets/916d7b82-a851-4fae-a0f1-f8e92e40bb9c" />
<img width="1873" height="893" alt="Screenshot 2026-11-14 111200" src="https://github.com/user-attachments/assets/b5edce98-0805-4c2f-acc1-024b68da67b0" />
<img width="1876" height="902" alt="Screenshot 2026-11-14 111218" src="https://github.com/user-attachments/assets/a3def918-c561-475e-81f6-04e18db8d0d9" />
<img width="1877" height="743" alt="Screenshot 2026-11-14 111244" src="https://github.com/user-attachments/assets/125cd4ab-64c9-49d9-b239-ba19f8aa1093" />
<img width="1882" height="907" alt="Screenshot 2026-11-14 111335" src="https://github.com/user-attachments/assets/a4407018-e4ca-4696-abb7-64d1b56c0747" />

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
