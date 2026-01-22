### Case 56510 — Decision Explanation

**Model decision (threshold=0.20):** NON-FRAUD  
**Predicted fraud probability:** 0.0000

#### Key drivers pushing toward FRAUD
- **V7** (value=-7.318) contributed **+4.763** (↑ fraud risk)
- **V2** (value=4.113) contributed **+2.282** (↑ fraud risk)

#### Key drivers pushing toward NON-FRAUD
- **V1** (value=-20.809) contributed **-17.985** (↓ fraud risk)
- **V5** (value=-14.515) contributed **-12.880** (↓ fraud risk)
- **V14** (value=5.884) contributed **-8.876** (↓ fraud risk)

#### What this means
The model starts from a baseline risk level and adjusts the final risk using feature contributions.  
Positive SHAP contributions raise fraud risk; negative contributions reduce it. The final probability reflects the combined effect of all features.