---
layout: post
title: "Pancreatic Cancer: Why Are We Still Finding It Too Late?"
date: 2026-09-09
categories: [Cancer Research, Biology, Data Science]
tags: [pancreatic cancer, cancer biology, epidemiology, early detection, treatment]
---

<style>
.research-hero {
    padding: 70px 0 80px 0;
    border-bottom: 1px solid #ddd;
    margin-bottom: 60px;
}

.research-kicker {
    text-transform: uppercase;
    letter-spacing: 0.14em;
    font-size: 0.75rem;
    font-weight: 700;
    color: #777;
    margin-bottom: 20px;
}

.research-hero h1 {
    font-size: clamp(3rem, 8vw, 7rem);
    line-height: 0.95;
    letter-spacing: -0.055em;
    max-width: 1050px;
    margin-bottom: 35px;
}

.research-subtitle {
    font-size: 1.35rem;
    line-height: 1.5;
    max-width: 850px;
    color: #555;
}

.research-question {
    margin: 50px 0;
    padding: 35px;
    background: #111;
    color: white;
    border-radius: 12px;
}

.research-question .label {
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.12em;
    color: #aaa;
    margin-bottom: 15px;
}

.research-question h2 {
    margin: 0;
    font-size: clamp(1.5rem, 3vw, 2.4rem);
    line-height: 1.2;
}

.stat-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
    margin: 40px 0;
}

.stat-card {
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 25px;
    background: #fafafa;
}

.stat-number {
    display: block;
    font-size: 2.3rem;
    font-weight: 800;
    letter-spacing: -0.04em;
}

.stat-title {
    display: block;
    font-weight: 600;
    margin-top: 8px;
}

.stat-source {
    display: block;
    font-size: 0.75rem;
    color: #888;
    margin-top: 15px;
}

.research-callout {
    padding: 25px 30px;
    margin: 35px 0;
    border-left: 4px solid #111;
    background: #f3f3f0;
}

.figure-placeholder {
    border: 1px dashed #aaa;
    border-radius: 10px;
    min-height: 320px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 30px 0;
    padding: 30px;
    color: #777;
}

.figure-placeholder strong {
    display: block;
    color: #222;
    margin-bottom: 10px;
}

.research-table {
    width: 100%;
    border-collapse: collapse;
    margin: 30px 0;
}

.research-table th,
.research-table td {
    border-bottom: 1px solid #ddd;
    padding: 14px;
    text-align: left;
}

.research-table th {
    font-weight: 700;
}

.research-roadmap {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
    margin: 30px 0;
}

.roadmap-card {
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 25px;
}

.roadmap-number {
    color: #888;
    font-size: 0.8rem;
    font-weight: 700;
}

.solution-box {
    margin: 50px 0;
    padding: 40px;
    background: #111;
    color: white;
    border-radius: 12px;
}

.solution-box h2 {
    color: white;
    margin-top: 0;
}

.placeholder {
    color: #888;
    font-style: italic;
}

@media (max-width: 800px) {
    .stat-grid,
    .research-roadmap {
        grid-template-columns: 1fr 1fr;
    }
}

@media (max-width: 550px) {
    .stat-grid,
    .research-roadmap {
        grid-template-columns: 1fr;
    }

    .research-hero {
        padding-top: 35px;
    }
}
</style>


<!-- =====================================================
     HERO
===================================================== -->

<section class="research-hero">

    <div class="research-kicker">
        CANCER RESEARCH PROJECT
    </div>

    <h1>
        Pancreatic Cancer:
        <br>
        Why Are We Still Finding It Too Late?
    </h1>

    <p class="research-subtitle">
        A data-driven investigation into the burden, biology,
        detection, treatment, and survival of pancreatic cancer —
        and the question of whether earlier detection could
        fundamentally change outcomes.
    </p>

</section>


<!-- =====================================================
     RESEARCH QUESTION
===================================================== -->

<div class="research-question">

    <div class="label">
        Central Research Question
    </div>

    <h2>
        Why is pancreatic cancer frequently diagnosed at an
        advanced stage, and could earlier detection meaningfully
        improve survival?
    </h2>

</div>


<!-- =====================================================
     PROJECT THESIS / MOCK
===================================================== -->

## Working Hypothesis

> <span class="placeholder">
> Pancreatic cancer remains highly lethal not simply because
> treatment is ineffective, but because many tumors are discovered
> after the disease has already progressed beyond the point where
> curative treatment is most effective.
> </span>

### What I am trying to determine

This project will investigate whether the available evidence
supports the idea that **earlier detection should be one of the
highest-priority opportunities for reducing pancreatic cancer
mortality**.

