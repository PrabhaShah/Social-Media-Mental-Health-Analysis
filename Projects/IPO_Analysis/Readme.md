📊 **IPO Analysis: Understanding Listing-Day Behavior in Indian IPOs**

📌 **Project Overview**

- IPO investments are often driven by headline indicators such as subscription multiples and short-term market enthusiasm. However, these signals are frequently
  interpreted without sufficient context, leading to decisions based more on hype than evidence.
- This project analyzes recently listed IPOs in India to understand how pre-listing demand, issue characteristics, and IPO type (SME vs Mainline) relate to
  listing-day price behavior. The focus is on uncovering patterns and structural differences, not on prediction or stock recommendations.

🎯 **Objectives**

- Examine whether IPO subscription levels meaningfully explain listing-day performance
- Compare behavioral differences between SME and Mainline IPOs
- Analyze listing-day dynamics to distinguish market excitement from price discovery
- Provide investor-relevant insights grounded in data rather than heuristics

🔍 **Key Questions Explored**

1️) **Does IPO subscription meaningfully predict listing performance?**_

  - Is higher subscription associated with higher listing gains?
  - Do extremely high subscriptions outperform moderate ones?
  - Are there diminishing returns to IPO hype?

2️) **Do SME and Mainline IPOs behave differently?**_

  - Which segment exhibits higher volatility?
  - How does subscription impact each segment differently?
  - Do SME IPOs experience sharper intraday corrections?

📂 **Dataset Description**

  - Each record represents a single IPO and includes: IPO name and classification (SME / Mainline)
  - Issue details (issue size, issue price)
  - Demand indicator (total subscription)
  - Listing-day metrics (opening price, closing price, listing gains)
  - Early post-listing indicators (LTP, today’s gain where available)

**Note:** 
- The dataset is refreshed from publicly available sources on each run.
- Missing values are retained where IPOs are newly listed or not yet traded, as these reflect lifecycle stages rather than data quality issues.

🧠 **Methodology**
  1) The analysis follows a structured, transparent approach:
    - Data Quality Checks
    - Missing values
    - Duplicate records
    - Outlier assessment
    - Statistical summaries

  2) Exploratory Data Analysis (EDA)
     - Distribution of issue size, subscription, and pricing
     - Segmentation by IPO type (SME vs Mainline)

  3) Core Analysis
     - Subscription vs listing gains
     - Diminishing returns to oversubscription
     - Listing-day behavior (opening vs closing prices)
     - Intraday correction analysis
     - Comparative analysis across IPO types

  4) Synthesis
     - Investor-oriented interpretation

  5) Clear articulation of patterns and limitations

📈 **Key Insights**
    - IPO subscription is most predictive of opening-day excitement, not sustained performance
    - Extremely high subscription levels show diminishing returns
    - SME IPOs exhibit higher volatility and sharper intraday corrections
    - Mainline IPOs demonstrate greater stability and more efficient price discovery
    - Listing-day closing prices provide stronger signals than opening gaps
    - Subscription reflects attention, not conviction.

🧠 **Investor Takeaways**

    - Subscription should be treated as a contextual signal, not a decision rule
    - SME and Mainline IPOs require different evaluation logic
    - Strong opening gains often precede intraday correction
    - Moderate demand combined with stable price discovery may be preferable to extreme hype

**This project does not provide buy or sell recommendations.
It provides a framework for thinking clearly about IPO behavior.**

⚠️ **Limitations**

    - The dataset represents a snapshot of recent IPOs, not full historical coverage
    - Client-side rendering on the source platform limits dataset size
    - Analysis focuses on short-term listing behavior, not long-term performance
    - External sentiment and macroeconomic factors are not included

🛠️ **Tools & Technologies**

      - Python
      - Pandas, NumPy
      - Matplotlib, Seaborn
      - Jupyter Notebook
