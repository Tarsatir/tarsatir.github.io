---
layout: page
title: Inferring Economic Landscapes
description: Mapping barriers to human development through stochastic modelling.
img: assets/img/13.png
importance: 1
category: work
---




## Project Overview

Understanding social mobility is critical for addressing inequality and fostering sustainable development. This project develops a **non-parametric, multidimensional approach** to model social mobility using Markov chains. By estimating transition matrices, we uncover the hidden dynamics of mobility across socio-economic dimensions, enabling a nuanced understanding of structural and exchange mobility patterns.

---

## Visual Insights

### Pathways and Bottlenecks in Social Mobility

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/styl_potential.png" title="Social Mobility Pathways" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The figure illustrates that existing pathways might follow certain sequences and reveal information about the order of successful interventions, or where bottlenecks lie. The shortes path might or might not be the most efficient path to improve overall welfare. 
</div>

**Why This Matters:**  
Identifying common pathways and bottlenecks in social mobility enables better policy design by revealing where structural barriers exist. By targeting these barriers, policymakers can enhance access to opportunities and improve socio-economic resilience.

---

## Key Contributions

- **Theoretical Framework:** A novel method for transition matrix estimation tailored to multidimensional social mobility analysis.
- **Data Integration:** Utilization of high-quality longitudinal household datasets from EUROSTAT and Dutch CBS.
- **Error Estimation:** Comprehensive uncertainty quantification through Frobenius norms and comparisons of cross-sectional data distributions.
- **Policy Insights:** Data-driven guidance for designing equitable interventions to reduce poverty and enhance social equity.

---

## Research Methodology

Our approach models household-level transitions in socioeconomic states using Markov chains. The methodology consists of three main components:

- **Data Preprocessing:** Discretizing state-space dimensions like income, education, and occupation.
- **Matrix Estimation:** Applying optimization techniques to infer the most probable transition matrices from observed data.
- **Analysis:** Calculating relevant metrics such as mixing times, recurrence rates, and resilience indicators.

---

### Research Workflow and Core Findings

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/methodology.jpg" title="Research Workflow" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/results.jpg" title="Core Findings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The left panel outlines the research workflow from data collection to policy recommendations. The right panel highlights key findings about socio-economic mobility across different countries.
</div>

**Why This Matters:**  
The research workflow ensures a systematic and replicable process for analyzing social mobility dynamics, leading to actionable insights that inform public policy and resource allocation.

---

## Results & Policy Implications

### Social Mobility Disruptions from the COVID-19 Pandemic

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/COVID_mobility.png" title="Pandemic-Induced Barriers" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The figure illustrates changes in social mobility patterns during the COVID-19 pandemic, emphasizing newly emerged barriers and reduced mobility potential.
</div>

**Key Insight:**  
The COVID-19 pandemic significantly reduced social mobility, particularly in countries like the Netherlands, where a unique "triple-well" potential emerged, creating substantial upward mobility barriers.

---

### Multidimensional Poverty Analysis

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MPI_panel.png" title="Income and Education Landscapes" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The figure displays socio-economic landscapes, mapping income (PY010) against education (PE040) for three countries, revealing key mobility pathways.
</div>

**Policy Insight:**  
By analyzing multiple dimensions such as income and education, informed by the OPHI MPI framework, we can pinpoint the most vulnerable groups and identify strategic intervention points for enhancing mobility.

---

### Future Research Directions

<div class="caption">
    Future work will explore additional social mobility dimensions, linking this framework to welfare economics literature. This will enable projecting high-dimensional mobility spaces into simplified metrics, guiding policy design toward maximizing welfare state occupation and improving social equity outcomes.
</div>