---

# The Cancer in Numbers

The first part of this project asks a simple question:

> **How large is the problem?**

<div class="stat-grid">

<div class="stat-card">
<span class="stat-number">[67,530]</span>
<span class="stat-title">New Cases</span>
<span class="stat-source">Source: <a href="https://seer.cancer.gov/statfacts/html/pancreas.html" target="_blank">Surveillance, Epidemiology, and End Results Program (SEER) [2]</a></span>
</div>

<div class="stat-card">
<span class="stat-number">[52,740]</span>
<span class="stat-title">Deaths</span>
<span class="stat-source">Source: <a href="https://seer.cancer.gov/statfacts/html/pancreas.html" target="_blank">Surveillance, Epidemiology, and End Results Program (SEER) [2]</a></span>
</div>

<div class="stat-card">
<span class="stat-number">[13.7%]</span>
<span class="stat-title">5-Year Relative Survival (2016 - 2022)</span>
<span class="stat-source">Source: <a href="https://seer.cancer.gov/statfacts/html/pancreas.html" target="_blank">Surveillance, Epidemiology, and End Results Program (SEER) [2]</a></span>
</div>

<div class="stat-card">
<span class="stat-number">[~90%]</span>
<span class="stat-title">Diagnosed at Advanced Stage</span>
<span class="stat-source">Source: <a href="https://www.ox.ac.uk/news/2022-11-01-pancreatic-cancer-could-be-diagnosed-three-years-earlier" target="_blank">University of Oxford, Pancreatic Cancer Action, and University of Surrey [4]</a></span>
</div>

</div>


## Incidence

<span class="placeholder">
Describe how frequently pancreatic cancer occurs in the population.
Compare current incidence with previous decades and explain whether
incidence is increasing, decreasing, or relatively stable.
</span>


## Mortality

<span class="placeholder">
Describe how many patients die from pancreatic cancer and compare
the mortality burden with other major cancers.
</span>


## Incidence vs. Mortality

<span class="placeholder">
This is where I will investigate whether pancreatic cancer has an
unusually high mortality burden relative to the number of people
diagnosed.
</span>


<div class="figure-placeholder">

<div>
<strong>FIGURE 1 — PANCREATIC CANCER INCIDENCE OVER TIME</strong>

Jupyter-generated graph will go here.

Example:
Year → incidence rate per 100,000 people
</div>

</div>


<div class="figure-placeholder">

<div>
<strong>FIGURE 2 — PANCREATIC CANCER MORTALITY OVER TIME</strong>

Jupyter-generated graph will go here.

Example:
Year → mortality rate per 100,000 people
</div>

</div>


# Who Gets Pancreatic Cancer?

Understanding the population affected by the disease is important
because overall averages can hide major differences between groups.

## Age

<span class="placeholder">
Research the age distribution at diagnosis.
</span>

## Sex

<span class="placeholder">
Compare incidence and mortality between males and females.
</span>

## Race and Ethnicity

<span class="placeholder">
Investigate whether incidence, mortality, stage at diagnosis,
or survival varies among populations.
</span>

## Geography

<span class="placeholder">
Compare U.S. states, regions, or countries.
</span>


<div class="figure-placeholder">

<div>
<strong>FIGURE 3 — AGE DISTRIBUTION</strong>

Jupyter-generated age distribution graph.
</div>

</div>


<div class="figure-placeholder">

<div>
<strong>FIGURE 4 — INCIDENCE OR MORTALITY BY POPULATION GROUP</strong>

Jupyter-generated demographic comparison.
</div>

</div>


# What Is Pancreatic Cancer?

## What does the pancreas do?

<span class="placeholder">
Explain the endocrine and exocrine functions of the pancreas.
</span>

## Where does pancreatic cancer begin?

<span class="placeholder">
Explain the major pancreatic cancer cell types and identify
which form is the focus of this project.
</span>

## How does a normal cell become cancerous?

<span class="placeholder">
Explain mutations, abnormal signaling, uncontrolled growth,
invasion, and metastasis.
</span>


# Cancer Biology

Your course introduces the **Hallmarks of Cancer** as a framework
for understanding how cancer cells acquire capabilities that allow
them to grow, survive, invade, and spread.

The lecture identifies hallmarks including proliferative signaling,
evasion of growth suppressors, invasion and metastasis, replicative
immortality, angiogenesis, resistance to cell death, immune evasion,
inflammation, genome instability, and deregulated cellular energetics.

<span class="placeholder">
For pancreatic cancer, identify which hallmarks appear especially
important and explain why.
</span>


## Important Molecular Changes

