# 🧠 Teen Mental Health & Social Media — Analytics Project

> A comprehensive data analytics project examining the relationship between social media usage, sleep, physical activity, and mental health outcomes across 1,200 teenagers aged 13–19.

---

## 📌 Project Overview

This project performs end-to-end data analysis on a Teen Mental Health dataset, covering:
- Data validation, cleaning & quality assurance
- KPI generation across demographics
- Behavioral pattern detection
- Risk profiling and anomaly flagging
- Professional Excel & interactive HTML dashboard outputs

---

## 📊 Dataset Summary

| Attribute | Detail |
|---|---|
| **Records** | 1,200 teens |
| **Age Range** | 13–19 years |
| **Variables** | 13 (+ 5 engineered) |
| **Missing Data** | 0% |
| **Duplicates** | 0% |
| **Platforms Covered** | Instagram, TikTok, Both |

---

## 🔑 Key Findings

### 🔴 Depression Threshold at Stress Level 7+
Every single depressed teen in the dataset had a stress score of **7 or above**. Zero depressed cases were recorded at stress levels 1–6. This provides a clear, data-backed **early screening threshold**.

### 😴 Widespread Sleep Deficit
- Average sleep: **6.45 hours** (recommended: 8–10h)
- **240 teens (20%)** sleep fewer than 5 hours per night
- Pre-sleep screen time averages **2 hours/night**

### 📱 Duration Beats Platform
Instagram, TikTok, and combined users showed **nearly identical** stress, anxiety, and depression rates. The risk driver is **how long**, not **where**.

### 🎮 Addiction is the Top Risk Metric
Average addiction score: **5.56 / 10** — the highest across all measured variables. Ages 17–19 carry the heaviest burden.

### ⚡ Ages 15–16: Highest-Risk Cohort
- Depression rate: **3.50%** (highest of all age groups)
- Avg. anxiety: **5.79 / 10** (highest of all age groups)

### 🏃 1 in 10 Teens: Zero Physical Activity
34 teens (2.8%) report zero physical activity, compounding mental health risk when combined with high screen time.

---

## 🛠️ Tools & Methodology

```python
# Core Stack
- Python 3
- Pandas        # Data wrangling & KPI computation
- NumPy         # Numerical operations
- OpenPyXL      # Excel report generation
- HTML/CSS/JS   # Interactive dashboard
```

**Pipeline:**
1. Data ingestion & profiling
2. Cleaning & standardization
3. Feature engineering (age groups, risk scores, flags)
4. KPI computation by gender, platform, age group, social interaction
5. Anomaly detection (low sleep, zero activity)
6. Excel + HTML output generation

---

## 📁 Outputs

| File | Description |
|---|---|
| `Teen_Mental_Health_Analytics_Report.xlsx` | 5-sheet Excel report: Dashboard, Clean Data, KPIs, Anomalies, Insights |
| `Teen_Mental_Health_Analytics_Report.html` | Fully interactive dark-theme dashboard |

---

## 💡 Recommendations

| Priority | Action |
|---|---|
| 🥇 High | Implement stress-level screening (flag ≥ 7) in school health programs |
| 🥇 High | Launch sleep hygiene awareness campaigns targeting ages 15–16 |
| 🥈 Medium | Promote physical activity as a primary mental health intervention |
| 🥈 Medium | Educate on **screen time duration** — not platform type |
| 🥉 Lower | Develop addiction-awareness programs for 17–19 age group |

---

## 📈 KPI Snapshot

```
Total Records          : 1,200
Depression Rate        : 2.58%  (31 teens)
Avg. Stress Level      : 5.49 / 10
Avg. Anxiety Level     : 5.06 / 10
Avg. Addiction Level   : 5.56 / 10  ← Highest metric
Avg. Sleep Hours       : 6.45h      ← Below recommended
Avg. Social Media/Day  : 4.54h
Flagged Anomalies      : 261 records
```

---

## 🤝 Connect

If you work in **education, public health, policy, or youth development**, feel free to open an issue or reach out — data-driven decisions can genuinely improve outcomes for the next generation.

---

*Built with Python · Pandas · OpenPyXL · HTML/CSS/JS*
