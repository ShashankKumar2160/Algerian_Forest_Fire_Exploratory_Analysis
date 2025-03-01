# 🔥 Exploratory Data Analysis (EDA) of Algerian Forest Fires

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Algerian Forest Fires Dataset** from the UCI Machine Learning Repository. The dataset contains meteorological and fire-related data collected from two regions in Algeria to help analyze fire occurrences and environmental patterns.

## 📂 Dataset Overview
- **Total Instances:** 244
- **Total Attributes:** 13
- **Regions Covered:**
  - **Bejaia Region (1st region)**
  - **Sidi Bel-abbes Region (2nd region)**
- **Target Variable:** Fire occurrence (`fire` or `not fire`)

## 🏷️ Features
| Feature | Description |
|---------|-------------|
| `Date` | Date of observation |
| `Temperature (°C)` | Daily average temperature |
| `RH (%)` | Relative humidity |
| `Ws (km/h)` | Wind speed |
| `Rain (mm)` | Total daily rainfall |
| `FFMC` | Fine Fuel Moisture Code (fire risk indicator) |
| `DMC` | Duff Moisture Code (moisture in medium fuels) |
| `DC` | Drought Code (long-term moisture deficit) |
| `ISI` | Initial Spread Index (fire spread potential) |
| `BUI` | Buildup Index (total fuel availability) |
| `FWI` | Fire Weather Index (comprehensive fire risk indicator) |
| `Classes` | Fire occurrence (`fire` = 1, `not fire` = 0) |

## 🎯 Objectives
- Understand **fire occurrence patterns** based on meteorological variables.
- Identify **correlations** between weather conditions and fire spread.
- Perform **data visualization** and statistical analysis.
- Develop insights for **fire prevention and management**.

## 📊 EDA Steps
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical data
   - Data type conversions
2. **Descriptive Statistics**
   - Summary statistics (mean, median, mode, etc.)
   - Checking for outliers
3. **Data Visualization**
   - Distribution plots (histograms, boxplots)
   - Correlation heatmaps
   - Time-series analysis
4. **Feature Engineering**
   - Creating new meaningful features
   - Removing redundant columns

## 🛠️ Tools & Libraries
- **Python**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning** *(optional)*: `scikit-learn`

## 📌 Key Findings
- **Temperature & Fire**: Higher temperatures correlate with increased fire occurrences.
- **Humidity & Fire**: Lower humidity is associated with a higher risk of fire.
- **Wind Speed**: Stronger winds can accelerate fire spread.
- **FWI Index**: A high Fire Weather Index strongly indicates fire-prone conditions.

## 🚀 How to Run the Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/ShashankKumar2160/Algerian_Forest_Fire_Exploratory_Analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd algerian-forest-fire-eda
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook eda_algerian_forest_fire.ipynb
   ```

## 📌 Future Work
- Build a **fire prediction model** using classification algorithms.
- Implement **real-time fire risk monitoring** using weather data.
- Expand the analysis with **satellite imagery** and GIS tools.

## 📜 License
This project is licensed under the **MIT License**.

## 🙌 Contributions
Contributions, issues, and feature requests are welcome! Feel free to open a pull request or an issue.

📧 **Contact:** shashankkumar2160@gmail.com  
🔗 **GitHub Repository:** [GitHub Link](https://github.com/ShashankKumar2160/Algerian_Forest_Fire_Exploratory_Analysis)

