# Drug Dose Optimization Using MATLAB Simulation

This MATLAB project estimates optimal drug dosages based on patient data using rule-based logic, data preprocessing, visualization, and PCA (Principal Component Analysis). It provides insights into dosage distribution and enables prediction for new patients through command-line input.

## 📂 Files

- `fods.mlx`: Main MATLAB Live Script implementing data loading, cleaning, normalization, PCA, rule-based dosage estimation, visualization, and user interaction.
- `drug1.csv`: Input dataset containing patient information (must be in the same directory).

## 🧪 Features

- **Data Cleaning:** Removes missing or invalid entries.
- **Normalization:** Standardizes `age` and `temperature` fields.
- **EDA & Visualization:**
  - Histograms and boxplots for age and temperature.
  - PCA plots to reduce dimensionality and visualize patient clustering.
- **Dosage Estimation:** Rule-based logic considering:
  - Age and temperature
  - Medical conditions (Depression, Diabetes, Hypertension)
  - Blood pressure and sugar level
- **Classification:** Categorizes dosage into `Low`, `Moderate`, or `High`.
- **User Interaction:** Command-line input for custom dosage prediction.

## 🧾 Dependencies

- MATLAB R2019b or newer (Live Script support)
- Ensure `drug1.csv` is present in the current MATLAB directory.

## ▶️ How to Run

1. Open `fods.mlx` in MATLAB.
2. Run all sections to clean data, generate plots, and calculate dosages.
