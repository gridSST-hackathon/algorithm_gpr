# algorithm_gpr
Code to interpolate via GP regression

Plan for code development during Hackathon
1. Extract ~7 days of pre-processed L2P data in region of interest -- use same region as Georgy from GOES to test?
2. Subtract coarse-resolution (CMC L4) field from L2P data to get anoamlies
3. Use anomalies to train GP regression model using code from https://gpytorch.ai/ 
4. Estimate (predict) anomaly field at 1 km (hourly?) and add back to coarse-resolution field.

