# Hi, I’m Maxwell Pearson 👋

**University of Nottingham student | Data Analytics, BI & Applied Machine Learning | Seeking Summer 2027 internships**

[🫀 Try my live machine-learning project](https://cardiomodel-shift-maxpearson.streamlit.app/) · [📊 Explore my Clinical Trials Intelligence project](https://github.com/MaxPearson05/Clinical-Trials-Intelligence) · [🔗 Connect on LinkedIn](https://www.linkedin.com/in/maxwell-pearson-168900259)

I’m a Sport & Exercise Science student preparing for a year focused on Data Analytics and AI. I’m building a self-directed portfolio spanning SQL, Python, machine learning, data modelling, Power BI and interactive analytics applications.

My background combines practical data analysis, university club leadership, coaching and international powerlifting. I enjoy turning complex data into clear findings, testing whether those findings are reliable and communicating what they mean for real decisions.

## Featured projects

### 🫀 CardioModel Shift

**Python · pandas · scikit-learn · Machine Learning · Model Validation · Streamlit**

[Live model explorer](https://cardiomodel-shift-maxpearson.streamlit.app/) · [GitHub repository](https://github.com/MaxPearson05/cardiomodel-shift)

A cross-population audit investigating whether heart-disease classification models maintain their performance when transferred between different patient cohorts.

Using 597 historical records from the Cleveland and Hungarian cohorts of the UCI Heart Disease collection, I:

- Audited missingness, outcome definitions and population differences
- Harmonised ten shared clinical features
- Built leakage-controlled preprocessing pipelines
- Trained Logistic Regression and Random Forest models
- Evaluated ROC-AUC, PR-AUC, accuracy, sensitivity, specificity and Brier score
- Compared transfer in both cohort directions
- Repeated the experiment across 30 stratified data splits
- Assessed classification errors and probability calibration
- Used permutation importance to investigate model reliance
- Built and deployed an interactive Streamlit model explorer

#### What the analysis found

- Cleveland-trained models transferred relatively well to Hungary.
- Hungary-trained models showed a more consistent decline when evaluated in Cleveland.
- Hungary-to-Cleveland ROC-AUC fell by an average of 0.052 for Logistic Regression and 0.040 for Random Forest.
- External ROC-AUC was lower in 83.3% and 90.0% of repeated Hungary-to-Cleveland splits respectively.
- Random Forest generally produced stronger external discrimination, but sometimes at the cost of lower sensitivity.
- Features that differed between populations were not necessarily the features on which models relied most heavily.

The project demonstrates why accuracy alone is insufficient and why external validation, calibration and error tradeoffs matter when evaluating predictive models.

The application uses anonymous historical examples and is strictly an educational demonstration. It is not a diagnostic system or personal risk calculator.

---

### 📊 Clinical Trials Intelligence

**PostgreSQL · SQL · Power BI · DAX · Python · Healthcare Analytics**

[View the project, dashboard and methodology](https://github.com/MaxPearson05/Clinical-Trials-Intelligence)

An analysis of 46,955 industry-led interventional drug and biological trials using ClinicalTrials.gov and AACT data, with a global view and UK focus.

I prepared trial-level data, modelled multinational participation and built three Power BI dashboard pages:

- **Trial Overview:** activity, status, phase mix and country participation
- **Portfolio & Delivery Insights:** enrollment, site footprint and recorded timelines
- **Geographic & Reporting Governance:** UK participation and public results visibility

#### Selected findings

| Finding | Why it matters |
|---|---|
| Phase 3 median recorded enrollment was 312, compared with 36 in Phase 1; median site counts were 24 versus 1. | Highlights differences in recruitment and coordination requirements across development phases. |
| UK participation was 17.6% for 2015 starts and 12.8% for 2025 starts among trials with known geography. | Provides a starting point for geographic benchmarking. |
| Mature eligible results coverage was 18.2% in Phase 1 and 71.3% in Phase 3. | Shows uneven public evidence availability without presenting it as proof of regulatory non-compliance. |

The repository contains the SQL research, Power BI report, DAX measures, supporting data, validation evidence and documented limitations. A separate Python and pandas workflow demonstrates API ingestion and nested JSON preparation.

## Experience beyond the portfolio

### GPS Data Analysis — University of Nottingham Men’s Hockey 1st Team

I previously worked with the team as a GPS Data Analyst Intern, analysing training and competition data. I monitored physical-performance metrics and provided real-time feedback to support coaching and match-day decisions.

I’m returning to work with the team and plan to develop a longer-term analytical workflow that brings season records together, supports consistent reporting and makes performance trends easier to investigate.

### President & Club Coach — University of Nottingham Powerlifting Club

I lead the club and coach athletes from novice through to competitive level, including athletes progressing to national and international championships.

My competitive experience includes:

- U18 British National Champion and national record holder
- Represented Team GB at the IPF World Championships, finishing sixth
- Placed seventh at BUCS 2026

Coaching and club leadership have strengthened my communication, organisation and ability to turn performance information into practical decisions.

## Technical toolkit

| Area | Tools and experience |
|---|---|
| Programming and analysis | Python, pandas, NumPy, SQL and PostgreSQL |
| Machine learning | scikit-learn, Logistic Regression, Random Forest, preprocessing pipelines and permutation importance |
| Model evaluation | Cross-population validation, ROC-AUC, PR-AUC, sensitivity, specificity, calibration and repeated-split analysis |
| Reporting and visualisation | Power BI, DAX, Matplotlib, Seaborn, Excel and Power Query |
| Applications and delivery | Streamlit, Git, GitHub and reproducible Jupyter notebooks |
| Data engineering foundations | API ingestion, JSON normalisation, relational modelling, bridge tables and BigQuery `UNNEST` |

## How I approach analysis

- Begin with a clear question, population and unit of analysis.
- Audit source quality before modelling or visualisation.
- Check keys and relationships before joining tables.
- Prevent leakage between training and evaluation data.
- Validate counts, missingness and metric denominators.
- Compare multiple metrics rather than selecting the most flattering result.
- Distinguish observed relationships from causal explanations.
- Document assumptions, limitations and reproduction steps.
- Communicate results around decisions rather than tools alone.

## What I’m developing next

- Applying analytics to longer-term university sports-performance data
- Strengthening statistical reasoning and model-validation skills
- Developing cleaner reusable Python workflows
- Continuing SQL problem-solving practice
- Learning how analytical products move from notebooks into usable applications

My goal is to build on each project with stronger technical judgement, clearer evidence and better communication—not simply a longer list of tools.

## Learning and development

My Applied Data Analytics Portfolio records the exercises and development work behind my progress across Excel, Power Query, PostgreSQL, relational modelling, SQL, Python, API ingestion and Power BI during the time I created the Clinical Trials Intelligence Repo.

The featured repositories present completed employer-facing projects, while the learning portfolio shows how the underlying skills were developed and tested.

## Let’s connect

I’m seeking Summer 2027 Data Analyst, Business Intelligence and applied analytics internship opportunities across industries.

I’m particularly interested in roles where I can contribute to meaningful analytical questions, build practical technical experience and learn from experienced colleagues.

[LinkedIn](https://www.linkedin.com/in/maxwell-pearson-168900259) · [GitHub](https://github.com/MaxPearson05) · [Live CardioModel Shift app](https://cardiomodel-shift-maxpearson.streamlit.app/)