| Gene / Pathway | Normal Function | What Changes? | Why It Matters |
|---|---|---|---|
| [KRAS] | [Research] | [Research] | [Research] |
| [TP53] | [Research] | [Research] | [Research] |
| [CDKN2A] | [Research] | [Research] | [Research] |
| [SMAD4] | [Research] | [Research] | [Research] |

<span class="placeholder">
Replace this table with findings from NCI, TCGA, peer-reviewed
papers, and other primary/authoritative sources.
</span>


# Risk Factors

Instead of simply listing risk factors, I will divide them into
categories.

## Genetic / Hereditary

<span class="placeholder">
Family history, inherited syndromes, germline mutations, etc.
</span>

## Behavioral

<span class="placeholder">
Smoking, alcohol, diet, physical activity, etc.
</span>

## Medical

<span class="placeholder">
Diabetes, chronic pancreatitis, obesity, etc.
</span>

## Environmental

<span class="placeholder">
Occupational and environmental exposures where evidence supports
an association.
</span>


## Risk Factor Table

<table class="research-table">

<tr>
<th>Risk Factor</th>
<th>Strength of Evidence</th>
<th>Modifiable?</th>
<th>Potential Intervention</th>
</tr>

<tr>
<td>[Factor]</td>
<td>[High / Moderate / Emerging]</td>
<td>[Yes / No]</td>
<td>[Intervention]</td>
</tr>

<tr>
<td>[Factor]</td>
<td>[High / Moderate / Emerging]</td>
<td>[Yes / No]</td>
<td>[Intervention]</td>
</tr>

<tr>
<td>[Factor]</td>
<td>[High / Moderate / Emerging]</td>
<td>[Yes / No]</td>
<td>[Intervention]</td>
</tr>

</table>


# How Is Pancreatic Cancer Detected?

## Symptoms

<span class="placeholder">
Describe common symptoms and — importantly — whether they tend
to appear early or later in the disease process.
</span>


## Imaging

<span class="placeholder">
Research CT, MRI, PET, endoscopic ultrasound, and other relevant
imaging approaches.
</span>


## Biopsy

<span class="placeholder">
Explain how tissue is obtained and how pathology confirms the diagnosis.
</span>


## Biomarkers

<span class="placeholder">
Investigate CA 19-9 and newer biomarkers while distinguishing
established clinical uses from experimental approaches.
</span>


## Genetic / Molecular Testing

<span class="placeholder">
Explain when molecular testing is used and how it affects treatment.
</span>


# The Detection Problem

> **The key question is not only "How do we detect pancreatic cancer?"
> but "How early can we detect it reliably?"**

<span class="placeholder">
Investigate why pancreatic cancer is difficult to detect early.

Possible research directions:

- Lack of early symptoms
- Anatomical location
- Lack of average-risk screening
- Biomarker limitations
- False positives / false negatives
- Tumor biology
- Difficulty distinguishing benign from malignant findings
- Healthcare access
</span>


<div class="figure-placeholder">

<div>
<strong>FIGURE 5 — STAGE AT DIAGNOSIS</strong>

Show the percentage of cases diagnosed as localized,
regional, distant, or unknown stage.
</div>

</div>


# Staging

## Stage 0

<span class="placeholder">
Research the applicable definition.
</span>

## Stage I

<span class="placeholder">
Research the applicable definition.
</span>

## Stage II

<span class="placeholder">
Research the applicable definition.
</span>

## Stage III

<span class="placeholder">
Research the applicable definition.
</span>

## Stage IV

<span class="placeholder">
Research the applicable definition.
</span>


# Stage vs. Survival

This is one of the most important analyses in this project.

<div class="figure-placeholder">

<div>
<strong>FIGURE 6 — FIVE-YEAR RELATIVE SURVIVAL BY STAGE</strong>

Compare localized, regional, and distant disease.
</div>

</div>


## What does this tell us?

<span class="placeholder">
Do not simply describe the graph.

Explain what the survival gap suggests about the importance
of early diagnosis and why stage at diagnosis may be an important
target for intervention.
</span>


# Current Treatments

## Surgery

<span class="placeholder">
Explain resection and which patients may be candidates.
</span>

## Chemotherapy

<span class="placeholder">
Describe major chemotherapy approaches and when they are used.
</span>

## Radiation

<span class="placeholder">
Describe its role in localized, locally advanced, or palliative treatment.
</span>

## Targeted Therapy

<span class="placeholder">
Research biomarker-directed treatments and which patients may benefit.
</span>

## Immunotherapy

<span class="placeholder">
Research which pancreatic cancer populations may benefit and why.
</span>

## Clinical Trials

