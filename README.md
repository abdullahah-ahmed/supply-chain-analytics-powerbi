# 🚚 Supply Chain Analytics Dashboard — Power BI

## 🗂️ Project Overview

An interactive **Supply Chain Analytics Dashboard** built in Power BI for a beauty & cosmetics company operating across multiple Indian cities. The project analyzes product performance, logistics efficiency, supplier quality, and customer satisfaction across 3 product categories: **Skincare, Haircare, and Cosmetics**.

---

## 🎯 Business Questions Answered

- Which product types generate the most revenue and sell the most units?
- How does location affect sales and revenue performance?
- What is the distribution of transportation modes and shipping routes?
- How do inspection results vary by product type?
- What is the average customer satisfaction rate and how does it vary?
- What are the lead times and shipping cost averages across the supply chain?

---

## 🛠️ Work Done

### DAX Measures
Key measures built to support supply chain KPIs:

| Measure | Description |
|---|---|
| `Revenue generated` | Total revenue across all products |
| `avg_satisfaction_rate` | Average customer satisfaction score (1–5) |
| `satisfaction rate` | Satisfaction rate per segment |
| `Availability` | Total stock availability |

### Feature Engineering (Calculated Columns)
- Encoded and categorized `Inspection results` (Pass / Fail / Pending) for visual filtering
- Classified `Product type` for cross-category comparison
- Derived `Transportation modes` and `Routes` groupings for logistics analysis

---

## 📊 Dashboard

### 🟢 Supply Chain Dashboard
**Audience:** Supply Chain Managers, Operations & Logistics Teams

**KPIs:**
- Revenue Generated: **577,605**
- Products Sold: **46,099**
- Availability: **4,840**
- Avg Shipping Cost: **5.55**
- Avg Lead Time: **17.08 days**
- Avg Satisfaction Rate: **2.97 / 5**

**Visuals:**
- 📊 Products Sold & Availability by Product Type (Skincare leads: 20.7K sold)
- 📊 Products Sold & Revenue by Location — Mumbai & Kolkata top performers
- 📈 Price & Revenue by Product Type — Cosmetics highest avg price ($57)
- 🍕 Revenue by Product Type — Skincare 41.83%, Haircare 30.2%, Cosmetics 27.96%
- 🍕 Products by Transportation Mode — Road 29%, Sea 28%, Rail 26%, Air 17%
- 📊 Shipping Times by Product Type
- 📊 Production Volume by Product Type
- 🍕 Products by Routes — Route A 43%, Route B 37%, Route C 20%
- 🍕 Product Type by Inspection Results — Pass 41%, Pending 36%, Fail 23%
- 🎯 Gauge: Customer Satisfaction Score — **2.97/5**

---

## 💡 Key Insights

- **Skincare** dominates in both units sold (20.7K) and revenue share (41.83%).
- **Mumbai & Kolkata** are the top revenue-generating locations.
- **Cosmetics** has the highest average price ($57) but the lowest production volume — premium positioning opportunity.
- **23% of products fail inspection** — a significant quality control risk.
- **Customer satisfaction at 2.97/5** — below average, indicating a need for service improvement.
- **Road transport** is the most used mode (29%) — opportunity to optimize with Sea/Rail for cost reduction.

---

## 🚀 Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | DAX, Calculated Columns, Report Design |
| **DAX** | KPI measures for revenue, satisfaction, availability |
| **Feature Engineering** | Product classification, inspection encoding, route grouping |

---

## 📁 Project Structure

```
📦 Supply-Chain-Analytics/
 ┣ 📊 Supply_Chain_Dashboard.pbix
 ┣ 📸 screenshots/
 ┃ ┗ supply_chain_dashboard.png
 ┗ 📄 README.md
```

---

## 👤 Author

**[Abdullah Ahmed]**
Data Analyst | Power BI Developer
