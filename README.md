# German HTA Case Study: IQWiG A25-111 — Lecanemab

### Independent Self-Directed Analysis of a German Early Benefit Assessment under §35a SGB V

An applied health technology assessment (HTA) case study examining the German early benefit assessment of **lecanemab** for early Alzheimer's disease.

The project uses the published **IQWiG A25-111 assessment** to demonstrate practical understanding of German HTA methodology, evidence appraisal, statistical interpretation, and Market Access.

> **Educational portfolio project:** This is an independent analysis of publicly available evidence and does not represent professional work for IQWiG, G-BA, a pharmaceutical company, or a Market Access consultancy.

---

## Project Overview

This case study examines how clinical evidence is evaluated within the German **AMNOG / §35a SGB V** early benefit assessment framework.

The analysis focuses on:

* German HTA methodology
* IQWiG evidence assessment
* PICO formulation
* Appropriate comparator therapy (ZVT)
* Clinical trial evidence
* Patient-relevant outcomes
* Relative risks and confidence intervals
* Risk of bias
* Evidence uncertainty
* Benefit–harm assessment
* Evidence gaps
* Market Access implications

The project is based primarily on **IQWiG Project A25-111: Lecanemab — Benefit assessment according to §35a SGB V**.

---

## Case Study

| Item               | Details                                    |
| ------------------ | ------------------------------------------ |
| Medicine           | Lecanemab                                  |
| Indication         | Early Alzheimer's disease                  |
| IQWiG project      | A25-111                                    |
| Assessment         | Benefit assessment according to §35a SGB V |
| IQWiG report       | Version 1.0                                |
| Report date        | 27 November 2025                           |
| Publication        | 1 December 2025                            |
| Clinical trial     | CLARITY AD                                 |
| ClinicalTrials.gov | NCT03887455                                |
| DOI                | 10.60584/A25-111                           |
| HTA framework      | AMNOG / §35a SGB V                         |

---

## Research Questions

The assessment considered three main questions.

### 1. MCI due to Alzheimer's disease

**Intervention:** Lecanemab
**Comparator:** Watchful waiting

### 2. Mild Alzheimer's dementia with background AChEI therapy

**Intervention:** Lecanemab + acetylcholinesterase inhibitor
**Comparator:** AChEI therapy

### 3. Mild Alzheimer's dementia — monotherapy

**Intervention:** Lecanemab
**Comparator:** Acetylcholinesterase inhibitor therapy

The third question illustrates an important HTA evidence gap: a relevant comparative study for lecanemab monotherapy versus the appropriate comparator was not identified.

---

## HTA Framework

The project follows the logic of a German early benefit assessment:

```text
Marketing authorisation
        ↓
Manufacturer evidence dossier
        ↓
§35a SGB V early benefit assessment
        ↓
IQWiG scientific assessment
        ↓
Comments / hearing
        ↓
G-BA resolution
        ↓
Reimbursement / Market Access implications
```

The case study focuses primarily on the scientific evidence-assessment component.

---

## Key HTA Concepts Applied

### §35a SGB V

The German legal framework for the early benefit assessment of medicines.

### IQWiG

The Institute for Quality and Efficiency in Health Care, which conducts scientific assessments on behalf of the G-BA in areas including pharmaceutical benefit assessment.

### G-BA

The Federal Joint Committee, responsible for the formal decision on the added benefit of medicines within the German statutory health insurance system.

### PICO

The evidence question is structured around:

* **Population**
* **Intervention**
* **Comparator**
* **Outcomes**

### ZVT

The **zweckmäßige Vergleichstherapie**, or appropriate comparator therapy, is central to the German benefit assessment.

---

## Evidence Analysis

The project maps the relevant evidence to the German research questions rather than relying only on the overall clinical trial population.

Examples of outcomes examined include:

* CDR-SB
* ADAS-Cog14
* EQ-5D VAS
* QOL-AD
* Symptomatic ARIA
* Infusion-related reactions

The analysis considers both efficacy and safety.

---

## Statistical Interpretation

Relative risks (RRs) and confidence intervals are used to interpret selected outcomes.

For example:

