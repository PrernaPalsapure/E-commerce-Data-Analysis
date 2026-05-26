# 📊 E-Commerce Data Analysis & Insights

> Transforming raw e-commerce transaction data into actionable business insights using interactive dashboards and statistical analysis.

## 📋 Table of Contents

- [Overview](#overview)
- [Key Metrics](#key-metrics)
- [Dataset](#dataset)
- [Analysis Performed](#analysis-performed)
- [Key Findings](#key-findings)
- [Visualizations](#visualizations)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)
- [Key Insights & Recommendations](#key-insights--recommendations)
- [Author](#author)

---

## 🎯 Overview

This project analyzes a comprehensive e-commerce dataset spanning 2010-2011, uncovering critical patterns in **customer behavior**, **product performance**, and **sales trends**. The interactive Tableau dashboard enables data-driven decision-making for business optimization.

**Business Problem:** Understanding which products drive revenue, identifying seasonal patterns, and optimizing inventory & marketing strategies.

**Solution:** Built a multi-layered analytics dashboard with 5 interactive visualizations revealing actionable insights.

---

## 📊 Key Metrics

| Metric | Value |
|--------|-------|
| **Total Revenue** | $10.6M |
| **Total Transactions** | 10,000+ |
| **Unique Customers** | 4,340 |
| **Average Order Value** | $527.50 |
| **Revenue Growth** | 160% (Jan → Dec) |
| **Top Product Market Share** | 30% (Paper Craft) |
| **Data Period** | 2010-2011 |

---

## 📁 Dataset

### Data Source
- **Type:** E-commerce transaction records
- **Records:** 10,000+ transactions
- **Time Range:** January 2010 - December 2011
- **Granularity:** Individual order level
- **Format:** CSV (Structured data)

### Data Fields
```
- Invoice Date: Transaction timestamp
- Product Name: Item sold
- Quantity: Units ordered
- Unit Price: Price per unit
- Total Amount: Revenue per transaction
- Customer ID: Unique customer identifier
- Product Category: Classification (Craft, Home, etc.)
```

---

## 🔍 Analysis Performed

### 1. **Descriptive Analysis**
- Revenue aggregation by month and product
- Customer count and transaction volume
- Average order value calculations
- Product popularity ranking

### 2. **Trend Analysis**
- Monthly revenue patterns
- Seasonality identification
- Year-over-year growth calculation
- Peak season identification

### 3. **Product Performance Analysis**
- Top 10 products by quantity sold
- Revenue contribution by product
- Product category breakdown
- Sales velocity analysis

### 4. **Customer Segmentation**
- Customer clustering by purchase behavior
- Order value distribution
- Customer lifetime value estimation
- Repeat purchase analysis

### 5. **Statistical Insights**
- Growth rate calculations
- Seasonal decomposition
- Trend identification
- Outlier detection

---

## 💡 Key Findings

### 🔴 Finding 1: Strong Seasonality Effect
**Observation:** Revenue peaks in December ($1.3M) and dips in March-May (~$500K)

**Why It Matters:** 
- Q4 (holiday season) drives 30% of annual revenue
- Q2-Q3 represents untapped opportunity

**Business Action:**
- Increase inventory in October-November
- Run promotions in Q2-Q3 to smooth demand
- Plan staffing based on seasonal surges

---

### 🔴 Finding 2: Product Concentration Risk
**Observation:** Top 3 products drive 50% of revenue; Paper Craft alone = 30%

**Why It Matters:**
- Revenue depends heavily on few products
- Risk if supply chain breaks down
- Opportunity to cross-sell and diversify

**Business Action:**
- Develop backup suppliers for top products
- Invest marketing in Paper Craft (proven winner)
- Launch campaigns to promote underperforming products
- Analyze what makes Paper Craft successful

---

### 🔴 Finding 3: Consistent Customer Spending
**Observation:** Average order value remains stable at $527.50 throughout year

**Why It Matters:**
- Customer purchasing power doesn't change seasonally
- No evidence of successful upselling
- Retention matters more than discount-driven growth

**Business Action:**
- Focus on customer retention (reduce churn)
- Implement loyalty programs
- Test bundling strategies (multiple products)
- Analyze repeat purchase rate

---

### 🔴 Finding 4: Growth Trajectory
**Observation:** 160% revenue growth from January ($500K) to December ($1.3M)

**Why It Matters:**
- Business is clearly growing
- This growth is expected (seasonal) not organic
- Baseline expectations set for next year

**Business Action:**
- Plan inventory for sustained growth
- Set performance targets based on last year
- Invest in systems to handle scaling

---

### 🔴 Finding 5: Customer Segmentation Opportunity
**Observation:** Customer segments cluster into distinct groups by purchase value

**Why It Matters:**
- Different customers need different strategies
- High-value customers deserve VIP treatment
- Low-value customers represent growth opportunity

**Business Action:**
- Create tiered loyalty program
- Personalize marketing by segment
- Identify what high-value customers have in common

---

## 📊 Visualizations

The Tableau dashboard includes 5 interactive views:

### 1. **Sales Trends Over Time** (Line Chart)
- Shows monthly revenue patterns
- Identifies seasonality clearly
- Date range filter for custom analysis
- **Use Case:** Track performance over time, spot trends

### 2. **Total Revenue KPI Card**
- At-a-glance business health metric
- Highlights total value generated
- Updates with dashboard filters
- **Use Case:** Executive briefing, quick reference

### 3. **Average Order Value KPI Card**
- Shows customer spending consistency
- Indicates pricing strategy success
- Benchmarking metric
- **Use Case:** Monitor customer quality, pricing impact

### 4. **Total Customers KPI Card**
- Tracks customer base growth
- Combined with revenue = efficiency metric
- Revenue per customer indicator
- **Use Case:** Growth tracking, acquisition analysis

### 5. **Top 10 Products by Quantity** (Horizontal Bar Chart)
- Visual product performance ranking
- Paper Craft clearly dominates
- Easy comparison of volume leaders
- **Use Case:** Inventory planning, marketing prioritization

### 6. **Monthly Revenue Breakdown** (Line Chart)
- Detailed month-by-month performance
- Seasonality visualization
- Trend identification
- **Use Case:** Quarterly planning, performance review

### 7. **Customer Segmentation** (Bubble Chart)
- Shows customer distribution by purchase value
- Identifies market segments
- Visual clustering patterns
- **Use Case:** Customer targeting, segment analysis

---

## 🛠️ Technologies Used

### Data Analysis & Visualization
- **Tableau** - Interactive dashboard creation
- **Python (Pandas, NumPy)** - Data cleaning and preprocessing

### Data Processing
- **Python Libraries:**
  - `pandas` - Data manipulation and aggregation
  - `numpy` - Numerical calculations
  - `matplotlib` / `seaborn` - Statistical visualization

### Version Control
- **Git & GitHub** - Code repository management

### Documentation
- **Markdown** - README and documentation
- **Jupyter Notebook** - Analysis notebooks

---

## 📂 Project Structure

```
E-commerce-Data-Analysis/
│
├── README.md                                    # This file
├── LICENSE                                      # MIT License
│
├── data/
│   └── data.csv                                # Raw e-commerce transaction data
│
├── dashboards/
│   ├── E-COMMERCEproject.twbx                  # Tableau workbook (interactive)
│   └── Dashboard_Screenshots/                  # Dashboard screenshots for reference
│
├── analysis/
│   ├── PROJECT_(2).ipynb                       # Python analysis notebook
│   └── data_cleaning_notes.txt                 # Data quality notes
│
└── documentation/
    ├── DATA_DICTIONARY.md                      # Field explanations
    ├── METHODOLOGY.md                          # Analysis approach
    └── INSIGHTS_SUMMARY.md                     # Key findings detailed
```

---

## 🚀 How to Use

### Option 1: View Interactive Dashboard (Recommended)
1. Download the `E-COMMERCEproject.twbx` file
2. Open in **Tableau Desktop** or **Tableau Public**
3. Use interactive filters to explore data
4. Click on charts to drill down into details

### Option 2: View Analysis in Jupyter Notebook
1. Open `PROJECT_(2).ipynb`
2. Run cells sequentially
3. See data cleaning steps and analysis code
4. Examine visualizations with annotations

### Option 3: Access Raw Data
1. Load `data.csv` into your analysis tool
2. Data is structured and ready for analysis
3. Follow the data dictionary for field definitions

---

## 💼 Key Insights & Recommendations

### Priority 1: Inventory & Supply Chain Optimization
**Action:** Plan inventory for Q4 surge
- Increase Paper Craft stock by 40% in Oct-Nov
- Establish backup suppliers for top 3 products
- Implement just-in-time delivery for slow-moving items
- **Expected Impact:** Reduce stockouts by 30%, improve cash flow

### Priority 2: Marketing & Demand Management
**Action:** Launch targeted campaigns for Q2-Q3
- Run promotions on underperforming products (March-May dip)
- Create bundle deals to increase AOV (average order value)
- Develop email campaigns targeting high-value customer segment
- **Expected Impact:** Smooth revenue across year, reduce seasonal dip

### Priority 3: Product Strategy
**Action:** Investigate Paper Craft success
- Conduct competitive analysis (why is it #1?)
- Identify key features driving demand
- Develop similar products in other categories
- **Expected Impact:** Increase market share, launch successful products

### Priority 4: Customer Retention
**Action:** Build loyalty program
- Create tiered rewards for repeat customers
- Develop VIP treatment for high-value customers
- Implement email nurture sequences
- **Expected Impact:** Increase repeat purchase rate, reduce churn

---

## 📈 Methodology

### Data Cleaning Process
1. ✅ Loaded 10,000+ records
2. ✅ Checked for missing values (handled appropriately)
3. ✅ Removed duplicate transactions
4. ✅ Standardized date formats
5. ✅ Validated numerical fields
6. ✅ Confirmed data integrity

### Analysis Approach
1. **Descriptive:** What happened? (KPIs, totals)
2. **Exploratory:** Why did it happen? (trends, patterns)
3. **Diagnostic:** What caused it? (correlations, segments)
4. **Predictive:** What will happen? (forecasts, outlooks)

### Visualization Best Practices Applied
- ✅ Appropriate chart types for data
- ✅ Clear titles and labels
- ✅ Color-blind friendly palette
- ✅ Interactive filters for exploration
- ✅ Consistent design language

---

## 🎓 Learning Outcomes

This project demonstrates:
- ✅ **Data Cleaning:** Handling messy real-world data
- ✅ **Analytics:** Extracting meaningful insights
- ✅ **Visualization:** Communicating findings clearly
- ✅ **Business Thinking:** Connecting data to action
- ✅ **Dashboard Design:** Creating interactive user experiences
- ✅ **Statistical Analysis:** Identifying patterns and trends

---

## 🤝 Contributions

This is a portfolio project. Feedback and suggestions are welcome!

If you find insights or have recommendations:
1. Open an Issue with your findings
2. Include data, analysis, and proposed action
3. Reference specific dashboard elements

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You're free to use this analysis for learning and reference.

---

## 👤 Author

**Prerna Palsapure**

- 📧 Email: preranapalsapure@gmail.com
- 💼 LinkedIn: [linkedin.com/in/prerna-palsapure-3881b8347](https://linkedin.com/in/prerna-palsapure-3881b8347)
- 🐙 GitHub: [github.com/PrernaPalsapure](https://github.com/PrernaPalsapure)

**About Me:**
Data Analyst with 9 months of internship experience at AI Variant. Passionate about transforming data into actionable insights. Building projects that create real business value.

---

## 📞 Questions & Support

Have questions about the analysis or want to discuss the insights?

- **GitHub Issues:** Open an issue in the repo
- **Email:** preranapalsapure@gmail.com
- **LinkedIn:** Connect and message me

---

## 🎯 Related Projects

Check out my other portfolio projects:

- **[Zomato Food Delivery Dashboard]([https://github.com/PrernaPalsapure](https://github.com/PrernaPalsapure/zomato-sales-dashboard-excel))** - 120K+ records analyzed
- **[Car Price Prediction]([https://github.com/PrernaPalsapure](https://github.com/PrernaPalsapure/Used_Car_Price_Prediction))** - Machine learning model (R² 0.81)
- **[Heart Failure Survival Prediction]([https://github.com/PrernaPalsapure](https://github.com/PrernaPalsapure/heart-failure-survival-prediction))** - Medical ML model (84% accuracy)

---

## ⭐ If You Found This Helpful

- ⭐ Star this repository
- 👀 Watch for updates
- 🔗 Share with others learning data analytics

---

**Last Updated:** May 2026

**Status:** ✅ Analysis Complete | 📊 Dashboard Interactive | 📖 Documentation Complete

---

### Thank You! 🙏

Thank you for exploring this data analysis project. I hope the insights and methodology prove useful for your work or learning journey.

Happy analyzing! 📊✨
