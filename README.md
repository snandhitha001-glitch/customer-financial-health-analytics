# Financial Health Scoring & Customer Segmentation (Retail Banking)

## Problem Overview
Retail banks process large volumes of transactional data, yet often lack a **clear, interpretable view of customer financial health.** Reliance on isolated indicators such as balances or transaction counts makes it difficult to identify **financial stress, behavioral risk, and proactive intervention opportunities.**

This project delivers an **end-to-end financial health analytics solution** built on transactional behavior to:
* Quantify customer financial health using a **transparent, business-friendly scoring framework**
* Segment customers based on real financial behavior patterns
* Identify **high-risk accounts** requiring monitoring or intervention
* Present insights through an **executive-level Power BI dashboard**

This analysis is performed on a **simulated retail banking dataset modeled on Lloyds Banking Group customer behavior,** reflecting transaction patterns while maintaining strict data privacy standards.

The project mirrors **real-world data analyst and business analyst workflows** in a retail banking context, from data preparation to stakeholder-ready reporting.

## Data Source & Ethical Use
This project uses a **fully synthetic retail banking dataset modeled on Lloyds Banking Group customer behavior**.
* Contains **no real customer data** or personally identifiable information
* Designed to realistically reflect retail banking transaction and balance behavior
* Used exclusively for **educational and portfolio demonstration purposes**

This approach enables meaningful financial behavior analysis while aligning with **data governance, privacy, and ethical standards** expected in financial services.

## Business Objectives
* Detect financially at-risk customers early using transactional behavior signals
* Translate complex financial data into **clear, explainable insights** for business stakeholders
* Segment customers to support targeted monitoring and engagement strategies
* Enable leadership to track financial health trends and risk exposure over time

## Analytical Approach
### Data Understanding & Preparation
* Cleaned and standardized transaction-level data
* Addressed missing values and inconsistent account identifiers
* Aggregated transactions to a monthly account-level view
* Engineered core financial metrics (inflows, outflows, net cash flow, volatility)
**Outcome**: An analysis-ready behavioral dataset suitable for scoring and segmentation.

### Behavioral Feature Engineering
Developed key indicators that capture *how* customers manage their finances:
* Transaction frequency and consistency
* Net cash flow trends over time
* Balance volatility and stability
* Persistent low-balance behavior
**Why this matters:** These features focus on **financial behavior**, not just static snapshots, enabling more meaningful risk identification.

### Financial Health Scoring Framework
Designed an **interpretable, rule-based financial health scoring model** aligned with business logic and regulatory transparency.

The score combines normalized indicators across multiple dimensions:
* Balance stability
* Cash flow health
* Transaction activity
* Volatility
* Persistent low-balance patterns

Each account is assigned:
* A **numeric financial health score**
* A **categorical label**: *At-Risk, Moderate or Healthy*

This approach prioritizes interpretability and stakeholder trust over black-box modeling.

### Customer Segmentation
Segmented accounts using aggregated behavioral metrics, including:
* Transaction activity levels
* Cash flow patterns
* Average balance behavior
* Volatility and spending diversity
**Key Segments Identified:**
* **Financial Strained** - Persistent low balances, negative cash flow, elevated risk
* **Stable Low-Engagement** - Low volatility and risk, but limited financial activity
These segments help explain *why* customers are at risk, not just *whether* they are.

### Master Analytics Table & Reporting Layer
Consolidated:
* Financial health scores
* Customer segments
* Monthly behavioral metrics
Into a single **Master Analytics Table** optimized for reporting and dashboarding.

Generated executive-level KPIs such as:
* At-risk customer rate
* Average financial health score
* Balance and cash flow trends

### Power BI Dashboard
Developed an interactive **executive dashboard** to support strategic decision-making.

**Key Views**
* Financial health score distribution
* Customer segmentation overview
* At-risk accounts by segment
* Net cash flow vs. balance behavior
* Financial health trends over time
* High-risk account shortlists for action

**Dashboard Capabilities**
* Segment and health category slicers
* Time-based filtering
* Drill-down analysis
* Clean, business-aligned visual design optimized for executive decision-making

### Key Insights
* Over **65% of accounts** fall into *At-Risk* or *Moderate* health categories
* Financially strained customers consistently exhibit negative cash flow and low balances
* Stable low-engagement customers show low volatility but limited financial movement

### Decision Support Use Cases
This analystis enables stakeholders to:
* Identify customers requiring proactive financial wellness outreach
* Priortize monitoring of the high-risk behavioral segments
* Track changes in financial health over time at a portfolio level
* Support policy, engagment, or risk review discussions with data-backed insights

## Tools & Technologies
* **Python** (Pandas, NumPy, Scikit-learn)
* **PowernBI** (data modeling, DAX, dashboard design)
* **Jupyter Notebook**
* **Git & GitHub**

## Business Impact & Next Steps
In real retail banking environment, this solution could:
* Support early warning systems for financial distress
* Enable targeted customer engagement strategies
* Feed downstream risk monitoring or decision-support workflows

**Future Enhancements**
* Introduce alerts for sudden behavioral changes
* Track financial recovery following interventions

### Author
Nandhitha Sivakumar
Focused on analytics-driven business decision-making
