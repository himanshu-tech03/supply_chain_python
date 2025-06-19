📦 Supply Chain Billing Audit & Analysis
📝 Project Description
This project analyzes and validates courier billing data by comparing the actual charges billed by a courier company with the expected charges calculated by Company X. It uses SKU-level product weights, pincode-based delivery zones, and courier rate cards to compute fair charges and identify overcharges or undercharges.

🔍 Objectives
✅ Calculate total shipment weight for each order using SKU-level product weights.

✅ Map shipment weight into standard courier slabs (multiples of 0.5 KG).

✅ Derive expected charges based on company-provided courier rate card.

✅ Compare expected charges with billed charges and quantify differences.

✅ Perform zone-wise, slab-wise, and billing accuracy analysis.

✅ Visualize key findings using bar plots, pie charts, boxplots, and heatmaps.

📂 Files Used
File	Description
Company X - Order Report.xlsx	Contains order-wise SKU quantity
Company X - SKU Master.xlsx	SKU-wise gross weight in grams
Courier Company - Invoice.xlsx	Courier invoice: charged weight and billing
Courier Company - Rates.xlsx	Courier rate card by zone and slab
Company X - Pincode Zones.xlsx	Mapping of pincode pairs to delivery zones
supply_chain.ipynb	Jupyter notebook with full logic and analysis

📊 Visualizations Included
Average charges per weight slab (0.5kg, 1kg, 1.5kg…)

Billing amount distribution by slab

Overcharge/undercharge summary by zone

Zone-wise order volume & billing comparison

Billing accuracy breakdown using pie chart

📈 Tools & Libraries
Python 3.x

pandas, numpy – data manipulation

matplotlib, seaborn – visualization

📌 Key Insights
Slab mismatch leads to recurring overcharges in certain zones

Billing is mostly accurate for 0.5kg and 1kg slabs

Zone C had the highest overcharge incidents

Courier billing is generally consistent, but audit flags anomalies

✅ How to Run
Place all Excel files in the working directory.

Open supply_chain.ipynb in Jupyter or VS Code.

Run all cells from top to bottom.


