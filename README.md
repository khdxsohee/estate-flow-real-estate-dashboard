
# EstateFlow - Real Estate Business Dashboard

EstateFlow is a responsive real estate business dashboard designed to help teams review property listings, leads, transactions, agent activity, and business performance from one interface.

The dashboard includes interactive charts, searchable tables, date-range controls, and a dark-mode option. It currently uses sample data and runs as a front-end demo.

<img width="1366" height="1253" alt="screencapture-file-C-Users-Wang-Lin-s-Heart-Downloads-file-html-2026-11-24-02_08_33" src="https://github.com/user-attachments/assets/3dfb356a-7f30-4585-9898-0a154a7ad8fe" />

## Features

- **Overview dashboard** with revenue, listings, leads, and conversion metrics
- **Revenue chart** showing sample revenue and sales trends
- **Lead sources chart** for website, social media, referrals, and other sources
- **Properties section** with sample listings and searchable records
- **Leads section** with sample lead details and search
- **Transactions section** with deal and transaction records
- **Calendar section** with sample meetings, viewings, and events
- **Agents section** with sample team performance information
- **Reports section** with sample business reports
- **Settings section** showing workspace preferences
- **Dark-mode toggle**
- **Responsive layout** for desktop, tablet, and mobile screens
- **Sidebar navigation** between dashboard sections
- **Interactive demo buttons** with notifications

## Tech Stack

- HTML
- CSS
- JavaScript
- [Chart.js](https://www.chartjs.org/) for charts
- Google Fonts: DM Sans and Manrope

## Getting Started

### Option 1: Open the file directly

1. Clone or download this repository.
2. Open `index.html` in a web browser.

### Option 2: Run a local development server

If you have Python installed, open a terminal in the project folder and run:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

The dashboard uses external resources for Chart.js and Google Fonts, so an internet connection is needed to load those resources.

## Project Structure

```text
estate-flow-real-estate-dashboard/
├── index.html
└── README.md
```

The dashboard's styles, page markup, sample data, and JavaScript are currently contained in `index.html`.

## Using the Dashboard

- Select **Overview** to return to the main dashboard.
- Use the sidebar to open other sections.
- Search the Properties table by property name, location, or other visible text.
- Filter the Properties table by status.
- Change the date range to update the displayed sample revenue and lead figures.
- Use the theme button in the top bar to switch between light and dark mode.
- Use the section search boxes to filter the visible sample records.

## Demo Data

The dashboard currently displays sample property, lead, transaction, and agent information. The displayed names, figures, and business activity are placeholders for demonstration purposes; they are not connected to a live business database.

## Limitations

This project is currently a front-end demo:

- Data changes are not saved permanently.
- There is no login or user authentication.
- Add, edit, and action buttons display demo notifications rather than saving records.
- Charts and metrics use sample values.
- No backend or database is connected.

## Future Improvements

Possible next steps for the project include:

- Connect a backend API and database.
- Add authentication and role-based access.
- Build forms to create and edit properties, leads, and transactions.
- Save changes and dashboard settings.
- Add data export and report downloads.
- Connect charts to real business data.
- Add automated tests and deployment instructions.

