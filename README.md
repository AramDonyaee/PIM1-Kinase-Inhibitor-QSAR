# Machine Learning QSAR Study for Investigating the Desired Characteristics of a Potential Inhibitory Molecule for PIM-1 Kinase

## Overview

This repository contains a comprehensive study focused on the design of inhibitory molecules targeting the PIM-1 kinase protein, which plays a significant role in various types of cancer. Leveraging machine learning techniques, particularly Quantitative Structure-Activity Relationship (QSAR) modeling, this project aims to identify potential inhibitors that can be further validated through molecular docking simulations.

## Table of Contents

- [Background](#background)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Usage](#usage)
- [To-Do](#to-do)

## Background

PIM-1 kinase is a serine/threonine kinase that is implicated in the regulation of cell survival, proliferation, and metabolism. Overexpression of PIM-1 has been linked to several cancers, making it a promising target for therapeutic intervention. This study utilizes machine learning approaches to predict the activity of potential inhibitors based on their chemical structure.

## Objectives

- Develop a robust QSAR model to predict the inhibitory activity against PIM-1 kinase.
- Identify and prioritize candidate molecules for further validation.
- Set the foundation for future molecular docking studies to evaluate binding affinities.

## Methodology

1. **Data Collection**: 
   - Gathered a dataset of known PIM-1 inhibitors and their corresponding biological activity from CHEMBL database.
   
2. **Feature Engineering**: 
   - Generated Pubchem molecular fingerprints to represent chemical structures.

3. **Model Development**: 
   - Employed a regression based machine learning algorithms (Random Forest) to build a predictive model.
   - Conducted model evaluation using performance metrics (R²).

4. **Model Interpretation**: 
   - Analyzed feature importance to understand key molecular features influencing activity.

## Usage

To run the code in this repository, open the Jupyter notebook and run the cells in the exact order, one by one.

## To Do
-[x] Perform molecular docking studies to evaluate the binding affinities of the identified inhibitors.
-[x] Optimize the QSAR model based on feedback and additional data.
-[x] Document the molecular docking methodology and publish the results in a peer-reviewed journal
