# 📊 BDM Capstone Project  
## A Primary Data-Based Study of Improving Academic Performance and Business Enhancement in Small-Scale Educational Services

**Author:** Nirmit Desai  
**Roll Number:** 23F3001502  
**Program:** IIT Madras – Online BS Degree  
**Course:** Business Data Management (BDM) Capstone  
**Academic Year:** 2024–2025  

---

## 📌 Project Overview

This project analyzes **academic performance** and identifies **business enhancement opportunities** for a small-scale educational service, **Meghna Tutorials**, which caters to students from **Grades 4 to 10**.

Using **primary data** collected directly from the organization, the study applies **data-driven analytics** to:

- Identify students at risk of poor academic performance or dropout  
- Evaluate the effectiveness of remedial classes  
- Generate automated, personalized academic reports  
- Design a sustainable business model for additional revenue  

The project integrates **educational analytics** with **business decision-making** to deliver actionable insights.

---

## 🎯 Objectives

- Analyze academic performance across grades, subjects, and trimesters  
- Identify early warning indicators for dropout risk  
- Evaluate the impact of remedial interventions  
- Automate student-specific academic report generation  
- Propose business strategies for:
  - Summer remedial programs  
  - Performance-based incentives  
  - Revenue optimization  

---

## 🏫 Organization Studied

**Meghna Tutorials**  
- Location: Hiranandani Estate, Thane  
- Established: 2015  
- Founder: Mrs. Meghna Desai  
- Focus: Personalized tutoring for Grades 4–10  
- Subjects: PCMB, Social Studies, English  

---

## 📂 Dataset Description

- **Type:** Primary data  
- **Students:** 50  
- **Records:** 639  
- **Grades:** 4 to 10  
- **Subjects:**  
  - Mathematics  
  - Science  
  - Physics  
  - Chemistry  
  - Biology  
  - English  
  - Hindi  
  - Social Studies  
- **Time Period:** Academic Year 2024–25  
- **Granularity:** Student × Grade × Trimester × Subject  

### Key Variables
- Monthly Test Score  
- Term-End Score  
- Total Score (0–100)  
- Attendance Percentage  
- Tutor Feedback Score (0–10)  
- Dropout Indicator  
- Remedial Class Participation  

---

## 🔍 Methodology

### 1. Data Preparation
- Data cleaning and validation using Python (`pandas`)
- Handling missing values and anomalies
- Normalization of metrics for comparison

### 2. Descriptive & Diagnostic Analysis
- Summary statistics (mean, median, standard deviation)
- Grade-wise, subject-wise, and trimester-wise analysis
- Attendance and feedback trend analysis

### 3. Risk Identification
- Threshold-based rules:
  - Attendance < 75%
  - Total Score < 50
  - Feedback ≤ 5
- Composite risk score using weighted normalized metrics
- Bottom 20% of students flagged as “at risk”

### 4. Correlation Analysis
- Heatmaps to analyze relationships between:
  - Attendance
  - Academic scores
  - Feedback
  - Dropout status

### 5. Remedial Class Evaluation
- Comparison of remedial vs non-remedial students
- Performance and attendance trends across trimesters

### 6. Automation
- Python-based pipeline to generate:
  - Attendance trend charts
  - Subject-wise performance comparisons
  - Risk flags
  - Personalized recommendations

---

## 📈 Key Findings

- Overall academic performance is strong (average scores above 80)
- Attendance is the strongest predictor of performance and dropout
- Low attendance and poor feedback strongly correlate with dropout risk
- Remedial classes help but do not fully close the performance gap
- Academic risk is multi-factorial and not grade-specific
- High performers consistently show strong attendance, scores, and feedback

---

## 💡 Business Insights & Recommendations

### Academic Recommendations
- Early intervention for at-risk students
- Mandatory attendance tracking for remedial students
- More structured and frequent tutor feedback
- Continuous monitoring using composite risk scores

### Business Model Proposal
- **Summer Remedial Program**
  - Fee: ~10% of annual tuition
  - Target group: Low-performing students
- **Performance Incentives**
  - 5% fee discount for high achievers
- **Outcome**
  - Additional summer revenue
  - Improved student retention and parent engagement

---

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Libraries:**  
  - pandas  
  - numpy  
  - matplotlib  
- **Analysis Type:** Descriptive & Diagnostic Analytics  
- **Visualizations:** Heatmaps, bar charts, scatter plots, line charts  

---



