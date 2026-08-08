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
## Assembled Onboarding Plan 
| Stage | User Segment | Message Type | Frequency | Limitations | Prompt Message | Purpose | Message Content |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **Business Calibration** | **The Reactive Founder** | In-App Modal | 1 per session | Limited real-time transaction categorization capabilities | **Tailor Your Cash View** | Guide activation | "Welcome to FinWise! Select your business model and primary goal so we can tailor your cash runway cards instantly." |
| **Bank Data Integration** | **The Reactive Founder** & **Operational Growth Lead** | In-App Slide-over | 1 per session | Third-party bank API sync latencies | **Secure 1-Click Bank Sync** | Guide activation | "Connect your business account via Plaid. While API sync completes, we will automatically organize your last 90 days of cash history." |
| **Cash Runway Dashboard (Aha)** | **The Reactive Founder** | In-App Insight Banner | 1 per session | Limited real-time transaction categorization capabilities | **Actionable Expense Alert** | Highlight actionable insights | "We flagged $4,200 in recurring subscriptions with low utilization. Click 'Resolve' now to reclaim cash and extend your runway by 2 weeks." |
| **Cash Runway Dashboard (Aha)** | **The Operational Growth Lead** | Interactive Tooltip | 1 per session | Rigid trial paywall configurations | **Unlock 90-Day Forecast** | Highlight actionable insights | "Your 14-week cash forecast is active. Test custom 'What-If' scenario models right now to plan upcoming Q4 hiring and cash reserves." |
| **Team Collaboration** | **The Operational Growth Lead** & **External Advisor** | In-App Pop-up | 1 per session | Rigid trial paywall configurations | **Invite Your Advisory Co-Pilot** | Encourage collaborator invites & drive paid conversion | "Bring your accountant or leadership team into FinWise. Invite a collaborator today to lock in this forecast and share live audit-ready reports." |
## 🚀 How to Use This Repository

1. **Review the Interactive Worksheet:** Open `FinWise_Hypothesis_Worksheet.md` to see the complete log of initial hunches, data pressure-tests, and formalized experiment parameters.
2. **Execute Experiments:** Use the structured $IF / THEN / BECAUSE / MEASURED\ WITH$ framework established in Module 1 to design downstream A/B variants.
