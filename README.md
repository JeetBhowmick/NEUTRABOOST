# NEUTRA-BOOST: Imbalanced Multiclass Boosting Framework

## Overview

NEUTRA-BOOST is a novel gradient boosting framework designed to address severe class imbalance in multiclass classification problems.

## Problem Statement

Traditional boosting methods struggle with minority class prediction in highly imbalanced datasets. NEUTRA-BOOST addresses this limitation through adaptive learning strategies.

## Key Results

* Evaluated on a 10,000-sample dataset with 17× class imbalance
* Achieved Macro-F1 = 0.777
* Outperformed:

  * XGBoost by +3.98%
  * LightGBM by +5.03%
![Comparison](NewFolder/macroF1.png) 
* Improved worst-class F1 score by over 100%
![Comparison](NewFolder/worstF1.png) 
## Performance Comparison

![Model Comparison](NewFolder/performance1.png)
## Core Ideas (High-Level)

* Margin-adaptive sample weighting
* Class-aware gradient scaling
* Specialized handling of confusing class pairs
## System Overview

The framework follows a structured boosting pipeline:

Data → Preprocessing → Adaptive Boosting → Class-Aware Optimization → Predictions  
![Architecture](NewFolder/architecture.png)
## Status

📄 Research work under review (full paper not publicly shared)

## Note

Detailed implementation and methodology are withheld until publication.

