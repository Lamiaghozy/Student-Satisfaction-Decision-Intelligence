# Optimising Student Satisfaction Through Decision Intelligence

### AWS QuickSight Business Intelligence Case Study

**Industry:** Higher Education
**Focus:** Business Intelligence • Decision Intelligence • Executive Analytics • Cost Efficiency

---

## Project Overview

This case study demonstrates how Business Intelligence and Decision Intelligence can be applied to support leadership decisions around student evaluation outcomes, professor performance, and course cost efficiency.

Using **AWS QuickSight**, the project transformed student enrollment, course, professor, evaluation, and cost data into an integrated analytical environment combining:

* Data preparation and modelling
* KPI analysis
* Executive dashboards
* Natural-language analytics
* Scenario-based analysis
* Data storytelling
* Strategic recommendations

The objective was not simply to report historical performance, but to investigate where improvement opportunities existed and how successful practices could potentially be replicated while maintaining financial discipline.

> **Decision focus:** How can student evaluation outcomes and teaching performance be improved without increasing course delivery costs?

---

# Business Challenge

Higher education institutions must balance teaching quality, student experience, and financial sustainability.

While operational data may be available, historical reporting alone does not necessarily tell leadership:

* Which professors consistently demonstrate strong evaluation performance
* Which courses combine strong evaluation outcomes with relatively low costs
* Where recent improvements have occurred
* Which successful practices may be worth investigating for replication
* Where limited resources could potentially generate greater value

This project addresses that decision challenge by bringing performance and cost indicators into a unified Business Intelligence framework.

---

# Decision Objective

The analysis was designed to help leadership:

1. Identify patterns associated with stronger professor and course evaluation outcomes.
2. Examine changes in evaluation performance over time.
3. Investigate course-level improvements contributing to stronger performance.
4. Identify courses demonstrating strong evaluation outcomes alongside relatively low delivery costs.
5. Develop evidence-based recommendations for improving outcomes while maintaining financial discipline.

---

# Solution

An AWS QuickSight Business Intelligence environment was developed to connect analytical exploration with executive decision-making.

The solution incorporated:

**Data → Analysis → Dashboard → Scenario → Recommendation**

The workflow moved progressively from descriptive analysis toward decision-oriented investigation.

### Analytical workflow

```text
Data Preparation
       ↓
Calculated Fields & Modelling
       ↓
Performance Analysis
       ↓
Executive Dashboards
       ↓
Natural-Language Analytics
       ↓
Scenario Analysis
       ↓
Data Storytelling
       ↓
Strategic Recommendations
```

This structure demonstrates how a BI solution can move beyond reporting toward structured decision support.

---

# Executive Dashboard Solution

Four dashboards were developed to provide complementary views of institutional performance.

## 1. Executive Performance Overview

Provides leadership with a consolidated view of enrollment, professor evaluation performance, course evaluations, and cost-related indicators.

**Business purpose:** Enable rapid identification of performance patterns, gaps, and areas requiring further investigation.

![Executive Performance Overview](screenshots/executive-performance-overview.png)

---

## 2. Professor Performance Analysis

Examines evaluation performance across professors to identify consistently strong performers and areas where further investigation may be valuable.

**Business purpose:** Support evidence-based faculty development and investigation of practices associated with stronger evaluation outcomes.

![Professor Performance Analysis](screenshots/professor-performance-analysis.png)

---

## 3. Course Performance & Cost Efficiency

Brings course evaluation performance and course delivery cost into the same decision context.

**Business purpose:** Help leadership identify courses that demonstrate strong evaluation outcomes alongside relatively efficient delivery costs.

![Course Performance & Cost Efficiency](screenshots/course-performance-cost-efficiency.png)

---

## 4. Student Demographics & Enrollment Trends

Examines student composition and enrollment patterns across the available periods.

**Business purpose:** Provide visibility into participation patterns and support broader institutional planning.

![Student Demographics & Enrollment Trends](screenshots/student-demographics-enrollment-trends.png)

---

# Key Business Insights

The analysis produced several findings with direct relevance to institutional decision-making.

### 1. High-Performing Professors Represent a Replication Opportunity

Consistently strong professor evaluation performance provides an opportunity to investigate the teaching practices associated with higher evaluation outcomes and assess whether these practices can be replicated across departments.

### 2. 2022 Performance Improvement Provides a Replication Opportunity

Evaluation performance improved in 2022 compared with previous periods. This creates an opportunity to investigate the institutional, course-level, and teaching factors associated with the improvement.

### 3. Course-Level Improvements Can Create Institutional-Level Impact

The analysis highlighted improvements in **Accounting and Statistics** as important contributors to the overall increase in evaluation performance during 2022.

This demonstrates how targeted course-level improvements can contribute to broader institutional performance.

### 4. Strong Evaluation Outcomes Do Not Necessarily Require Higher Cost

Several courses demonstrated strong evaluation outcomes while maintaining relatively low delivery costs.

This suggests that educational quality and financial efficiency do not necessarily require proportional increases in expenditure.

### 5. Data Visualisation Provides a Cost-Effective Excellence Example

The **Data Visualisation** course emerged as an example of strong evaluation performance alongside relatively low cost.

This creates an opportunity for deeper investigation into the practices associated with the outcome and whether similar approaches could be transferable elsewhere.

---

# Scenario-Based Decision Analysis

A structured analytical scenario was developed around the central decision question:

