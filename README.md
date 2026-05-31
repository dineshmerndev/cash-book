# CashBook

A simple offline cashbook web app for recording income and expense entries, managing books, and generating reports.

## Project Files

- `cashbook.html` - Main web app with all HTML, CSS, and JavaScript for the cashbook interface.
- `app.py` - Contains the raw HTML/JS content for the project as a Python string.

## Features

- Create and manage multiple cashbooks
- Add income and expense entries
- View ledger summary with total income, expenses, and balance
- Filter entries by category, type, and search text
- Generate reports in PDF or Excel format
- Export all books to Excel or PDF
- Mobile-friendly interface

## How to Run

1. Open `cashbook.html` in a web browser.
2. Use the app directly in the browser.

> For the best experience, use a modern browser such as Chrome, Edge, or Firefox.

## Notes

- This app is fully client-side and does not require a server.
- Data is stored only in memory while the page is open (no persistent storage).
- The app uses CDN libraries for PDF and Excel export:
  - `jspdf`
  - `jspdf-autotable`
  - `xlsx`

## Recommended Usage

- Open `cashbook.html` from the project folder.
- Add books and entries using the interface.
- Use the report screen to generate PDF or Excel exports.

## License

This project has no license file included.
