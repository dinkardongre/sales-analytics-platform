# 📊 **Sales Data Analysis Platform**

### **Tech Stack:**

**Python · Pandas · Dask · Polars · NumPy · Matplotlib · Seaborn · Excel Automation**

This project demonstrates a **scalable end-to-end sales analytics pipeline** capable of processing both small and large multi-month transactional datasets. It includes  **data cleaning** ,  **feature engineering** ,  **exploratory data analysis (EDA)** ,  **customer segmentation** , and **automated reporting** using modern data-processing libraries.

The notebook in this repo replicates the exact workflow mentioned in my resume and can serve as a portfolio-ready demonstration of retail analytics skills.

---

# 🚀 **Project Highlights**

### ✅ **1. Scalable Data Processing**

* Used **Pandas** for fast in-memory transformations
* Used **Dask** for parallel processing of large CSVs
* Used **Polars LazyFrame** for ultra-fast query optimization
* Supports multi-million row datasets

### ✅ **2. End-to-End Data Pipeline**

Includes:

* Data loading & validation
* Cleaning & handling missing values
* Feature engineering for analytics
* Time-based transformations
* Automated exports (Excel, CSV)

### ✅ **3. Business-Driven Analytics**

Performed analysis such as:

* Monthly revenue trends
* Top products & categories
* Customer segmentation ( **RFM** )
* **Cohort retention analysis**
* Discount impact analysis
* Basket value & order behavior insights

### ✅ **4. Automated Reporting**

Generates:

* **Multi-sheet Excel report** (revenue, segmentation, cohorts)
* Visual dashboards using Matplotlib & Seaborn
* Reproducible results for any dataset

---

# 📁 **Repository Structure**

<pre class="overflow-visible!" data-start="1904" data-end="2266"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre!"><span><span>📦 sales-data-analysis-platform
│
├── 📘 sales_analysis.ipynb        </span><span># Main Jupyter Notebook</span><span>
├── 📄 sales.csv                   </span><span># Sample dataset (1000 rows)</span><span>
├── 📄 requirements.txt            </span><span># Required libraries</span><span>
├── 📄 README.md                   </span><span># Project documentation</span><span>
│
└── 📂 reports/
    ├── sales_report.xlsx          </span><span># Auto-generated Excel output</span><span>
</span></span></code></div></div></pre>

---

# 🧩 **Features in the Notebook**

### **1. Data Cleaning**

* Convert `order_date` to datetime
* Fill missing city & gender
* Drop null price/quantity
* Normalize city names (Bangalore → Bengaluru)
* Remove duplicates

### **2. Feature Engineering**

* `total_amount = quantity × price`
* `discount_amount = price × discount / 100`
* `final_price = price - discount_amount`
* Extract Year, Month, Day
* Create **Age Groups**
* Customer Value Flag (High-value > ₹50,000)

### **3. Exploratory Data Analysis**

* Most common cities
* Popular categories & products
* Price statistics
* Gender-wise spending
* Category & city revenue comparison
* Discount patterns

### **4. Time Series Analytics**

* Daily revenue
* Weekly revenue
* Monthly order volume
* Highest revenue day

### **5. Customer Analytics**

* Top spenders
* Unique categories purchased
* Repeat customers
* RFM Segmentation
* Cohort Retention Matrix

### **6. Advanced EDA**

* Pivot tables (category vs gender)
* Filtering using `.query()`
* Encoding categorical variables

---

# 🛠 **How to Run the Project**

### **1️⃣ Clone the repository**

<pre class="overflow-visible!" data-start="3466" data-end="3584"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>git </span><span>clone</span><span> git clone https://github.com/dinkardongre/sales-analytics-platform.git
</span><span>cd</span><span> sales-data-analysis-platform
</span></span></code></div></div></pre>

### **2️⃣ Install dependencies**

<pre class="overflow-visible!" data-start="3619" data-end="3662"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>pip install -r requirements.txt
</span></span></code></div></div></pre>

### **3️⃣ Launch Jupyter Notebook**

<pre class="overflow-visible!" data-start="3700" data-end="3728"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>jupyter notebook
</span></span></code></div></div></pre>

### **4️⃣ Open and Run:**

<pre class="overflow-visible!" data-start="3756" data-end="3784"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre!"><span><span>sales_analysis.ipynb
</span></span></code></div></div></pre>

---

# 📈 **Results & Insights**

This analysis reveals:

* Revenue peaks during specific months
* Category contribution is highly skewed
* A few customers contribute disproportionately high revenue
* Discount patterns significantly affect final price
* Strong customer retention patterns across months
* RFM segmentation separates loyal, at-risk, and new customers

---

# 🙋‍♂️ **About the Project**

This project is designed as:

* A real-world analytics workflow
* A resume-supported portfolio project
* A demonstration of scalable data handling
* A reusable template for any sales dataset

---

# ⭐ **If you like this project, consider giving it a star!** ⭐
