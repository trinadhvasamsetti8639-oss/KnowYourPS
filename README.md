# Election Polling Station & Reserve Staff Finder (v2)

A mobile-friendly and desktop-ready GitHub Pages web app for election employees to check their allotted **Polling Station Number (`PSNo`)** or **Reserve Staff** status.

## What's New in v2
- **Updated with `Ward Wise PS Wise Staff attendance at pllinz.xlsx`**: Displays Polling Station Number (`PSNo`), Ward No, Table No, Polling Station Location/Building, Returning Officer (RO) details, Role, and Full Polling Team.
- **No summary counts displayed**: Removed the polling station and staff count statistics bar from the UI.
- **Dedicated Lookup Modes**:
  - **Polling Station Lookup**: Search by Employee ID, Election ID, or Phone Number printed on the Election Order already served.
  - **Reserve Staff Lookup**: Search by Employee ID, Phone Number, or Name as per the Election Order.
- **2-Sheet Excel Admin Updater (`admin-update.html`)**: Supports uploading a single Excel file with one sheet for **Regular** and a second sheet for **Reserve** to regenerate `data.js` in one click.

## How to Publish on GitHub Pages
1. Unzip `election-polling-station-finder-v2.zip`.
2. Upload all 4 files (`index.html`, `data.js`, `admin-update.html`, `README.md`) to your GitHub repository (replacing the older files if updating an existing repo).
3. In GitHub: **Settings -> Pages -> Branch: `main` / `(root)` -> Save**.
