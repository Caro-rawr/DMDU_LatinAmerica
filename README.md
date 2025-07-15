# 🔍 DMDU in Latin America

This repository documents a literature mapping of how Decision-Making under Deep Uncertainty (DMDU) is being applied across Latin America.  
It is part of the Latin America Working Group of the DMDU Society, focused on exploring tools and methods to navigate uncertainty in complex policy settings.

> ⚠️ *Note: While the repository interface is in English, the main analytical code and instructions are provided in both English and Spanish.*

## 📚 Project Overview

As part of our effort to systematically review and compare academic literature related to DMDU, we developed a framework to classify articles based on three core analytical modules:

1. Types and manifestations of uncertainty  
2. Stakeholders and participatory processes  
3. Implementation challenges in decision-making contexts  

The purpose of this framework is to identify patterns, gaps, and emphases across the literature — for instance, whether most studies address epistemic uncertainty, whether beneficiaries are considered as stakeholders, or which kinds of implementation challenges are most commonly cited in Latin American contexts.

To make this process scalable and replicable, we built a classification matrix linked to representative keywords, which can be extended to include additional dimensions such as methods (e.g., RDM, adaptive pathways), tools, or other relevant topics.

## ⚙️ What Does the Script Do?

The main `.Rmd` file (`Rmd/DMDU_LatinAmerica_analysis.Rmd`) performs automated classification and standardization of multiple academic articles using this keyword-based framework. It:

- Reads all `.pdf`, `.docx`, and `.txt` files in the target folder  
- Extracts and cleans their text  
- Applies the classification matrix  
- Calculates metrics such as:
  - Relative weight of each category  
  - Density per 1,000 words  
- Outputs a unified dataset for visualization and comparative analysis

## 📁 Repository Structure

- `Rmd/` → Reproducible RMarkdown script  
- `Data/` → Classification matrix (`dmdu_classification_matrix_with_keywords.xlsx`) and article corpus folder  
- `Scripts/` → Additional R scripts  
- `docs/` → Additional outputs or figures  

## 📝 License & Citation
Created with perseverance and collective effort by [Caro Cruz](https://github.com/Caro-rawr) and members of the Latin America Working Group of the DMDU Society.  
Feel free to reach out to me or to our representative, [Conceição de Maria Alves](cmaalves@gmail.com), if you'd like to contribute or collaborate.

This work is released under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.  
You are free to use, adapt, and share the material — as long as you provide proper attribution.

