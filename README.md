# 📊 Play Store Apps Data Cleaning & Analysis  

## 📌 Project Overview  
This project aims to clean and analyze a dataset of Google Play Store apps. The dataset contains information on app categories, ratings, reviews, installs, pricing, and more. By cleaning and preprocessing the data, we uncover key insights that can help businesses optimize app strategies.

## 🔍 Dataset  
- **Source**: Google Play Store Dataset  
- **Attributes**:
  - `App`: Name of the application
  - `Category`: Type of app
  - `Rating`: User rating
  - `Reviews`: Number of reviews
  - `Size`: App size
  - `Installs`: Number of downloads
  - `Type`: Free/Paid
  - `Price`: App price
  - `Content Rating`: Age group suitability
  - `Genres`: App genres  
  - `Android Version`: Minimum required Android version  

## 🛠️ Data Cleaning & Preprocessing  
The following steps were performed:
✅ Handling missing values  
✅ Removing outliers (Using IQR)  
✅ Converting data types (Size, Price, Installs)  
✅ Fixing inconsistent values  

## 📊 Key Insights & Findings  
- **Most Expensive App:** 📌 `app_name_here` priced at `$value_here`
- **Highest Number of Apps in Genre:** `genre_here`
- **Average Size of Free vs Paid Apps:** `size_free_here` vs `size_paid_here`
- **Estimated Google Revenue from Apps with 5M+ Installs:** `$revenue_here`  
- **Correlation Analysis:** Ratings, reviews, size, and price relationships visualized.

## 📈 Visualizations  
| Insight | Visualization |
|---------|--------------|
| Rating Distribution | 📊 Histogram |
| Price Outliers | 📉 Box Plot |
| Free vs Paid Apps | 📊 Bar Chart |
| Content Rating Distribution | 📊 Stacked Bar Chart |

## 🚀 How to Run the Notebook  
1️⃣ Clone this repository:  
```bash
git clone https://github.com/your_username/your_repo_name.git
```
2️⃣ Install required libraries:  
```bash
pip install pandas numpy matplotlib seaborn
```
3️⃣ Run `Playstore_Data_Cleaning.ipynb` in Jupyter Notebook.

## 📌 Next Steps  
🔹 Perform sentiment analysis on user reviews.  
🔹 Build a machine learning model to predict app success.  
🔹 Automate data cleaning with functions.
