# Pitch Probability Project

This repository contains a Jupyter notebook and a collection of pitch‐by‐pitch CSV files. It trains and evaluates three machine‐learning models (Random Forest and CatBoost) to predict baseball pitch types based on game context and release mechanics.
- **`PitchProbabilityFinal.ipynb`**  
Main notebook which:
1. Reads & concatenates all CSVs in the working directory  
2. Cleans data and engineers features  
3. Builds & compares Random Forest, KNN, and CatBoost models  
4. Evaluates performance and visualizes results

## 🚀 Getting Started

### 1. Clone this repo
```bash
git clone https://github.com/your-org/pitchProbabi.git
cd pitchProbability

pip install --upgrade pip
pip install pandas matplotlib scikit-learn catboost jupyterlab

jupyter lab   # or jupyter notebook
Open PitchProbabilityFinal.ipynb.
Run each cell in order:
	•	Data loading: concatenates all CSV files
	•	Preprocessing: cleans, imputes, encodes features
	•	Modeling: fits Random Forest, KNN, then CatBoost
	•	Evaluation & plots: displays accuracy, classification reports, and charts
