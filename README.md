# IPL Match Analytics – Powerplay Impact Study

## 📌 Problem Statement

In T20 cricket, it is widely believed that a strong start in the Powerplay (first 6 overs) significantly influences the final match result. 

This project aims to statistically evaluate whether winning the Powerplay increases the probability of winning an IPL match.

---

## 🎯 Objective

- Analyze IPL 2024 league-stage data.
- Identify team performance trends.
- Measure correlation between Powerplay winner and Match winner.
- Quantify win probability using structured data analysis.

---

## 📊 Dataset Overview

- IPL 2024 League Stage (10 Teams)
- 43-match subset used for Powerplay correlation analysis
- Data collected from official IPL scorecards and ESPNcricinfo

### Key Variables:
- Team
- Matches Played
- Wins
- Losses
- Powerplay Winner
- Match Winner

---

## 🧹 Data Cleaning & Preparation

The dataset was processed using Microsoft Excel:

- Removed no-result matches
- Standardized team abbreviations (KKR, CSK, SRH, etc.)
- Eliminated duplicate records
- Created derived categorical feature:
  
  → **"Same Winner"** (Powerplay winner = Match winner)  
  → **"Different Winner"** (Powerplay winner ≠ Match winner)

This ensured consistency and analytical accuracy.

---

## 📈 Analysis Methodology

1. Aggregated league-stage team performance
2. Calculated total wins per team
3. Compared Powerplay Winner vs Match Winner
4. Counted outcome frequencies
5. Computed win probability percentage
6. Visualized findings using bar charts and correlation graphs

---

## 🔍 Key Findings

- Kolkata Knight Riders (KKR) emerged as the most consistent team with 9 wins.
- Teams winning the Powerplay also won the match in **69.7% of cases**.
- This indicates a strong positive correlation between early momentum and match outcome.

---

## 📊 Visual Insights

- League team wins distribution
- Powerplay vs Match outcome correlation graph
- Comparative performance trends across teams

(Visualizations available in the `/visuals` directory.)

---

## 🛠 Tools Used

- Microsoft Excel (Advanced)
- Pivot Tables
- Conditional Logic (IF formulas)
- Data Cleaning Techniques
- Statistical Calculations
- Data Visualization

---

## 🧠 Analytical Interpretation

The results suggest that while overall league success depends on consistency, early-game dominance in the Powerplay phase significantly increases match win probability.

This reinforces the strategic importance of aggressive early-phase gameplay in T20 cricket.

---

## 📁 Repository Structure
data/

README.md

---

## 🚀 Future Scope

- Extend analysis using Python (Pandas, Matplotlib)
- Build predictive model for match outcome
- Include toss factor and venue-based bias
- Perform player-level performance analysis

---

## 📌 Conclusion

This project demonstrates how structured data analytics can validate sports hypotheses using statistical reasoning rather than intuition. 

It highlights the practical application of data cleaning, feature engineering, correlation analysis, and visualization in solving real-world analytical problems.
