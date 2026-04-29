# Motor Fault Diagnosis Project

This project focuses on the detection and classification of motor faults (electrical and mechanical) using diagnostic signal fusion. By analyzing current and rotational data, the system identifies the healthy state of the unit as well as various types of induced damages. The analysis includes both the initial model development phase and subsequent verification on independent measurement sets.

---

### Project Structure
```text
.
├── Motor_Fault_Classification_Stacking_SHAP.ipynb  # Main analysis and modeling
├── Motor_Fault_Validation_and_Stability.ipynb      # Model validation on new data
└── data/                                           # Directory for CSV datasets
    ├── motors.csv                                  # Primary training dataset
    ├── Faulty-*.csv                                # New measurements (Faulty)
    └── Healthy-*.csv                               # New measurements (Healthy)
