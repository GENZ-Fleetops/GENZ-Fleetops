# GENZ FleetOps™ — Upload Package

## Folder Structure
```
GENZ-FleetOps/
├── index.html        ← Marketing landing page (homepage)
├── crm.html          ← CRM Operations Command Center
├── booking.html      ← B2C Booking Engine
├── dispatch.html     ← Live Dispatch Module
├── finance.html      ← Finance & P&L Dashboard
├── driver.html       ← Driver App Preview (2 phone screens)
├── settings.html     ← Platform Settings (NEW)
└── assets/
    └── genz-fleetops-logo.png   ← Place your logo here
```

## Asset Required
Create an `assets/` folder inside `GENZ-FleetOps/` and add:
- `genz-fleetops-logo.png` — Your GENZ FleetOps logo (recommended: 200x100px PNG)

## Hosting Options

### Option A — Netlify (Fastest, free)
1. Go to netlify.com → "Add new site" → "Deploy manually"
2. Drag the entire `GENZ-FleetOps/` folder into the upload zone
3. Done — live in 30 seconds

### Option B — cPanel / Web Hosting
1. Open File Manager → public_html
2. Upload all 7 HTML files + assets/ folder
3. Set index.html as home page

### Option C — Local Preview
Double-click `index.html` to open in browser.
All links between pages work as relative paths.

## Nav Links (all corrected)
Every page links to:
- index.html (HUB / landing page)
- crm.html
- booking.html
- dispatch.html
- finance.html
- driver.html
- settings.html

## WhatsApp Contact
Update the WhatsApp number in each nav's CONTACT button:
Find: `https://wa.me/971504236099`
Replace: `https://wa.me/YOUR_NUMBER`
