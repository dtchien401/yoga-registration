# International Yoga Day Landing Page

## Files
- `index.html`: landing page with public registration tab and password-protected dashboard tab.
- `Code.gs`: Google Apps Script backend to save/read data from Google Sheet.

## Setup
1. Create a Google Sheet.
2. Copy the Sheet ID from the URL.
3. Open Extensions > Apps Script.
4. Paste `Code.gs`.
5. Replace `SHEET_ID`.
6. Deploy as Web App:
   - Execute as: Me
   - Who has access: Anyone
7. Copy the Web App URL.
8. Paste it into `API_URL` inside `index.html`.
9. Upload `index.html` to GitHub Pages / Netlify / your web host.

## Default dashboard login
- User: `admin`
- Password: `CaliLife`
