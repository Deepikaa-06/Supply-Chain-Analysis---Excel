# 📦 Supply Chain Analysis Project

## 📌 Project Overview

This project focuses on analyzing supply chain data to identify discrepancies between **expected courier charges** and **actual billed charges**. The analysis helps in detecting overcharges, understanding shipment patterns, and improving cost efficiency.

---

## 📂 Dataset Description

The project is based on multiple datasets combined into a single Excel workbook:

* **Order Report** → Contains order-level details
* **SKU Master** → Product weight and SKU information
* **Invoice** → Courier billing details
* **Rates** → Pricing structure for shipments
* **Pincode Zones** → Mapping of delivery zones
* **Summary Sheet** → Aggregated insights
* **Final Report** → Cleaned and analyzed dataset
* **Pivot Table** → Visual summary for insights

---

## ⚙️ Steps Performed

1. **Data Cleaning**

   * Removed inconsistencies and missing values
   * Standardized column formats

2. **Data Merging**

   * Combined multiple sheets using common keys (Order ID, SKU, etc.)

3. **Feature Engineering**

   * Calculated total weight per order
   * Derived weight slabs for pricing

4. **Cost Calculation**

   * Computed **Expected Charges** using rate cards
   * Compared with **Courier Billed Charges**

5. **Analysis**

   * Identified differences between expected and actual charges
   * Highlighted overcharged and correctly charged orders

6. **Visualization**

   * Created pivot tables for better understanding
   * Summarized key metrics

---

## 📊 Key Insights

* Many orders show a **difference between expected and billed charges**
* Overcharging occurs mainly due to:

  * Incorrect weight slabs
  * Wrong delivery zone classification
* Some orders are correctly billed, showing accurate rate application
* High-weight shipments contribute most to cost variation

---

## 🛠️ Tools Used

* **Microsoft Excel**

  * Pivot Tables
  * Formulas & Functions
  * Data Cleaning Techniques

---

## 📈 Project Outcome

* Built a structured system to **validate courier charges**
* Identified cost leakages in the supply chain
* Provided insights to improve billing accuracy

---

## 📎 How to Use

1. Download the Excel file from this repository
2. Open in Microsoft Excel
3. Explore:

   * **Final Report** for detailed analysis
   * **Summary** for quick insights
   * **Pivot Table** for visualization
