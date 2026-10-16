# GenAI Powered Data Analytics Job Simulation – Geldium

## Project Overview

This repository documents my completion of the **GenAI Powered Data Analytics Job Simulation** through Forage in October 2026.

The simulation focused on applying data analytics, predictive modeling concepts, business reporting, and responsible AI principles to a customer collections scenario for Geldium.

The objective was to explore customer delinquency patterns and propose a responsible AI-powered collections strategy to support earlier intervention, operational efficiency, and better customer outcomes.

## Project Objectives

- Perform exploratory data analysis (EDA) and customer risk profiling.
- Examine delinquency patterns and data-quality issues.
- Develop a conceptual framework for predicting customer delinquency.
- Translate analytical findings into business recommendations.
- Propose an AI-powered collections workflow with human oversight.
- Identify ethical, fairness, explainability, privacy, and compliance safeguards.
- Define measurable business KPIs and customer outcome indicators.

## Tasks Completed

### 1. Exploratory Data Analysis and Risk Profiling

Reviewed customer-level data to understand delinquency patterns, missing values, repayment history, and potential risk indicators.

Key considerations:
- Investigated missing values and inconsistent payment-history patterns.
- Examined potential relationships between customer attributes and delinquency.
- Distinguished exploratory observations from validated predictive signals.
- Identified the need to verify the delinquency definition and observation period.

### 2. Predicting Delinquency with AI

Outlined a predictive modeling approach to help identify potentially at-risk customer accounts.

Proposed approach:
- Establish a clear target definition and prediction horizon.
- Audit data quality and prevent target leakage.
- Compare an interpretable logistic regression baseline with an appropriate challenger model.
- Use train-only preprocessing and cross-validation.
- Evaluate precision, recall, F1-score, ROC-AUC, PR-AUC, and probability calibration.
- Select operating thresholds based on business costs and customer impact.

**Note:** This repository describes the proposed modeling framework. It does not claim that a production model was deployed or that predictive performance was validated.

### 3. Business Reporting and Data Storytelling

Translated analytical observations into concise business recommendations for a collections strategy.

The recommendations emphasized:
- Validating inconsistent payment-history records.
- Investigating missing loan-balance information.
- Treating exploratory customer-segment differences cautiously.
- Using verified, pre-outcome information for decisions.
- Supporting data-driven decisions without overstating uncertain findings.

### 4. Implementing an AI-Driven Collections Strategy

Designed a high-level concept for an AI-powered collections system.

**Proposed workflow:**

1. **Inputs:** Repayment history, missed-payment trends, credit utilization, loan balance, and other approved data available at decision time.
2. **Decision logic:** Combine validated business rules with a calibrated risk score to recommend proportionate next steps.
3. **Actions:** Provide approved reminders, self-service options, and supportive guidance; route complex or sensitive cases to trained staff.
4. **Learning loop:** Monitor repayment outcomes, engagement, complaints, model drift, and fairness indicators before approving changes.

## Responsible AI Principles

The proposed system incorporates the following safeguards:

- **Fairness:** Monitor performance and outcomes across relevant customer groups.
- **Explainability:** Record understandable reasons for model-supported recommendations.
- **Privacy:** Minimize data collection, restrict access, and establish retention controls.
- **Human oversight:** Require trained staff to review hardship arrangements, disputes, exceptions, and sensitive cases.
- **Compliance:** Confirm applicable legal and regulatory requirements before deployment.
- **Auditability:** Document decisions, model changes, overrides, and monitoring results.

The system is intended to support responsible customer assistance, not automatically make adverse decisions.

## Expected Business Impact

Potential outcomes to evaluate through a controlled pilot include:

- Reduced delinquency and improved repayment or cure rates.
- More efficient collections operations.
- Better prioritization of customer outreach.
- More consistent and explainable customer treatment.
- Improved access to relevant support options.
- Stronger monitoring of fairness and customer experience.

These are intended outcomes, not measured results. Any proposed improvement target must be tested against a valid baseline and an appropriate comparison group.

## Proposed Evaluation Metrics

### Business KPIs
- Change in 60-day delinquency relative to a control group.
- On-time repayment and cure rates.
- Cost per resolved account.
- Staff time per case.

### Model and Responsible AI Metrics
- Precision, recall, F1-score, ROC-AUC, and PR-AUC.
- Probability calibration and model drift.
- Complaint rates and customer engagement.
- Group-level error rates and outcome differences.

## Tools and Concepts

- Exploratory Data Analysis
- Predictive Analytics
- Statistical Risk Profiling
- Logistic Regression (proposed baseline)
- Business Reporting and Data Storytelling
- Responsible AI and Model Governance
- Human-in-the-Loop Decision-Making

These tools and concepts reflect the project framework; this list does not imply that every technique was implemented in code.

## Deliverables

- Business Summary Report
- AI-Powered Collections Strategy PowerPoint
- Predictive Modeling Framework and Evaluation Plan

Add the final deliverables to this repository if they are appropriate to share publicly.

## Key Learning

This simulation demonstrated how analytical findings can be translated into a business strategy while accounting for data quality, model uncertainty, customer fairness, explainability, and human oversight.

## Disclaimer

This is an educational job simulation and conceptual project. Geldium is the business scenario used for the exercise. The proposed system is not a deployed production solution, and the recommendations should be validated before real-world use.

## Author

**Al Fahad K**

GitHub: https://github.com/alfahadk

LinkedIn: https://www.linkedin.com/in/alfahadk/
