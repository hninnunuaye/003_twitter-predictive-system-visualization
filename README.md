# Data Visualization Analysis: Twitter as a Predictive System

This repository contains a comprehensive data visualization analysis and design enhancement report based on the academic paper **"Twitter as a predictive system: A systematic literature review"** (Cano-Marin, Mora-Cantallops, & Sánchez-Alonso, 2023).

## 📄 Project Files
* [View My Full Analysis Report](./Analysed%20Report%20(Done%20by%20Hnin).pdf)
* [View the Original Article](./Original%20Report%20(Twitter%20as%20a%20predictive%20system).pdf)

---

## 📋 Task Assignment Overview
The objective of this project is to apply data visualization principles to critically evaluate existing graphics in a published academic literature review, develop an optimized visual alternative for a selected data asset, and justify the underlying design choices to achieve maximum communication impact.

### Key Objectives Addressed:
1. **Evaluate Visualisation Techniques:** Critically assess the original paper's use of 13 visual elements (primarily dense data tables, an LDA coherence line chart, and a network word cloud) through the lens of Gestalt Principles of Visual Perception.
2. **Create an Improved Visualisation:** Select a high-density, complex visual from the paper and transform it into a highly intuitive graphic that highlights evolving data trends over time.
3. **Explain Design Choices:** Document an in-depth analysis detailing how the enhanced design principles actively lower cognitive load and improve data storytelling for a broad audience.

---

## 📊 Core Analysis Summary

### 1. Critique of Original Visuals
The original paper aggregates data from 3,250 final articles spanned across 15 distinct research domains. While the research methodology is highly robust, its presentation relies heavily on multi-page text tables and high-density heatmaps. While these tables accurately store precise numerical records, they rely heavily on the audience's verbal processing systems, making it time-consuming to map complex historical patterns, growth rates, and sudden data shifts.

### 2. The Enhanced Solution (Focus: Table 3 - Distribution of Publications)
To reveal the underlying story of how Twitter analytics research has shifted over time, **Table 3** (Distribution of publications per Year and Application Domain from 2009 to 2021) was extracted and completely redesigned. 

The data was transformed from a static numerical heatmap into an optimized **Multi-line Trend Chart** developed using Python (`pandas` + `matplotlib`) and refined in Microsoft Excel using advanced formatting rules.

### 3. Applied Design Innovations & Rationale
* **Decluttering Visual Noise:** Removed unnecessary gridlines, borders, and the primary vertical axis to eliminate visual clutter and lower cognitive load.
* **Proximity & Direct Data Labels:** Embedded data markers and labels directly onto key intersections along the timelines, leaning on the Gestalt principle of proximity to ensure reading ease.
* **Strategic Legend Placement:** Repositioned the application domain legends to sit on the right margin right next to the ending trend paths, utilizing the Gestalt principle of similarity to help viewers seamlessly match categories to their corresponding lines.
* **Empirical Storytelling:** The updated visual instantly emphasizes major global historical shifts, such as:
  * **Sentiment Analysis** maintaining a strong historical dominance that peaks distinctly in 2020.
  * An aggressive, dramatic surge in **Healthcare & Public Health** literature starting in 2020, capturing the global academic mobilization during the COVID-19 pandemic.

---

## 🛠️ Tech Stack & Methods Used
* **Data Evaluation:** Gestalt Principles of Visual Perception, Cognitive Load Theory (Knaflic, 2015).
* **Data Engineering & Initial Plotting:** Python (`pandas`, `matplotlib`).
* **Visual Polish & Formatting:** Microsoft Excel.

---
*Maintained by [Hnin Nu Nu Aye](https://github.com/hninnunuaye)*
