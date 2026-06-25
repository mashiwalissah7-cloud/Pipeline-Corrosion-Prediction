# Pipeline Corrosion Prediction and Integrity Assessment System

A Python-based engineering project for predicting pipeline corrosion damage, estimating remaining wall thickness, assessing risk level, and recommending maintenance actions.

## Project Overview

Industrial pipelines can lose wall thickness over time due to corrosion. If the remaining wall thickness becomes too low, the pipeline may become unsafe and require repair, replacement, or increased inspection.

This project uses Python to perform a simplified pipeline integrity assessment. It analyzes both a single pipeline and multiple pipelines, then ranks them based on corrosion risk and maintenance priority.

## Objectives

* Calculate metal loss caused by corrosion.
* Estimate remaining wall thickness.
* Predict remaining useful life.
* Classify corrosion risk level.
* Recommend maintenance actions.
* Compare multiple pipelines.
* Rank pipelines by priority.
* Visualize pipeline risk and thickness trends.
* Export final results for reporting.

## Tools Used

* Python
* Jupyter Notebook
* pandas
* Matplotlib
* GitHub

## Key Features

* Single pipeline corrosion assessment
* Multiple pipeline comparison
* Remaining useful life prediction
* Risk level classification
* Maintenance recommendation system
* Service status classification
* Pipeline priority ranking
* Risk priority visualization
* Final engineering conclusion
* CSV export of results

## Engineering Workflow

The project follows this workflow:

```text
Input pipeline data
→ Calculate metal loss
→ Estimate remaining wall thickness
→ Predict remaining useful life
→ Classify risk level
→ Recommend maintenance action
→ Rank pipelines by priority
→ Visualize results
→ Generate final engineering conclusion
```

## Main Findings

The multiple-pipeline analysis identified Pipeline D as the highest-priority pipeline because it had the lowest remaining wall thickness, a critical risk level, and was already below the minimum safe thickness.

Pipeline B was also below the safe limit and should be scheduled for repair. Pipelines A, C, and E still had service life remaining but require continued monitoring and increased inspection frequency.

## Project Limitations

This project uses a simplified corrosion model based on constant corrosion rate. In real pipeline integrity engineering, corrosion behavior may depend on material type, pressure, temperature, coating condition, soil environment, fluid chemistry, inspection data, and industry standards.

The risk score and inspection priority system used here are simplified decision-support models for learning and portfolio demonstration.

## Author

Mashiwal M Issah
