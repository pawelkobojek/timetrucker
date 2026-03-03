# Time Tracker

A simple time tracking app. Track hours per client, generate PDF reports. Data lives in a Google Sheet in your Google Drive.

## How It Works

- **Frontend:** Single HTML file (no build step, no framework)
- **Backend:** Google Sheets (your own spreadsheet, in your Drive)
- **Auth:** Google OAuth
- **PDF:** Generated in-browser with jsPDF
- **Cost:** $0

## Usage

1. **Sign in** with your Google account
2. **Add clients** via the "Clients" button
3. **Log time** with "+ Add Entry" (date, client, description, hours)
4. **Filter** by client or month using the toolbar
5. **Generate PDF** — pick a client, date range, and hit "Generate PDF"
6. The PDF downloads immediately

All data is stored in a Google Sheet called **"Time Tracker Data"** in your Google Drive.
