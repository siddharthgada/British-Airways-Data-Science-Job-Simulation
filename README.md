# ✈️ British Airways Data Science Virtual Experience – Forage
A data science project completed as part of the British Airways Job Simulation on Forage. This project simulates real-world airline business challenges and demonstrates how data science can support customer experience, operational decisions and targeted marketing. This experience involved analyzing airline customer data to deliver actionable insights in two key areas:
1. Lounge Eligibility Estimation using Excel
2. Predictive Modeling to forecast customer booking behavior

📌 Project Overview
The objective of this simulation was to analyze customer behavior and use predictive modeling to help British Airways optimize lounge usage and improve marketing strategies.

📂 Project Breakdown <br>
Part 1: 🧾 Lounge Occupancy Estimation (Excel)
Objective: Estimate how many passengers are likely to use airport lounges based on flight types and eligibility criteria.

Steps:
  - Categorized flights using pivot tables based on route type, destination region, and time of day.
  - Applied estimated eligibility percentages across categories to forecast lounge usage.

Output:
  - Excel file with clearly structured categories and forecasted usage
  - Recommendations for reallocating lounge capacity to better match expected demand

Part 2: 🤖 Predicting Holiday Bookings (Machine Learning)
Objective: Predict which customers are likely to book a holiday to support targeted marketing.

Steps:
  - Preprocessed and explored customer booking data
  - Used one-hot encoding for categorical features
  - Trained a Random Forest Classifier using cross-validation
  - Evaluated using accuracy and other classification metrics
  - Interpreted feature importance to identify booking drivers

Results:
  - Model Accuracy: 85%
  - Top Feature: Purchase Lead (Time between the purchase and departure)
  - Created a PowerPoint slide to present results and business implications for manager

  📊 Technologies Used:
1. Python (pandas, scikit-learn, matplotlib, seaborn)
2. Excel (pivot tables, formulas)
3. Jupyter Notebook
4. PowerPoint (for stakeholder presentation)

📌 Project Summary
🔍 Key Findings:
  - Lounge occupancy estimation revealed that certain flight categories (e.g., long-haul international or premium routes) had significantly higher lounge usage potential.<br>
  - The predictive model achieved 85% accuracy, indicating strong ability to identify patterns in booking behavior.<br>
  - Feature importance analysis revealed that flight destination, booking origin, and flight timing were major predictors of booking likelihood.<br>
  - Precision was moderate (0.505), but recall was low (0.137) — the model correctly identified only a small portion of actual bookers.<br>

✅ Recommendations:
  - I suggest adding more customer-centric features to improve recall and capture more potential bookers for proactive outreach.<br>
