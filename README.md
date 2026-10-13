# Deal Radar: Toyota 4Runner Market Tracker

A cloud data pipeline that tracks Toyota 4Runner listings across the US, used and new, and prices each one against the market so underpriced trucks stand out.

**Status:** In progress, built in public.

## Approach

- **Ingest broadly:** every 4Runner listing, all generations, kept as raw data from day one.
- **Model narrowly:** pricing starts with the 5th generation (2010 to 2024), with other generations and new trucks added once there is enough data.

## Stack

eBay Browse API, NHTSA vPIC, Azure Functions, Azure Blob Storage, Azure SQL, dbt, GitHub Actions, Power BI

## Outputs

- Power BI report of market prices and flagged deals
- Public website for 4Runner shoppers and owners

---
Natnael Gebremeden · Garland, TX