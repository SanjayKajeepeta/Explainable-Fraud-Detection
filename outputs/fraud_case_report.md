### Case 1146 — Decision Explanation

**Model decision (threshold=0.20):** FRAUD  
**Predicted fraud probability:** 1.0000

#### Key drivers pushing toward FRAUD
- **V8** (value=-37.353) contributed **+18.038** (↑ fraud risk)
- **V14** (value=-9.073) contributed **+14.420** (↑ fraud risk)
- **V7** (value=-18.751) contributed **+12.435** (↑ fraud risk)

#### Key drivers pushing toward NON-FRAUD
- **V1** (value=-13.193) contributed **-11.313** (↓ fraud risk)
- **V22** (value=-8.887) contributed **-7.332** (↓ fraud risk)

#### What this means
The model starts from a baseline risk level and adjusts the final risk using feature contributions.  
Positive SHAP contributions raise fraud risk; negative contributions reduce it. The final probability reflects the combined effect of all features.