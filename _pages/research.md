---
permalink: /research/
title: "Research"
---

I'm currently working with Dr. Erica Graham to understand the impact of hormonal fluctuations on lesion growth in endometriosis. The LESIOn model (Local Estradiol Synthesis in Infertility Onset) is the first incorporating receptor-binding dynamics and local E2 synthesis by lesion cells in endometriosis.

## Motivation

Endometriosis is a gynecological condition that presents with symptoms ranging from severe pelvic pain to infertility. It is characterized by growth of endometrial tissue outside of the uterine cavity. Diagnosis typically takes around 4-12 years due to the invasive nature of diagnostic surgery and widespread medical bias against female patients. Diagnosis is typically visually confirmed by presence of lesions after laparoscopic surgery, though imaging techniques such as ultrasound can also be used, while treatment is symptoms-based and typically involves progestin medication, NSAIDs, or hysterectomy. Endometriosis is grossly understudied, evident from the limited diagnostic and treatment options.

## Methods

We build upon pre-existing models: [Miller (2025)](https://doi.org/10.1098/rsif.2025.0076) and [Graham (2023)](https://doi.org/10.1016/j.mbs.2023.108979), adding our own modifications for estrogen receptor binding dynamics. We use ode15s in MATLAB R2024b to simulate a model containing (1) immune cell dynamics, (2) uterine cell profile, (3) steroid hormone levels, (4) pituitary hormone levels, and (5) estrogen receptors. We believe this model better reflects risk factors for disease onset and provides valuable insight into potential treatment efficacy. We added a term for E2 synthesis by lesions into FSH-stimulated oocyte development to investigate the role of local E2 synthesis on oocyte quality and growth.

## Results & Next Steps

We have found a correlation between the concentration of ER-beta (an estrogen receptor implicated in endometriosis onset) and disease severity, with higher ER-beta concentrations in more advanced disease. We were also able to distinguish disease states based on the amount of E2 (estrogen) synthesized by lesions. The LESIOn model explains endo-associated infertility as a side effect of E2 synthesis by lesion cells.

Work for this project is posted to [GitHub](https://github.com/suzannasem/endo)). 
