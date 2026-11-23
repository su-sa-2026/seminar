1. Why Imbalanced Data Matters

Imbalanced data happens when one class has far fewer examples than another—for instance, 9,500 normal cases (0) and 500 abnormal cases (1), which is a 5% minority rate.

If a model guesses "normal" (0) every single time, it gets 95% accuracy while catching 0% of abnormal cases. That is why accuracy alone is misleading, and why the notebook tracks metrics like PR-AUC, Recall, Precision, and F1-score instead.

2. Core Sampling Methods Compared

Method	                    How It Works	                                    
---
Random Oversampling	        Duplicates existing minority (1) rows at random.  

---
SMOTE                      Creates new synthetic minority (1) points between nearby minority neighbors (best for continuous numeric features).

---
Random Undersampling       Randomly drops majority (0) rows.

---

