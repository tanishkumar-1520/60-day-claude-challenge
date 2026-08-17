# Day 17 – Vehicle Cost Analysis Dashboard

## 🚗 Project Overview

Created a **Vehicle Cost Analysis Dashboard** using a CSV dataset and Claude AI.

The dashboard analyzes fuel costs, CO₂ emissions, maintenance expenses, refueling/recharging time, vehicle age, and E85 economics.

## 🎯 Objectives

* Analyze vehicle running costs by fuel type.
* Calculate average cost per kilometer.
* Compare CO₂ emissions across different fuel types.
* Analyze maintenance cost per kilometer.
* Compare vehicle costs across different age groups.
* Evaluate E85 fuel economics.
* Calculate E85 break-even fuel price.
* Generate an E85 score based on cost, CO₂, refueling time, and maintenance.
* Present all insights through an interactive HTML dashboard.

## 🛠️ Tools & Technologies

* Claude AI
* CSV Dataset
* HTML
* CSS
* JavaScript
* SVG Charts
* GitHub
* Browser Developer Tools

## 📊 Dashboard Features

The dashboard includes:

1. **KPI Cards**

   * Fuel cost/km
   * E85 cost/km
   * E85 premium vs Petrol
   * Break-even price
   * Monthly fuel cost

2. **Fuel Cost Comparison**

   * SVG bar chart comparing cost/km for each fuel type.

3. **CO₂ Comparison**

   * SVG doughnut chart showing CO₂/km by fuel type.

4. **Vehicle Age Analysis**

   * SVG line chart comparing cost/km across vehicle age from 0–12 years.
   * Vehicle age is highlighted on the chart.

5. **E85 Score**

   * Animated SVG gauge displaying the E85 score out of 10.

6. **Fuel Comparison Cards**

   * Pros
   * Cons
   * Best-use scenario
   * Highlighted selected fuel type

## 🧮 Key Calculations

### Cost per Kilometer

`Fuel Cost ÷ Distance`

### CO₂ per Kilometer

`CO₂ Emitted ÷ Distance`

### Maintenance Cost per Kilometer

`Maintenance Cost ÷ Distance`

### E85 Pump Saving

`((Petrol Price − E85 Price) ÷ Petrol Price) × 100`

### E85 Running Penalty

`((E85 Cost/km − Petrol Cost/km) ÷ Petrol Cost/km) × 100`

### E85 Break-even Price

`(E85 Mileage ÷ Petrol Mileage) × Petrol Price`

### E85 Score

The E85 score is calculated using:

* Cost → 4 points
* CO₂ → 3 points
* Refueling time → 2 points
* Maintenance → 1 point

## 🔎 Analysis Findings

The dashboard was reviewed for:

* Fuel cost efficiency
* Maintenance cost efficiency
* CO₂ emissions
* Refueling/recharging time
* Vehicle age impact
* E85 economics
* E85 break-even price
* Overall E85 score

The comparison helps identify which fuel type provides the best balance between **running cost, maintenance, environmental impact, and convenience**.

## 💡 Learnings

* Learned how to convert raw CSV data into meaningful vehicle-cost metrics.
* Improved understanding of cost-per-kilometer calculations.
* Learned how fuel types can be compared using multiple performance metrics.
* Understood how vehicle age can affect operating and maintenance costs.
* Learned how to calculate E85 pump savings and running penalties.
* Learned how break-even pricing can be used to evaluate alternative fuels.
* Practiced creating responsive dashboards using pure HTML, CSS, JavaScript, and SVG.
* Learned how AI can accelerate data analysis and dashboard development.
* Improved my workflow for reviewing, testing, and documenting AI-generated code.

## 📸 Screenshots

Dashboard screenshots are included in the `screenshots` folder.

## 📁 Project Files

```text
Day17/
├── day17.md
├── vehicle-cost-dashboard.html
└── screenshots/
    ├── dashboard-1.png
    └── dashboard-2.png
```

## 🚀 Conclusion

Day 17 focused on building a complete **Vehicle Cost Analysis Dashboard** from a CSV dataset using Claude AI.

This task combined **data analysis, financial calculations, environmental analysis, visualization, responsive UI design, and AI-assisted development** into one practical project.

#60DaysOfClaude #ClaudeAI #AI #DataAnalysis #WebDevelopment #HTML #JavaScript #Dashboard #GitHub
