Objective

The objective of this milestone is to develop an interactive health anomaly detection dashboard that allows users to upload fitness data, 
process it through analytical pipelines, visualize heart/sleep/steps insights, detect anomalies, and export reports for further analysis.

Dashboard Workflow:
1.Data Upload:
Users upload fitness data in CSV or JSON format through the dashboard.

2.Pipeline Execution:
The system performs preprocessing, feature engineering, modeling, and anomaly detection with a single click.

3.Timestamp Mapping:
A timestamp column is detected or generated for visualization purposes.

4.Date Filtering:
Users select a date range to filter visual results.

5.Visualization:
Interactive Plotly charts display:
Heart rate trends + anomaly markers
Sleep duration patterns + abnormal highlights
Step count trends + low-activity alerts

6.Reporting:
Anomalies are summarized in a table and can be downloaded as a CSV report.

Tools & Technologies:
Streamlit, Plotly, Pandas, Google Colab, pyngrok.

Key Insights from the Dashboard:

Heart Rate Variability:
Sudden spikes in heart rate are flagged, indicating potential stress or cardiac irregularity.

Sleep Behavior:
Abnormally low (<4 hours) or high (>10 hours) sleep durations are detected and highlighted.

Physical Activity Trends:
Step count visualization helps identify sedentary behavior and low-activity days.

Outcome:
Milestone-4 successfully integrates previous components into a unified dashboard that is user-friendly,
interactive, and capable of detecting anomalies in health data with simple reporting features.


