# ✈️ Turbofan Engine Predictive Maintenance
### *Predicting Remaining Useful Life (RUL) using Machine Learning & Power BI*

## 📌 Project Overview
This project addresses a critical challenge in aviation: **Predictive Maintenance**. Using the NASA C-MAPSS dataset, I developed a Machine Learning pipeline to predict the Remaining Useful Life (RUL) of turbofan engines. By predicting failure before it occurs, we can optimize maintenance schedules and reduce operational downtime.

The project demonstrates a full end-to-end data pipeline:
1. **Data Engineering:** Cleaning, scaling, and feature extraction from sensor data.
2. **Machine Learning:** Training a Random Forest Regressor to learn engine degradation.
3. **Business Intelligence:** Visualizing fleet health and model performance in Power BI.

## 📊 Key Results
- **Model:** Random Forest Regressor
- **Accuracy:** Final Test RMSE of **34.20 cycles**
- **Insight:** The model successfully captures the non-linear degradation of engine health, providing a reliable "Traffic Light" warning system for maintenance crews.

## 🛠️ Tech Stack
* **Language:** Python 3.10
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib,MYSQL
* **Visualization:** Power BI Desktop
* **Environment:** Jupyter Notebook

## 📈 Dashboard Features
The integrated **Power BI Dashboard** provides a "Control Room" view of the engine fleet:
* **Risk Assessment:** Donut charts classifying engines as *Healthy*, *Warning*, or *Critical*.
* **Predictive Accuracy:** A scatter plot comparing Predicted RUL vs. Actual RUL to validate model trust.
* **Priority List:** A sortable table identifying which Engine IDs require immediate inspection.

## 📁 Repository Structure
* `notebooks/`: Contains the `.ipynb` file with data cleaning and model training.
* `data/`: NASA FD001 training and test datasets.
* `results/`: The final CSV export used for the Power BI dashboard.
* `dashboard/`: The `.pbix` Power BI project file.

## 🚀 How to Run
1. Clone the repository: `git clone https://github.com/yourusername/Turbofan-Predictive-Maintenance.git`
2. Run the Jupyter Notebook to train the model and generate `Engine_Predictions_BI.csv`.
3. Open the Power BI file in `dashboard/` and refresh the data source to see the live visuals.

---
**Developed by:** Sudipta | Mechanical Engineering, MNNIT Allahabad
