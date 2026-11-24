# Election Polling Station & Reserve Staff Finder (Final)

A responsive GitHub Pages web application for both **mobile phones and desktop computers**, built from `Final Election Orders Database for Polling station search.xlsx`.

## Features
- **Clean, Count-Free UI:** Does not display total polling station or staff allotment counts.
- **Polling Station Lookup (`Sheet1`):** Displays the allotted **Polling Station Number (`PSNo`)**, Ward No, Table No, Polling Station Location, Returning Officer (RO) details, Role, and expandable Full Polling Team when staff enter their **Election ID**, **Employee ID**, or **Phone Number** printed on their Election Order.
- **Reserve Staff Lookup (`Sheet2`):** Allows Reserve Staff to search by **Employee ID (`EMP_ID`)**, **Phone Number**, or **Name as per Election Order**, and displays the Reserve instruction alert along with their verified details.
- **2-Sheet Excel Updater (`admin-update.html`):** Upload a future 2-sheet Excel workbook to regenerate `data.js` in one click.

## How to Publish on GitHub Pages
1. Unzip `election-polling-station-finder-final.zip`.
2. Upload all 4 files (`index.html`, `data.js`, `admin-update.html`, `README.md`) to your GitHub repository.
3. Go to **Settings -> Pages -> Branch: `main` / `(root)` -> Save**.