| Outcome                  |     Effect estimate |
| ------------------------ | ------------------: |
| CDR-SB deterioration     | RR 0.80 [0.53–1.20] |
| ADAS-Cog14 deterioration | RR 0.63 [0.35–1.14] |
| EQ-5D VAS deterioration  | RR 0.66 [0.37–1.16] |
| QOL-AD deterioration     | RR 0.56 [0.27–1.14] |

The analysis emphasizes that a favourable point estimate does not automatically establish an added benefit.

Confidence intervals, methodological limitations, population relevance, comparator alignment, and clinical relevance must also be considered.

---

## Risk of Bias

IQWiG assessed the risk of bias for the relevant analyses as **high**.

The case study considers methodological issues including:

* treatment modifications;
* disease progression;
* treatment discontinuation;
* missing or potentially informative observations;
* and the resulting uncertainty around estimated treatment effects.

This demonstrates an important HTA principle:

> A numerical treatment effect must be interpreted together with the credibility and limitations of the evidence producing it.

---

## IQWiG Conclusion

For the relevant research questions, IQWiG concluded that **added benefit was not proven**.

This does not mean that the clinical trial demonstrated that lecanemab had no biological or clinical effect.

Rather, within the specific German HTA framework, the relevant evidence did not establish an added benefit against the appropriate comparator for the assessed populations.

For the monotherapy question, relevant comparative evidence was not available.

---

## Market Access Lessons

The case demonstrates why Market Access analysis requires more than reporting clinical trial results.

Key lessons include:

1. **Comparator alignment is critical.**
2. **Trial populations must be relevant to the reimbursement question.**
3. **Patient-relevant outcomes must be interpreted carefully.**
4. **Effect estimates must be considered together with confidence intervals and uncertainty.**
5. **Risk of bias affects confidence in evidence.**
6. **Safety must be considered alongside efficacy.**
7. **Evidence gaps can create Market Access risks.**
8. **German HTA requirements should be considered during evidence planning, not only at submission stage.**

---

## Repository Structure

```text
german-hta-lecanemab-iqwig-a25-111/
│
├── README.md
│
├── analysis/
│   ├── README.md
│   ├── 01_hta_context.md
│   ├── 02_pico_and_zvt.md
│   ├── 03_evidence_mapping.md
│   ├── 04_critical_appraisal.md
│   ├── 05_hta_evidence_summary.md
│   ├── 06_statistical_interpretation.md
│   ├── 07_risk_of_bias.md
│   ├── 08_iqwig_conclusion.md
│   └── 09_market_access_takeaways.md
│
├── data/
│   ├── README.md
│   └── evidence_table.csv
│
└── references/
    └── sources.md
```

---

## Skills Demonstrated

### HTA / Market Access

* German AMNOG framework
* §35a SGB V
* IQWiG methodology
* G-BA process
* Appropriate comparator therapy (ZVT)
* PICO
* Evidence mapping
* Patient-relevant outcomes
* Benefit–harm assessment
* Evidence-gap identification

### Evidence & Data Analysis

* Clinical evidence interpretation
* Literature analysis
* Risk-of-bias assessment
* Relative risk interpretation
* Confidence intervals
* Statistical uncertainty
* Structured evidence extraction
* Reproducible evidence tables

### Scientific Communication

* Scientific writing
* Evidence synthesis
* Structured analytical reporting
* Technical documentation
* English-language communication

---

## Why I Built This Project

My academic background combines **public health and data science**, and I am interested in the intersection of healthcare evidence, data analysis, digital health, and evidence-based decision-making.

This case study was developed to build practical knowledge of **German HTA and Market Access methodology** using a real publicly available IQWiG assessment.

It demonstrates how clinical evidence can be translated into a structured assessment of:

**population → comparator → outcomes → statistical evidence → uncertainty → benefit–harm → Market Access implications**

---

## Primary Sources

The analysis is based primarily on official publications from:

* IQWiG
* G-BA
* ClinicalTrials.gov
* IQWiG methodological publications

See [`references/sources.md`](references/sources.md) for the complete source list.

---

## Disclaimer

This repository is an **independent educational portfolio project**.

It is not:

* an official IQWiG assessment;
* an official G-BA document;
* professional Market Access consulting work;
* a pharmaceutical-company submission;
* or evidence of employment or professional experience at IQWiG or G-BA.

All conclusions attributed to IQWiG are based on the publicly available source documents cited in this repository.
