# Fire Alarm Smoke Detection ??

This project uses Machine Learning to predict fire outbreaks based on environmental sensor data.

## Project Overview
The goal is to analyze sensor readings (Temperature, Humidity, CO2, etc.) to determine if a fire alarm should be triggered. This is a binary classification problem where safety and "Recall" (minimizing missed fires) are the top priorities.

## Technologies Used
* **Python**
* **Scikit-Learn** (for Random Forest/Decision Trees)
* **Pandas & NumPy** (for data processing)
* **Matplotlib/Seaborn** (for data visualization)

##  Dataset Features
The model analyzes the following inputs:
* **Temperature**
* **Humidity**
* **TVOC** (Total Volatile Organic Compounds)
* **eCO2** (CO2 equivalent concentration)
* **Pressure**

## How to Use
1. Clone the repository:
   `git clone https://github.com/Worku-Chemeda/smoke-detection.git`
2. Install dependencies:
   `pip install pandas scikit-learn matplotlib`
3. Run the notebook:
   Open `smoke_detection_improved.ipynb` in Jupyter or VS Code.

## ?? Results
* **Best Model:** (e.g., Random Forest)
* **Accuracy:** 98%
* **Key Insight:** Temperature and TVOC were the most significant predictors of fire.
