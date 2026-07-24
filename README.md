# Retail Sales Intelligence App

## Overview
This application was generated via Google AI Studio and deployed via Cloudflare Pages. It serves as a business dashboard that processes client-side Excel files (`retail_weekly_sales.xlsx` and `store_master.xlsx`) to deliver real-time KPIs, interactive charts, and automated business insights without requiring backend server persistence.

## Features
- **Data Upload:** Parses raw Excel data directly in the browser using SheetJS.
- **KPI Tracking:** Net Sales, Target Achievement, Average Transaction Value, Return Rate, and Discount Rate.
- **Interactive Visualizations:** Powered by Chart.js (Trend lines, Bar charts, Doughnut charts).
- **Dynamic Filtering:** Updates all metrics instantly based on Week, Region, Store, City, Format, and Category.
- **Automated Insights:** Flags underperforming stores and high-return categories.

## Deployment Pipeline
1. **AI Studio:** Prompted to generate a single-file vanilla JS/HTML/CSS dashboard.
2. **GitHub Integration:** Code exported directly to a GitHub repository.
3. **Cloudflare Pages:** Repo connected to Cloudflare for hosting. 
   - Build Command: None
   - Output Directory: /
   - Live URL: https://retail-sales-intelligence-app-dyd.pages.dev/
