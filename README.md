# 🏥 Epic Healthcare IT Portfolio — *Chastity Reeder*

> Aspiring Epic Analyst | Health Information Management | EHR Workflow Optimization | SQL & Data Integrity

Welcome to my hands-on healthcare IT simulation portfolio. Each project below demonstrates real-world skills used in Epic implementation, HIM operations, revenue cycle management, and clinical data analysis.

---

## 👩🏾‍💻 About Me

I am a healthcare IT professional building expertise in Epic EHR systems, health information management, and clinical data quality. My projects simulate the workflows, audits, and optimizations used daily by Epic analysts, HIM specialists, and revenue cycle teams.

📍 Charlotte, NC &nbsp;|&nbsp; 📧 [your-email@email.com] &nbsp;|&nbsp; 🔗 [LinkedIn Profile URL]

---

## 📁 Completed Projects

| # | Project | Tools Used | Key Skills |
|---|---------|-----------|------------|
| 1 | [🔬 Epic Data Integrity Audit](#project-1--epic-data-integrity-audit) | SQL Server, T-SQL | Data quality, MRN audits, referential integrity |
| 2 | [🏨 Epic Prelude / HIM Workflow Simulation](#project-2--epic-prelude--him-workflow-simulation) | OpenEMR, MS Word | Patient registration, scheduling, EHR documentation |
| 3 | [📊 Workflow Efficiency Analysis](#project-3--workflow-efficiency-analysis) | Microsoft Excel | Before/after analysis, KPIs, data visualization |
| 4 | [💊 Medication Safety Alert Audit](#project-4--medication-safety-alert-audit) | Excel | Drug-allergy alert testing, CPOE safety |

---

## Project 1 — 🔬 Epic Data Integrity Audit

**Folder:** [`/Epic-Data-Integrity-Audit`](./Epic-Data-Integrity-Audit)

Simulated a full data integrity audit on an Epic-style SQL Server database with three tables: Patients, Encounters, and Insurance. Identified missing values, duplicate MRNs, invalid flags, and orphaned records that would cause real-world billing failures and reporting errors.

**Findings:**
- 2 patients with missing Date of Birth → impacts age-based quality metrics
- 1 duplicate MRN (10002) shared by two patients → wrong-patient error risk
- 3 invalid ActiveFlag values → breaks workflow triggers
- 1 orphaned encounter linked to non-existent patient → reporting failure
- 1 patient with encounters but no insurance → unbillable claim

**What's inside:**
```
Epic-Data-Integrity-Audit/
├── README.md
├── sql/
│   ├── 01_create_tables.sql
│   ├── 02_insert_sample_data.sql
│   ├── 03_audit_patients.sql
│   └── 04_06_audit_encounters_insurance_crosstable.sql
└── report/
    └── Data_Integrity_Audit_Report.docx
```

---

## Project 2 — 🏨 Epic Prelude / HIM Workflow Simulation

**Folder:** [`/Epic-Prelude-HIM-Simulation`](./Epic-Prelude-HIM-Simulation)

Simulated the end-to-end patient registration and documentation workflow found in Epic Prelude and HIM modules using OpenEMR. Covered demographic entry, insurance verification, appointment scheduling, encounter documentation, and visit history reporting.

**Workflow Steps Simulated:**
1. New patient demographics entry (mirrors Epic Prelude registration)
2. Appointment scheduling via calendar system
3. Encounter documentation (office visit notes, provider assignment)
4. Visit history report generation (HIM reporting workflow)

---

## Project 3 — 📊 Workflow Efficiency Analysis

**Folder:** [`/Workflow-Efficiency-Analysis`](./Workflow-Efficiency-Analysis)

Used Excel to simulate a healthcare workflow efficiency study measuring before/after improvements across four KPIs following a process optimization intervention.

**Results:**

| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| Registration Time | 22.3 min | 16.7 min | ⬇️ 25% |
| Wait Time | 30 min | 20 min | ⬇️ 33% |
| Encounter Completion | 45 min | 32.3 min | ⬇️ 28% |
| Errors Per Encounter | 2.7 | 0.7 | ⬇️ 74% |

---

## Project 4 — 💊 Medication Safety Alert Audit

**Folder:** [`/Medication-Safety-Alert-Audit`](./Medication-Safety-Alert-Audit)

Simulated drug-allergy alert testing in a CPOE (Computerized Provider Order Entry) environment. Tested whether allergy alerts triggered correctly when medications were ordered for patients with known contraindications.

**Key Test:** Patient with Amoxicillin allergy → Penicillin VK ordered → Alert triggered ✅

---

## 🛠️ Skills & Tools

| Category | Skills |
|----------|--------|
| **EHR Systems** | Epic Prelude, Epic HIM, OpenEMR |
| **Database & SQL** | SQL Server, T-SQL, Joins, Subqueries, Data Auditing |
| **Data Analysis** | Microsoft Excel, KPI Reporting, Before/After Analysis |
| **Healthcare IT** | MRN Management, Revenue Cycle, CPOE, Medication Safety |
| **HIM Concepts** | Patient Registration, Encounter Documentation, Coding Workflows |
| **Soft Skills** | Documentation, Audit Reporting, Process Improvement |

---

## 🎯 Target Roles

- Epic Analyst (Prelude / HIM / Resolute)
- Health Information Management Specialist
- EHR Implementation Specialist
- Healthcare Data Analyst
- Revenue Cycle Analyst

---

*This portfolio is actively growing. New projects added regularly.*