> **How can professor performance and student evaluation outcomes be improved without increasing cost per course?**

The analytical thread progressed from broad performance investigation toward specific course-level opportunities:

1. What factors contribute to high professor evaluation scores?
2. What factors contributed to higher evaluation scores in 2022?
3. How did Accounting and Statistics improvements contribute to the 2022 increase?
4. Which courses achieve strong evaluation outcomes while maintaining relatively low costs?
5. What factors explain the strong performance of Data Visualisation despite its low cost?
6. What actions could improve student evaluation outcomes while maintaining cost discipline?

This progression demonstrates a structured approach to moving from **observation → investigation → comparison → decision**.

---

# Strategic Recommendations

Based on the analysis, the project recommends that leadership:

### Replicate High-Performing Teaching Practices

Investigate the practices associated with consistently strong professor evaluation performance and develop mechanisms for sharing successful approaches across departments.

### Prioritise High-Value, Cost-Efficient Courses

Evaluate course performance alongside delivery costs to identify areas demonstrating a strong combination of evaluation outcomes and financial efficiency.

### Use 2022 as a Performance Benchmark

Investigate the factors associated with the 2022 improvement, particularly within Accounting and Statistics, and determine which practices can be sustained or replicated.

### Investigate Cost-Effective Excellence

Use Data Visualisation as a case for deeper investigation into how strong evaluation outcomes were achieved alongside relatively low cost.

### Institutionalise Executive Performance Monitoring

Maintain consistent KPI monitoring across professor evaluations, course performance, enrollment patterns, and cost efficiency to support continuous evidence-based decision-making.

---

# Business Intelligence Capabilities Demonstrated

## Data Preparation & Modelling

* Dataset field configuration
* Data preparation
* Calculated fields
* Student segmentation
* Dataset refresh configuration

## Analytical Development

* Enrollment analysis
* Professor performance analysis
* Course evaluation analysis
* Course cost analysis
* Trend analysis
* Comparative performance analysis

## Dashboard Development

* Executive KPI dashboards
* Performance visualisation
* Cost-efficiency analysis
* Interactive analytical views
* Business-oriented visual design

## Advanced QuickSight Capabilities

* QuickSight Topics
* Named entities
* Verified answers
* Natural-language analytics
* Scenario analysis
* Data Story

## Business Communication

* Executive interpretation
* Strategic recommendations
* Decision-oriented storytelling
* Business-focused data visualisation

---

# Technical Approach

The project was implemented within **AWS QuickSight** and followed a structured BI workflow.

### Data Layer

The analytical dataset incorporated student, course, professor, evaluation, enrollment, and cost information.

A calculated **Student Type** field was created to distinguish:

* Youth students
* Adult Continuing Education students

using an age-based business rule.

### Analytical Layer

Multiple analyses were developed to investigate:

* Student majors by year
* Student type distribution
* Professor evaluation performance
* Course evaluation performance
* Average course cost by professor
* Average course cost by course

### Decision Layer

QuickSight Topics, verified answers, and scenario analysis were used to extend the analytical workflow beyond static visualisation toward natural-language exploration and structured decision analysis.

### Communication Layer

The final outputs were consolidated into executive dashboards and a Data Story designed to communicate analytical findings and recommendations to business stakeholders.

---

# Technology Stack

**AWS QuickSight**
**Business Intelligence**
**Data Modelling & Transformation**
**Calculated Fields**
**KPI Analysis**
**Dashboard Development**
**Natural-Language Analytics**
**Scenario Analysis**
**Data Storytelling**

---

# Project Structure

```text
student-satisfaction-decision-intelligence/
│
├── README.md
│
├── docs/
│   └── AWS_QuickSight_Business_Intelligence_Case_Study.pdf
│
└── screenshots/
    ├── executive-performance-overview.png
    ├── professor-performance-analysis.png
    ├── course-performance-cost-efficiency.png
    └── student-demographics-enrollment-trends.png
```

---

# Documentation

## Executive Case Study

The full executive case study is presented through the accompanying Notion portfolio page, providing the business narrative, decision context, analytical findings, recommendations, and executive interpretation.

**→ View the Executive Case Study**

## Detailed Project Report

The detailed technical report documents the original project workflow, including:

* Dataset configuration
* Calculated fields
* Analytical visuals
* QuickSight Topics
* Verified answers
* Dashboard development
* Scenario analysis
* Data Story
* Created QuickSight resources

**→ View Detailed Project Report**

---

# Project Status

**Completed**

This project represents a completed Business Intelligence case study demonstrating the application of AWS QuickSight to a decision-oriented analytical problem.

The original analytical work was developed as a Business Intelligence Engineer project and has subsequently been structured as a professional case study to emphasise business context, decision-making, analytical reasoning, and executive communication.

---

# Author

## Dr. Lamia Ghozy

**Senior Business Intelligence Analyst | Commercial Analytics | Healthcare Analytics | Decision Intelligence**

Business Intelligence professional with extensive experience across healthcare, pharmaceuticals, commercial analytics, executive reporting, and data-driven decision support.

**LinkedIn:** [Dr. Lamia Ghozy](https://www.linkedin.com/in/dr-lamia-ghozy-dba-mba-ci-nlp)

**Portfolio:** [Notion Executive Portfolio]

---

> **The objective of Business Intelligence is not simply to produce reports. It is to turn data into evidence that improves decisions.**
