# Minimum_Advertised_Price-MAP-Compliance_system 
________________________________________
🔍 Overview
This project builds an automated system to monitor and enforce Minimum Advertised Price (MAP) compliance. It identifies pricing violations by comparing seller prices with the Lowest Possible Price (LPP) and enables enforcement actions.
________________________________________
📁 Database Tables
The system is designed using multiple structured tables:
•	SKU Table – Contains product-level details (SKU, category, attributes)
•	Seller Mapping Table – Maps sellers to authorized products
•	Category Mapping Table – Defines product categories and hierarchy
•	PL Table (Price List Table) – Stores base pricing and LPP values
•	Price List Table – Maintains SKU-level pricing reference data
•	Promotion Table – Tracks promotional offers and discounts
________________________________________
🛠️ Tools & Technologies
•	Python (Pandas) – Data processing and transformation
•	SQL (MySQL) – Data storage
•	Gamma – Insights and presentation
________________________________________
⚙️ Workflow
1. Data Loading
•	Loaded datasets using Python (Pandas)
2. Data Cleaning & Transformation
•	Cleaned null values, duplicates, and inconsistencies
•	Standardized SKU-level data for accurate tracking
3. Database Integration
•	Imported all datasets into SQL database
•	Structured relational tables for efficient joins
4. Price Violation Detection
•	Compared Seller Advertised Price (SAP) with LPP
•	Flagged violations where SAP < LPP
5. Enforcement Logic
•	Generated warning alerts for violating sellers
•	Ensured compliance with MAP policies
6. Reporting & Insights
•	Presented findings using Gamma
•	Highlighted trends and violations


