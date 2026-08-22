# Source Audit — Initial Findings

## CV
The CV is the primary professional record. Verified items include:
- Shahriar Islam; Chittagong, Bangladesh.
- Positioning: ERP, MIS, Data Analytics, Business Intelligence.
- Current role: MIS Manager at DotZi, January 2025–Present.
- Previous roles: Operation Manager at Draft to Vessel (July–December 2024); Product Manager at Mexemy (April–June 2024); Associate Operations & Client Management at M/S Amanat Timber Enterprise (March 2022–February 2024).
- Education: MSc in Data Analytics & Design Thinking for Business, East Delta University (2024–2025); BBA in Supply Chain Management & Marketing, East Delta University (2019–2023), CGPA 3.24.
- Skills and tools listed: SmartPLS-4, SPSS, Minitab, Excel, SQL, R, ArcGIS (basic), Power BI, Tableau, HRIS, ERP, Odoo, Orange, Python, prompt engineering.
- Verified CV metrics include one-third reduction in manual reporting time at DotZi, 20% delivery timeline improvement at Draft to Vessel, 20% demand increase and 30% satisfaction increase at Mexemy, 10% instructor cost reduction at Mexemy, 25% delay reduction and 30% operational-efficiency improvement at M/S Amanat Timber Enterprise, career events for 300+ students, 80,000+ BDT fundraising, and EDU Gaming Fest sponsorship/participant/revenue figures.

## GitHub Profile
Public profile: https://github.com/ShahriaRGits
- Four public repositories are visible: Evaluation-of-Machine-Learning-Modes-on-MFS-Adoption-Among-Young-Adults-in-Bangladesh; Starbucks-Customer-Loyalty-Using-ML-Models; AI-student-support-assistant; MIS-Copilot.
- The profile shows public ownership under the GitHub username ShahriaRGits and recent commit activity in all four repositories.

## Repository 1: MFS adoption ML evaluation
URL: https://github.com/ShahriaRGits/Evaluation-of-Machine-Learning-Modes-on-MFS-Adoption-Among-Young-Adults-in-Bangladesh
- Problem: predict AI adoption intent from survey data using UTAUT constructs.
- Approach: benchmark six classifiers (logistic regression, random forest, SVM, KNN, decision tree, naive Bayes); uses a train/test split and k-fold cross-validation.
- Evidence: README, requirements.txt, MIT license, modular src files for preprocessing, visualization, models, and orchestration; data schema documentation and sample raw CSV.
- Portfolio value: strong academic/research case study connecting survey research, reproducible ML, and decision support. No verified outcome metrics should be invented.
- Overlap: overlaps with Starbucks project in ML classification, but differs in domain and research framing.

## Citation/source handling
All externally sourced facts used in final project content should link to the relevant CV or public GitHub/LinkedIn source. No unverifiable claims should be included.

## Repository 2: Starbucks customer loyalty
URL: https://github.com/ShahriaRGits/Starbucks-Customer-Loyalty-Using-ML-Models
- Problem: analyze Starbucks customer behavior and predict customer loyalty from demographic, visit, purchase, rating, membership, and promotion-related variables.
- Approach: data-quality checks, EDA, feature engineering, PCA/scaling/transformations, encoding/binning, missing-value imputation, feature selection, multiple classifiers, SMOTE class balancing, 5-fold cross-validation, and accuracy/classification-report evaluation.
- Models named in the repository: logistic regression, random forest, SVM, KNN, decision tree, naive Bayes, and gradient boosting.
- Evidence: organized data/notebooks/reports/src structure, README, requirements, project metadata, MIT license, and a report PDF. The dataset is not included and must be placed at the documented path, so avoid claiming fully runnable reproduction without the data.
- Portfolio value: strong applied analytics case study for customer intelligence and model comparison; useful complement to the MFS research project but technically adjacent.

## Repository 3: AI student support assistant
URL: https://github.com/ShahriaRGits/AI-student-support-assistant
- Problem: guide prospective students through programme discovery and recommendation.
- Product approach: four-step guided assessment, server-side AI interpretation, deterministic matching against a clearly labeled fictional catalogue, grounded AI explanations, comparison of up to three programmes, consent-based demo lead capture, and an authenticated admin dashboard.
- Important boundary: README explicitly identifies it as a demonstration product; the five-programme catalogue is fictional, leads are stored in memory for the active server session, and the enquiry form does not contact a real institution.
- Evidence: TypeScript project with GitHub Actions, documentation files including DEMO.md, PORTFOLIO-CASE-STUDY.md, case-study-evidence.md, local-environment guidance, and four commits under Shahriar’s GitHub account.
- Portfolio value: highest product-thinking and AI/automation case study. Present as a prototype/MVP, not as a deployed admissions system.

## Ranking so far
1. AI student support assistant — strongest product/AI/UX breadth and explicit case-study evidence.
2. MFS adoption ML evaluation — strongest research/reproducibility framing.
3. Starbucks customer loyalty — strong applied analytics, but overlaps with the MFS project in classification-model benchmarking.

## Repository 4: MIS Copilot
URL: https://github.com/ShahriaRGits/MIS-Copilot
- Problem: demonstrate an evidence-driven marketing-analytics and MIS workflow.
- Approach: ingest six synthetic CSV fixtures (campaigns, leads, clients, conversions, revenue, operational KPIs); validate schemas and business rules; calculate deterministic KPI cards with formulas, numerators, denominators, and trends; flag rule-based anomalies; send a bounded evidence packet to a server-side LLM; apply numeric-match and banned-causal-phrase guardrails; support bounded Q&A; require a human decision rationale and log decision history.
- Evidence: extensive repository structure, documentation, GitHub Actions, test/build/API smoke-test claims in commit messages, and 10 commits. The repository identifies itself as a focused single-user demonstration rather than a production system.
- Portfolio value: strongest alignment with Shahriar’s MIS, marketing analytics, automation, and business-systems positioning. Feature prominently, but describe synthetic fixtures and MVP/demo boundaries accurately.

## LinkedIn
URL: https://www.linkedin.com/in/shahriar-islam-51450b259/
- The public profile redirected to LinkedIn’s authentication wall. No profile details, certifications, or current-context claims were independently visible.
- Use the CV as the professional record and link to LinkedIn as a destination; do not claim LinkedIn certifications or other details unless separately verified.

## Provisional project selection
Feature four projects to avoid redundancy while covering the intended breadth: MIS Copilot; AI Student Support Assistant; MFS Adoption ML Evaluation; and Starbucks Customer Loyalty. Label the first two as MVP/prototype demonstrations where applicable and the latter two as academic/applied machine-learning work. Avoid fabricated outcomes; use only outcomes explicitly documented in repository evidence or the CV.

## Design research takeaways
The reviewed portfolio references consistently emphasize a clear personal introduction, a small set of strong projects, storytelling rather than raw code links, and visible evidence of communication and business value. The portfolio should therefore lead with a concise positioning statement, use four selected project case-study cards, make the recruiter path obvious through resume/contact CTAs, and keep technical details available without overwhelming the first scan. The design direction will synthesize an editorial layout with analytical visual cues: warm off-white canvas, ink-black typography, restrained cobalt and lime accents, grid lines, compact metadata, high-contrast action buttons, and motion limited to reveal and hover states.

References:
- [CareerFoundry data analytics portfolio examples](https://careerfoundry.com/en/blog/data-analytics/data-analytics-portfolio-examples/)
- [Karaleise business analyst portfolio guidance](https://karaleise.com/business-analyst-portfolio/)
