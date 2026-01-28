# Mobile Device Price & Value Analysis Dashboard (Power BI)

A Power BI project that compares smartphone specifications and ranks devices by **best value** using a weighted **Value Score**.

## What this dashboard answers
- Which devices offer the best value for money based on specs vs price?
- How do brands compare on overall value?
- What are the top devices when filtering by key features (e.g., 5G, storage, battery)?

## Dataset
- Source: Manually compiled / public listings (specifications and pricing)
- Fields used: Brand, Model, Price, RAM, Storage, Battery, Camera (MP), 5G
- Notes: Any sensitive data has been removed/anonymized (if applicable).

## Method (Value Score)
The Value Score is calculated by assigning weights to key specs and balancing them against price.  
This allows quick ranking of devices while keeping the scoring logic transparent and adjustable.

## Dashboard pages / outputs
- **Best Value Devices:** Top-ranked devices using Value Score (table + filters)
- **Brand Comparison:** Value Score by brand (summary visuals)
- **Device Matrix:** Specs comparison across devices (price, RAM, storage, battery, camera, 5G)

## Tools
- Power BI (report + visuals)
- Excel/CSV (data preparation)

## How to view
- Open the PDF export: `exports/dashboard.pdf` (recommended)
- View screenshots: `exports/screenshots/`
- Open the Power BI file: `pbix/dashboard.pbix`

## Notes
- The scoring weights can be tuned depending on what "value" means (e.g., prioritize battery vs camera).
- This project is intended for reporting and comparison purposes, not as a definitive purchasing recommendation.
