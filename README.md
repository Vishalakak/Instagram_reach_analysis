# 📊 Instagram Reach Analysis using Machine Learning

This project analyzes Instagram post performance using machine learning. It aims to predict the **reach** of a post based on features such as likes, comments, shares, saves, impressions, post type, and posting time.

---

## 🔍 Project Objective

To understand what factors influence Instagram reach and build a model that can **predict the expected reach** of a post. This helps content creators and marketers make data-driven decisions to improve engagement.

---

## 🧰 Tools & Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy**
- **Matplotlib, Seaborn** (for data visualization)
- **Scikit-learn** (for machine learning models)

---

## 📁 Dataset

The dataset contains Instagram insights for multiple posts with features such as:

- `Likes`
- `Comments`
- `Shares`
- `Saves`
- `Impressions`
- `Reach` (Target Variable)
- `Post_Type` (Image, Video, etc.)
- `Post_Time` (Datetime of post)

> Note: This is a sample dataset. You can replace it with your own Instagram business data exported from insights.

---

## 📊 Workflow

1. **Data Loading**
   - Load the dataset from a CSV file using pandas.

2. **Data Preprocessing**
   - Handle missing values
   - Extract useful time features (e.g., post hour)
   - Encode categorical features (e.g., Post_Type)
   - Normalize if needed

3. **Exploratory Data Analysis (EDA)**
   - Understand correlations and relationships between features
   - Visualize with heatmaps, bar charts, and scatter plots

4. **Model Training**
   - Split data into training and test sets
   - Train a Linear Regression model to predict `Reach`

5. **Evaluation**
   - Evaluate using R² Score and Mean Squared Error
   - Visualize actual vs. predicted reach

6. **Prediction**
   - Input new post data to predict its expected reach

---



## 📌 Key Insights

- Posts with more **saves and shares** tend to reach a wider audience.
- **Videos** usually get more reach than images.
- **Posting time** (evening hours) significantly affects reach.

---

## 🚀 How to Use This Project

1. Clone this repo or download the `.ipynb` file.
2. Make sure you have Jupyter Notebook or Google Colab.
3. Place the dataset (`instagram_data.csv`) in the same folder.
4. Open the notebook and run cells top to bottom.
5. Modify the new input data to test different reach predictions# Instagram_reach_analysis
