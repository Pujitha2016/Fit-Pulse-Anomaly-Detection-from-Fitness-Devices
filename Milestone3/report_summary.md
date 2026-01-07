Milestone 3: Anomaly Detection and Visualization

Objective:
To detect, label, and visualize anomalies in fitness data using statistical,
rule-based, and clustering approaches.

Anomaly Identification:
 - Residual Analysis: Prophet model residuals were analyzed to detect abnormal
 deviations in heart rate.  
 - Threshold-Based Detection: Domain-specific limits were applied for heart rate,
 sleep duration, stress level, and step count.
 - Cluster-Based Detection: Outliers were identified based on distance from
 cluster centroids obtained in Milestone 2.

Anomaly Labeling:
All detected anomalies were combined into a single label:
- '0' → Normal data
- '1' → Anomalous data

Visualization:
Interactive time-series plots were created to highlight anomalies in heart rate,
sleep patterns.

Conclusion:
The combined anomaly detection approach improves reliability and effectively
identifies abnormal health patterns in fitness device data.
