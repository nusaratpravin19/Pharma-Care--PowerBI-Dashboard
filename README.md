# PharmaCare – Medicine Stock & Expiry Dashboard

Hey! This is my Power BI project that I made as part of my BCA final year. The idea came from a real problem — pharmacies often don't track medicine expiry properly and end up with a lot of waste. So I thought, why not make a dashboard for it?

---

## What this project is about

I made a dashboard in Power BI that helps a pharmacy keep track of:
- Which medicines are expired or about to expire
- Which medicines are running low on stock
- Total inventory value
- Stock levels by category
- Supplier wise data

It's fully interactive — you can filter by category and storage location and all the charts update automatically.

---

## Dataset

I created the dataset myself with 200 rows of medicine data. It includes medicines like Paracetamol, Amoxicillin, Metformin, Insulin etc. from real Indian suppliers like Cipla, Sun Pharma, Dr. Reddy's, Lupin and more.

The dataset has these columns:

| Column | What it means |
|---|---|
| Medicine_ID | Unique ID for each medicine |
| Medicine_Name | Name and dosage |
| Category | Like Antibiotic, Analgesic, Antidiabetic etc. |
| Supplier | Company name |
| Pack_Type | Strip, Bottle, Vial etc. |
| Batch_No | Batch number |
| Manufacture_Date | When it was made |
| Expiry_Date | When it expires |
| Expiry_Status | Expired / Critical / Expiring Soon / Safe |
| Stock_Quantity | How many units are in stock |
| Reorder_Level | Minimum stock before reorder |
| Stock_Status | Low Stock or Adequate |
| Unit_Price_INR | Price per unit |
| Total_Stock_Value_INR | Total value of that medicine's stock |
| Storage_Location | Shelf A, Shelf B, Cold Storage etc. |

---

## What I used

- Power BI Desktop — for making the dashboard
- Microsoft Excel — for the dataset
- Just a lot of trial and error honestly 😅

---

## Visuals in the dashboard

- Donut chart showing expiry status breakdown
- Bar chart showing stock by category
- Cards showing total expired count, low stock count and total inventory value
- Two slicers — one for category, one for storage location
- A table showing critical and expired medicines with supplier info

---

## How to use

1. Download the files
2. Open `PharmaCare_Dataset.xlsx` if you want to see the data
3. Open `PharmaCare_Dashboard.pbix` in Power BI Desktop
4. Use the slicers on the right to filter the data
5. Click on any chart and the other visuals will filter automatically

---

## About me

**Nusarat Pravin**
BCA Final Year Student
Meerut Institute of Technology, Meerut

GitHub: [nusaratpravin19](https://github.com/nusaratpravin19)
