Summary
"In this project, I performed a full-cycle validation of a Probability of Default (PD) model for a retail loan portfolio (~37.5k records). I assessed data quality, mathematical correctness of the PD implementation, and model stability across a 3-year economic cycle."
Key Technical Findings:
  Data Integrity: Handled 35% missing values in arrangement data and resolved critical join-key type mismatches.
  Risk Differentiation: Measured a Gini Coefficient of 57.65%, proving the model effectively ranks risk.
  Stability Analysis: Identified Model Drift in 2024 as actual defaults tripled, leading to a performance drop in the Gini (from 66% to 49%).
  Calibration: Analyzed an AvE Ratio of 5.0x, indicating a highly conservative model bias.