<span class="placeholder">
Identify promising experimental approaches currently being tested.
</span>


# Treatment Is Changing

<div class="figure-placeholder">

<div>
<strong>FIGURE 7 — TIMELINE OF PANCREATIC CANCER TREATMENT</strong>

[Historical treatment]

→ [Modern chemotherapy]

→ [Precision treatment]

→ [Immunotherapy / targeted approaches]

→ [2026 developments]

</div>

</div>


# Precision Oncology

The same anatomical cancer does not necessarily behave identically
in every patient.

<span class="placeholder">
Investigate how genomic or molecular information can influence
treatment selection in pancreatic cancer.
</span>


# Survival and Prognosis

Rather than treating "life expectancy" as a single number, this project
will examine prognosis through multiple measures.

### 5-Year Relative Survival

[VALUE]

### Median Overall Survival

[VALUE]

### Survival by Stage

[INSERT GRAPH]

### Survival by Treatment

[INSERT GRAPH]

### Survival by Molecular / Clinical Subtype

[INSERT GRAPH IF DATA ARE AVAILABLE]


# What Are Patients Actually Dying From?

<span class="placeholder">
Investigate how progression, metastatic disease, organ involvement,
recurrence, and treatment complications contribute to mortality.

Do not assume that "death from cancer" means the same biological
process in every patient.
</span>


# The Biggest Unsolved Problem

## My Current Research Hypothesis

> **Pancreatic cancer mortality may be particularly difficult to reduce
> through treatment alone if most patients continue to reach diagnosis
> after the disease has already become difficult or impossible to cure surgically.**

<span class="placeholder">
Use evidence from the epidemiology, stage distribution, survival,
and treatment sections to decide whether this hypothesis is supported.
</span>


# What Solutions Already Exist?

<table class="research-table">

<tr>
<th>Solution</th>
<th>Current Evidence</th>
<th>Potential Benefit</th>
<th>Major Limitation</th>
</tr>

<tr>
<td>Risk-based surveillance</td>
<td>[Research]</td>
<td>[Research]</td>
<td>[Research]</td>
</tr>

<tr>
<td>Blood biomarkers</td>
<td>[Research]</td>
<td>[Research]</td>
<td>[Research]</td>
</tr>

<tr>
<td>Liquid biopsy</td>
<td>[Research]</td>
<td>[Research]</td>
<td>[Research]</td>
</tr>

<tr>
<td>Advanced imaging</td>
<td>[Research]</td>
<td>[Research]</td>
<td>[Research]</td>
</tr>

<tr>
<td>AI-assisted detection</td>
<td>[Research]</td>
<td>[Research]</td>
<td>[Research]</td>
</tr>

</table>


# My Proposed Solution

<div class="solution-box">

<h2>
Can risk-stratified early detection change the stage at diagnosis?
</h2>

<p>
<span class="placeholder">
This is a working project idea, not a proven clinical recommendation.
</span>
</p>

</div>


## Proposed Model

```text
General Population
        ↓
Risk Assessment
        ↓
Identify High-Risk Population
        ↓
Surveillance / Biomarker Testing
        ↓
Abnormal Result
        ↓
Confirmatory Imaging
        ↓
Earlier Diagnosis
        ↓
More Potentially Treatable Disease
        ↓
Potential Survival Improvement

---

## Source and Citation Statement

This project uses information from government agencies,
international cancer organizations, peer-reviewed scientific
literature, and publicly available cancer datasets.

Information from these sources has been summarized and analyzed
in my own words unless otherwise indicated.

Statistics and data visualizations identify their original
data source. Original graphs will be generated by the author
using Python/Jupyter Notebook.

External images, figures, and other copyrighted materials are
used only when their reuse terms permit it, and attribution is
provided where required.

---

## References

1. National Cancer Institute (NCI).  
   *Pancreatic Cancer.*  
   https://www.cancer.gov/types/pancreatic

2. National Cancer Institute, Surveillance, Epidemiology, and End Results (SEER).  
   *Cancer Stat Facts: Pancreatic Cancer.*  
   https://seer.cancer.gov/statfacts/html/pancreas.html

3. International Agency for Research on Cancer (IARC).  
   *Global Cancer Observatory: Pancreas.*  
   https://gco.iarc.who.int/

4. University of Oxford, Pancreatic Cancer Action, and University of Surrey
   *Pancreatic cancer could be diagnosed up to three years earlier.*  
   https://www.ox.ac.uk/news/2022-11-01-pancreatic-cancer-could-be-diagnosed-three-years-earlier

5. [ADD SOURCE HERE]

6. [ADD SOURCE HERE]

7. [ADD SOURCE HERE]