# FitPulse Health Anomaly Detection from Fitness Devices

## Milestone 1: Data Collection & Preprocessing

### Objective
To ingest raw fitness data from CSV/JSON files, clean and normalize timestamps,
handle missing values, and generate a clean dataset aligned to 1-minute intervals
for further analysis and anomaly detection.


## Dataset Description
The dataset contains fitness data collected from wearable devices:
- id
- timestamp: Date and time of record
- heart_rate: Heart rate in bpm
- steps: Step count values
- sleep: Sleep status (0 = awake, 1 = asleep)

The raw dataset contains missing and invalid values to simulate real-world data.

## Preprocessing Steps
1. Data ingestion and schema validation using Pandas.
2. Timestamp normalization and conversion to UTC format.
3. Handling missing values using interpolation, forward fill, and mode.
4. Resampling and aligning data to consistent 1-minute intervals.
5. Generating a clean dataset for further analysis.

## Output
A cleaned dataset (`clean_fitness_data.csv`) with normalized timestamps,
no missing values, and consistent 1-minute alignment.

## Status
Milestone 1 completed successfully.

