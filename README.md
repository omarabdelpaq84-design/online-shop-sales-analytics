# Online Shop Sales & Revenue Analytics 🛒📊

## Project Overview
This project analyzes the operational and financial performance of an online retail store. By examining order data across multiple categories (Electronics, Accessories, Furniture), the analysis provides insights into customer purchasing behavior, preferred payment methods, and regional sales hotspots.

## Project Workflow
The repository follows a professional data processing pipeline:

1.  **Raw Data (`Data Before Cleaning`):** Contains ~5,000 raw transaction records with inconsistent naming (e.g., "Omar Ssaid"), missing categories, and mixed date formats.
2.  **Mapping Tables (`Map` & `Q.Map`):** Reference tables used to standardize product-to-category relationships (e.g., mapping "Mouse" to "Accessories").
3.  **Cleaned Data (`Data After Cleaning`):** The final high-quality dataset where duplicates were removed, names were corrected, and categories were filled based on the mapping logic.
4.  **Sales Metrics (`Measures`):** Key business aggregations including:
    * **Category Performance:** Revenue breakdown for Accessories ($5.3M), Furniture ($3.6M), and Electronics ($3.4M).
    * **Payment Preferences:** Transaction volume across Bank Transfers, Cash, Credit Cards, and PayPal.
    * **Geographic Distribution:** Sales performance in major regions like Alexandria, Cairo, and Giza.
5.  **Executive Dashboard (`DashBoard`):** A visual summary featuring core KPIs such as Total Revenue ($12.4M), Total Quantity Sold (12.2K units), and Total Order Count (4,936).

## Key Insights Analyzed
- **Top Performing Products:** Identifying high-revenue items like Desks, Keyboards, and Monitors.
- **Customer Loyalty:** Tracking order counts and total spend for top customers (e.g., Ali Ahmed, Mona Nabil).
- **Logistics & Shipping:** Monitoring the timeline between Order Date and Shipping Date for operational efficiency.
- **Regional Demand:** Comparing market penetration across different Egyptian governorates.

## Tools Used
- **Microsoft Excel:** For data cleaning, VLOOKUP/XLOOKUP mapping, and pivot table analysis.
- **Data Modeling:** Creating relationships between sales data and product category maps.

## How to Explore
- View `Data After Cleaning.csv` for the final sanitized transaction records.
- Refer to `Measures.csv` for a detailed numerical breakdown of sales by region and payment method.

---
*Developed as part of an E-commerce Data Analysis portfolio.*
