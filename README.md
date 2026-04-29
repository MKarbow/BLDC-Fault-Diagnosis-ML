
This project focuses on the detection and classification of motor faults (electrical and mechanical) using diagnostic signal fusion. By analyzing current and rotational data, the system identifies the healthy state of the unit as well as various types of induced damages. The analysis includes both the initial model development phase and subsequent verification on independent measurement sets.

.
├── Motor_Fault_Classification_Stacking_SHAP.ipynb  # Main analysis and modeling / Główna analiza i modelowanie[cite: 1]
├── Motor_Fault_Validation_and_Stability.ipynb      # Model validation on new data / Walidacja modelu na nowych danych[cite: 2]
└── data/                                           # Directory for CSV datasets / Katalog na zbiory danych CSV
    ├── motors.csv                                  # Primary training dataset / Główny zbiór treningowy[cite: 1, 2]
    ├── Faulty-*.csv                                # New measurements (Faulty) / Nowe pomiary (Stany awaryjne)[cite: 2]
    └── Healthy-*.csv                               # New measurements (Healthy) / Nowe pomiary (Stany zdrowe)[cite: 2]
