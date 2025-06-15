
# 📱 Clicks vs. Commitment: Predicting Productivity Based on Social Media Habits
An insightful machine learning project that analyzes how social media usage affects individual productivity using Python, data visualization, and regression analysis.

# 📈 Overview
In today's hyper-connected world, social media has become a daily routine for most individuals. However, excessive usage often leads to reduced focus and lower productivity. This project leverages data analysis and a Linear Regression model to evaluate and predict how time spent on various social platforms like WhatsApp, YouTube, Instagram, Facebook, and Snapchat influences productivity.

**Our objective:**
Track social media usage → Discover correlations → Predict productivity score
All built with accessible and explainable ML techniques.

# 🧩 Problem Space
Measuring the impact of digital behavior on productivity is challenging due to:

- Diverse platform usage patterns

- Individual behavioral variation

- Multi-platform distractions

We approach this with a two-step process:

1. Exploratory Data Analysis (EDA) – Discover patterns and correlations between platform usage and productivity scores

2. Prediction Modeling – Use a Linear Regression model to forecast productivity based on social media habits

# 📊 Dataset
- **Source:** Custom-collected dataset

- **Features:** Time spent (in hours) on WhatsApp, Instagram, YouTube, Facebook, Snapchat

- **Target:** Individual productivity score (continuous numeric value)

# 🔍 Analysis Highlights
- WhatsApp and YouTube showed stronger negative correlations with productivity

- Moderate usage of Instagram had mixed impacts depending on user behavior

- Regression analysis revealed that even small changes in usage time can affect productivity noticeably

- Simple, interpretable model — ideal for student or personal productivity tracking

# 🧠 Prediction with Linear Regression
**Why Linear Regression?**
- Easy to interpret and implement

- Works well for modeling continuous outcomes

- Provides visibility into the effect of each feature (social media platform) on productivity

The model was trained using a standard train-test split and evaluated using:

- R² Score

- Mean Absolute Error (MAE)

# 🚀 Tech Stack
- **Language:** Python

- **Libraries:**

  - Pandas, NumPy – Data handling

  - Matplotlib, Seaborn – Visualizations

  - Scikit-learn – Model building & evaluation

- **Model:** Linear Regression

- **Platform:** Jupyter Notebook

📁 Project Structure
```bash

├── social_media_vs_productivity.csv                              # Dataset

├── AICTE_STU680e6831e132f1745774641.ipynb                        # Main analysis notebook

├── data visualizations                                           # Heatmaps, scatterplots , histogram

├── README.md                                                     # Project documentation (you are here)

└── .gitignore                                                    # Standard Python ignores
🙌 Thank You!
This project emphasizes the importance of digital mindfulness in our daily lives.
Feel free to fork the repository, explore the code, and contribute improvements.
Stay focused — both digitally and personally.



