# 📝 Amazon checkout redesign: Impact Analysis

## 🌟 Highlights
From this project "Amazon checkout redesign: Impact Analysis", the highlights are addressed as:
### Conclusion summary
- Lift analysis: 6.386% relative lift at started_checkout and 14.839% relative lift at purchased
- Funnel analysis: Modified checkout process affects customer behavior at started_checkout (1.3% delta) and purchased step (1.4% delta)
- Revenue analysis:
  - Significant difference in order value with 95% confidence level
  - Higher distribution of order value at 30~60 region at treatement group
  - Considering customers who order, lift of order value by group is 13.35%
- Segment analysis
  - No strong dependency between categorical factors and target columns with 95% confidence level and Camer's V analysis
- Conversion analysis: Significant difference at started_checkout and purchased with 95% confidence

### Final busincess decision
- Observed siginificant improvement in lift and conversion rate gain. As a result, it reflects at the significant revenue gain
- Based on pov of significant gain above, suggest to roll out the modified checkout process
- Other open questions might affect final business decision
  - Man power perspective. How much resource is needed to roll out the process ?
  - Cost perspective. How much is the cost to roll out the process 

## ℹ️ Project Introduction
In this Amazon e-commerse system, company currently has the orginal checkout process for a long time. Company is now considering another modified version of checkout process and wondering whether the new checkout process is better than orginal checkout process in terms of conversion rate and revenue gain. In order to judge the result statistically instead of blindly, A/B test is commonly used methodology to make decision in "data driven approach".

## 🎯 Mission & Goal
Given by the csv file including many information, such as grouping, user information, and the corresponding behavior at purchase journey, I need to use statistical approach (A/B testing in this case) to jduge whether modified version of checkout process is statistically better than orginal process. As a result, decision should be made to suggest or not suggest this change and the reason behind.  
**Disclaimer: the used data in this project is synthetic data created by ChatGPT (GPT-5.5)**

## 🏭 Project structure
- Import libraries
- Data inspection & Data cleaning
- EDA
- Lift analysis
- Funnel analysis
- Revenue analysis (t test)
- Segment analysis (chi square test)
- Conversion rate analysis (z test)
- Final business decision
