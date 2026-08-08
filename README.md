# FinWise Product Experimentation Framework

This repository contains the product hypothesis, experimentation blueprints, and data pressure-testing framework for **FinWise**, developed as part of the Product School Product Analytics & Experimentation certification.

---

## 📌 Executive Summary

FinWise’s initial growth diagnostic identified a critical gap between high product engagement and low trial-to-paid monetization. Despite strong adoption of core features like data imports and financial modeling during the reverse trial, conversion remained stagnant at ~2%.

This project shifts the growth strategy from onboarding usability to a **Collaboration-Driven Monetization Loop**, leveraging multi-seat team access and accounting partner workflows to drive organic acquisition and trial conversion.

---

## 🛠 Project Structure & Modules

```text
├── Module-1/
│   ├── FinWise_Hypothesis_Worksheet.md    # Completed Module 1 exercise & data pressure-testing
│   └── Exercise_1_Guide.md                # Reference guide for testable hypotheses
└── README.md

```

---

## 🧪 Module 1: Hypothesis & Bet Summary

### 1. Initial Assumption

* **Hypothesis:** Top-of-funnel drop-off stems from a broken onboarding flow preventing users from reaching their "aha moment".
* **Initial Bet:** Implement a guided 3-step setup checklist during initial login to drive Day-1 activation.

### 2. Data Pressure-Testing & Findings

* **Surprising Pattern:** Feature adoption spiked dramatically (e.g., Data Import reached 94% and Financial Modeling reached 63%) without lifting the trial-to-paid conversion rate.
* **Refined Insight:** The core funnel bottleneck is at the **Revenue stage**. Users extract high utility from the free reverse trial without encountering a compelling value paywall trigger.

### 3. Formalized Growth Experiment

* **Strategy:** Collaboration-Driven Growth Loop
* **Target Area:** Revenue & Referral stages
* **Core Test (Z):** Gate multi-seat stakeholder collaboration features (e.g., shared advisor/bookkeeper reporting) behind paid subscription tiers while offering free collaborator invitations during trial periods to establish operational lock-in.

---

## 📊 Key Metrics & Leading Indicators

| Metric Type | Metric Name | Target Benchmark |
| --- | --- | --- |
| **Leading Indicator** | Day-1 Core Action Completion | Increase setup completion within 10 mins |
| **Primary Outcome** | 14-Day Trial-to-Paid Conversion | Lift from 2.0% to 3.5% |
| **Retention Metric** | First-Year Customer Retention | Mitigate current 60% annual churn rate |

---

## 🚀 How to Use This Repository

1. **Review the Interactive Worksheet:** Open `FinWise_Hypothesis_Worksheet.md` to see the complete log of initial hunches, data pressure-tests, and formalized experiment parameters.
2. **Execute Experiments:** Use the structured $IF / THEN / BECAUSE / MEASURED\ WITH$ framework established in Module 1 to design downstream A/B variants.
