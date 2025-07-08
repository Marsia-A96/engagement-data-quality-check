# Excel Data Validation: Engagement Codes

🗂️ A practical Excel project demonstrating how to validate engagement-level data — with a focus on back-office operations, finance support, and data quality.
## 🔍 Objective:
Bring together data from two sheets (Engagements + Clients) and ensure it is clean, consistent, and ready for downstream use (e.g. invoicing, reporting, SAP).

---

## ✅ What it includes:

### 🔗 3 lookup approaches to achieve the same goal:
> Return the Client Name from a secondary sheet using:

- `VLOOKUP`
- `XLOOKUP`
- `INDEX + MATCH`

📌 This demonstrates flexibility and understanding of different Excel techniques.

---

### ⚙️ Data Quality Checks:
Each entry is evaluated using formulas such as:

- `ISBLANK` ➤ Missing values (e.g. Amount, Invoice Date)
- `COUNTIF` ➤ Duplicated Engagement Codes
- `LEN` / `LEFT` ➤ Format validation for code structure (e.g. "ENG-2024-XXXX")

---

### 🎨 Usability Features:
- Conditional Formatting for fast visual checks
- Pivot Table-ready layout
- Modular structure for Power Query expansion

---

## 📁 Files
- `Engagement_Final_Validated.xlsb`: main file
- `README.md`: documentation

---

## 🔧 Suitable for:
- Finance & Operations roles
- Reporting / Data Entry Quality Checks

