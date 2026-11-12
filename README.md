# ARKA Realty — Chi-V, Greater Noida

A zero-cost, static website for a student rental and PG referral brokerage.

## Launch

1. In GitHub repository **Settings → Pages**, choose **Deploy from a branch**, **main**, **/(root)**, then **Save**.
2. GitHub may publish at `https://arkarealty123.github.io/arka-realty-site./` (the repository name currently ends in a period). Rename it to `arka-realty-site` if you prefer a cleaner address.
3. Set the public website URL in your existing Google Business Profile.
4. Add **actual** student, owner and PG Google Form links to website buttons after creating the forms. Never store student data in this public repository.
5. Only add properties to `properties.json` after verifying authorization, current prices, occupancy conditions and written marketing permission.
6. Publish real business contact details, the final privacy notice and legally reviewed terms before collecting enquiries.

## Inventory format

```json
[
  {
    "type": "flat",
    "title": "Owner-approved listing title",
    "area": "Chi-V, Greater Noida",
    "details": "2 BHK · furnished · terms confirmed on date",
    "rent": 18000,
    "verified": true,
    "marketingConsent": true
  }
]
```

This is a **format example only**, not a real available property. Leave the production file as `[]` until a verified listing is ready.

### Operations

- Leads: private Google Forms → private Google Sheets
- Property verification: human-led due diligence
- Visits: manual confirmation and calendar
- Transactions: written fee disclosure, signed agreements, receipts and compliance checks
- Public website: static files only; **no cloud admin login or live CRM connection**
- Business Profile: supplied link is included but public identity has not been independently verified

### Not included

Automated backend, private database, payment processing, live listing sync, third-party API integrations or paid communication services.

### Note on GitHub Pages

Publishing the website files to the repository does not automatically activate GitHub Pages. An account administrator must enable Pages in repository settings.