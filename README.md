# Employee-Sales-EDA
Exploratory Data Analysis on employee sales data using Python, Pandas &amp; Matplotlib — covering outlier detection, distribution analysis, and salary-sales correlation.

# 📊 Employee Sales Data — Exploratory Data Analysis

An end-to-end EDA on an 8-employee HR/Sales dataset using NumPy, Pandas, and Matplotlib — covering data profiling, outlier detection, distribution analysis, and correlation testing.

---

## 📁 Dataset

| Column | Description |
|---|---|
| `Emp_ID` | Unique employee identifier |
| `Age` | Employee age |
| `Gender` | M / F |
| `Department` | HR, Sales, or IT |
| `Experience` | Years of experience |
| `Salary` | Monthly salary (₹) |
| `Sales` | Sales generated (₹) |

**Size:** 8 records × 7 columns

---

## 🔍 Analysis Performed

1. Loaded dataset into a Pandas DataFrame
2. Inspected first/last rows, shape, dtypes, and null values
3. Generated summary statistics (`.describe()`)
4. Calculated average salary and total sales per department
5. Identified top-performing employee by sales
6. Detected salary outliers using the IQR method + boxplot
7. Visualized age distribution (histogram)
8. Visualized department-wise average salary (bar chart)
9. Plotted Experience vs. Salary (scatter plot with trend line)
10. Measured Salary–Sales correlation (Pearson's r)

---

## 📈 Key Findings

**Department Pay Gap**
Sales has the highest average salary (₹46,000), followed by HR (₹27,667) and IT (₹21,000) — the widest gap of any dimension in the dataset.

**Experience → Salary**
A clear positive trend links experience to salary. The most experienced employee (8 years) earns ₹55,000, the highest in the dataset — though one IT employee (4 yrs, ₹4,000 salary) is a notable exception worth a data-quality check.

**Salary–Sales Correlation**
r = 0.94 — a strong positive correlation, meaning higher-paid employees are also the highest sales performers.

**Outliers**
No statistical outliers detected in salary using the IQR method (bounds: ₹-8,625 to ₹72,375) — despite the ₹4,000 figure looking unusual at a glance, it falls within the calculated range given the small sample size.

**Age Profile**
Most employees fall between 27–32 years old — a young-to-mid-career workforce.

---

## 🛠️ Tools & Skills
`Python` `Pandas` `NumPy` `Matplotlib` `EDA` `IQR Outlier Detection` `Correlation Analysis`

---

## 🗃️ Repository Structure
```
employee-sales-eda/
│
├── data/
│   └── employee_sales_data.csv
│
├── notebooks/
│   └── EDA_Employee_Sales.ipynb
│
└── README.md
```

---

*Part of an ongoing data analytics portfolio — see profile README for more projects.*

