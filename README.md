# Netflix-churn-DA

### 📁 Netflix Churn Analysis

**Project Overview**
This project involved a comprehensive analysis of Netflix user churn using two key data sources: a multi-year subscription trend chart and detailed Excel data on user joins, cancels, retention status, and viewing behavior. The goal was to understand patterns in subscription growth and churn, identify inconsistencies, and suggest actionable improvements for user retention strategies. The project also explored data visualization accuracy and user engagement insights.

**Tools & Technologies Used**

* Microsoft Excel (Formulas, PivotTables, Conditional Formatting, Charts)
* Visual and trend analysis
* Data filtering and quality validation

**Data Understanding and Preparation**
The analysis drew from two sources:

1. A monthly chart showing joins and cancels from Dec 2019 to Dec 2024.
2. An Excel dataset with detailed user-level info like plan type, weekly hours viewed, and retention status.

The chart showed inconsistencies, such as:

* Decimal values for cancels (e.g., 2,025.5496), which should be integers.
* A missing month (April 2023).
* Different Y-axis intervals (Joins: 1,000; Cancels: 2,000), skewing the visual interpretation.
* A data drop-off in December 2024.

[Watch here](https://www.loom.com/share/9f433601085846379b1709fb9bda0b63?sid=cb1c0110-1057-486f-b097-3038e714d3a6)

The Excel file had over 1,300 rows with null or zero values in weekly viewing hours. These were filtered out before deeper analysis.

**Key Insights and Errors Identified**

* **Joins vs. Cancels**: Joins began to consistently exceed cancels in mid-2023, indicating user growth.
* **September 2023 Issue**: Joins were 3,562 and cancels 2,025, yet the chart visually misrepresented this difference.
* **Data Accuracy**: Inconsistent formatting (e.g., decimals in cancels), and inclusion of future/incomplete data (Dec 2024) affected reliability.
* **Viewer Behavior**: Some users with low IMDB-rated titles still had high weekly hours viewed. Others had 0 hours, suggesting dormant accounts.

**Impact & Business Insight**
Correcting these issues revealed a much more positive growth trajectory for Netflix post-2023. Joins consistently surpassed cancels, particularly after mid-2023, suggesting improved customer acquisition or retention strategies. At the user level, segmentation based on weekly viewing and retention status allowed clearer identification of loyal vs. at-risk users. This dual-layered insight can help Netflix tailor retention campaigns, optimize content strategies, and improve user experience.

**Conclusion**
This project strengthened my skills in identifying and correcting misleading visuals, interpreting user behavior patterns, and connecting macro trends (Joins vs Cancels) with micro-level engagement (hours viewed per user). It reinforced the importance of accurate data representation and layered analysis in driving better business decisions.

---

### 📅 Netflix Churn Analysis – Key Insights & Recommended Actions

* **Joins consistently surpassed cancels** after mid-2023, signaling a shift toward net subscriber growth.
* **Visual misrepresentation** in the original chart (due to dual-axis scaling and formatting issues) could lead to incorrect strategic decisions.
* **Viewer engagement and retention** do not always correlate with title quality (based on IMDB ratings), suggesting Netflix should focus on actual behavior over subjective ratings.
* **High number of dormant users** with 0 weekly hours viewed present a churn risk and may require targeted re-engagement.
* **Actions Netflix could take:**

  * Standardize data formats to prevent analytical errors.
  * Rebuild churn visuals using single-axis or normalized charts.
  * Use viewing behavior as a predictive feature for churn models.
  * Create retention strategies focused on users with declining engagement.
  * Filter out unreliable future data (e.g., Dec 2024) for accurate trend modeling.

---
