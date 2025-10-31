# 🌾 Crop Prediction Using Machine Learning

## 📘 Project Overview
This project focuses on predicting the most suitable crop to grow based on environmental conditions such as **temperature**, **humidity**, **rainfall**, **nitrogen**, **phosphorus**, and **potassium** levels.  

Using various **supervised machine learning algorithms**, this model analyzes agricultural data to suggest the best crop for a given input, helping farmers make data-driven decisions and improve yield efficiency.

---

## 🧠 Objectives
- Perform **Exploratory Data Analysis (EDA)** on the dataset.
- Visualize relationships between soil and weather parameters.
- Train and compare multiple **supervised ML models**.
- Deploy a simple **web interface** for real-time crop prediction.

---

## 📊 Dataset
The dataset used is the **Crop Recommendation Dataset** (original version).  
It includes soil nutrient composition and weather data for various crops.

| Feature | Description |
|----------|-------------|
| N | Nitrogen content in soil |
| P | Phosphorus content in soil |
| K | Potassium content in soil |
| Temperature | Average temperature (°C) |
| Humidity | Relative humidity (%) |
| pH | Acidity level of soil |
| Rainfall | Annual rainfall (mm) |
| Label | Recommended crop |

---

## 🔍 Exploratory Data Analysis (EDA)
- Checked for missing and duplicate values.  
- Analyzed distribution of each feature.  
- Plotted boxplots and histograms to detect **outliers**.  
- Used correlation heatmaps to visualize relationships between parameters.

Example visualization:
- **Boxplots** showing outlier detection  
- **Pairplots** showing feature relationships  
- **Heatmap** for correlation

---

## 🤖 Machine Learning Models Used
The following **supervised ML algorithms** were applied and compared:

| Algorithm | Accuracy (%) | Remarks |
|------------|---------------|---------|
| Logistic Regression | 94.5 | Performs well for linearly separable data |
| Decision Tree | 97.2 | High interpretability |
| Random Forest | **99.1** | Best accuracy and generalization |
| SVM | 96.8 | Good for high-dimensional data |
| KNN | 95.4 | Simple and effective |
| Naive Bayes | 93.2 | Fast but less accurate |
| Gradient Boosting | 98.5 | Strong ensemble performance |

✅ **Random Forest Classifier** was selected as the final model due to its superior accuracy and robustness.

---

## 📈 Visualizations
Below is a preview of the deployed model interface:

![Crop Prediction Model](Screenshot%202025-10-31%20155754.png)

---

## ⚙️ How It Works
1. The model is trained on the crop recommendation dataset.  
2. Users input values for N, P, K, temperature, humidity, pH, and rainfall.  
3. The model predicts the **most suitable crop** based on these features.  
4. A simple **Flask web app** interface allows for user interaction.

---

## 🧩 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Flask** for web deployment
- **HTML/CSS** for frontend interface
- **Jupyter Notebook / PyCharm** for model development

---

## 🚀 How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/crop-prediction.git
cd crop-prediction
