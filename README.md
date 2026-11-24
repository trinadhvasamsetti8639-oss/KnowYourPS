# Election Polling Station & Reserve Staff Finder

A fast, mobile-friendly and desktop-ready web application for election staff to look up their allotted **Polling Station / Group Number**, **Role (PO / APO / OPO)**, and **Full Polling Team**, or check if they are placed under **Reserve Staff**.

## Included Data
- **491** Polling Stations / Groups
- **2,946** Assigned Election Staff (PO, APO, OPO-1 to OPO-4)
- **18** Unassigned / Reserve Staff (from rows without a Group Number)
- **Total:** 2,964 verified records from `MPL_PO-APO-OPO_Verified - Copy.xlsx`

## How to Host on GitHub Pages (Free, 2 Minutes)
1. Unzip `election-polling-station-finder.zip`.
2. Create a new public repository on [GitHub](https://github.com/new) (for example, `election-duty-finder`).
3. Click **Add file -> Upload files**, drag and drop all 4 files (`index.html`, `data.js`, `admin-update.html`, `README.md`), and click **Commit changes**.
4. Go to **Settings -> Pages** in your repository.
5. Under **Build and deployment -> Branch**, select `main` and `/ (root)`, then click **Save**.
6. In ~1 minute, your live link will appear at `https://<your-username>.github.io/<repo-name>/` — share it or turn it into a QR code for election staff!

## Adding a Separate Reserve Staff Excel / CSV Later
If you have an additional Reserve Staff Excel or CSV file:
1. Open `admin-update.html` in any browser (either locally or on your GitHub Pages site).
2. Upload your Reserve Staff `.xlsx` / `.csv` file.
3. Click **Merge & Download Updated data.js**.
4. Upload the new `data.js` to your GitHub repository to overwrite the old one.
