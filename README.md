# Student-Habits-and-Academic-Performance-Analysis

# 📊 Student Learning Habits and Academic Performance Analysis

This project is a comprehensive Data Mining analysis focused on understanding the impact of student habits on academic performance. Conducted as part of the **Data Mining course** at Ho Chi Minh City Open University, the project uses synthetic data to simulate real-world learning behaviors and outcomes.

## 🧠 Project Objectives

- 🔍 Predict academic outcomes (GPA, exam scores) using regression models.
- 🧠 Classify dropout risk using classification models.
- 🧱 Cluster students into behavioral groups based on lifestyle, habits, and performance.
- 📈 Analyze correlations between study habits, mental health, and learning results.
- 📊 Discover frequent behavior patterns with association rule mining.
- 🚀 Propose personalized study strategies based on data insights.

## 📁 Dataset Description

- **Name:** Student Habits and Academic Performance (Synthetic)
- **Size:** 80,000 samples, 31 features
- **Categories include:**  
  - Study habits (study hours, attendance, tutoring)  
  - Lifestyle (sleep, exercise, screen time)  
  - Mental health & motivation (stress, anxiety, motivation level)  
  - Academic performance (GPA, exam scores, dropout risk)

> ⚠️ *Note: The dataset is synthetically generated and used for educational purposes only.*

## 🛠️ Tools & Techniques

- **Language:** Python  
- **Libraries:** Pandas, Scikit-learn, XGBoost, Seaborn, Matplotlib  
- **Algorithms:**  
  - Linear Regression, Decision Tree, Random Forest, XGBoost  
  - K-Means, DBSCAN  
  - Apriori Association Rule Mining  
- **Evaluation Metrics:** MAE, MSE, R², Accuracy, F1-Score, AUC

## 🧪 Key Results

- **GPA & Exam Score Prediction:** XGBoost achieved the highest accuracy among regression models.
- **Student Clustering:** K-Means and DBSCAN identified 3 clear behavioral groups:
  - High-performing students
  - Average students
  - At-risk students
- **Important Features:** `previous_gpa`, `attendance_percentage`, `time_management_score`, `motivation_level`
- **Insights:** Students with higher study hours and motivation levels tend to score better; high stress negatively impacts performance.

## 📊 Visualizations

The project includes:
- Correlation heatmaps
- Scatter plots of key features vs. exam scores
- Cluster visualizations using PCA
- Feature importance charts
- Association rule matrices

## 👥 Team Members

- Võ Thanh Hào - 2251050026  
- Nguyễn Đức Lâm - 2251052057  
- Nguyễn Phước Nguyên - 2251050050

## 📚 Report

> The full project report is available in Vietnamese [📄 here](./Báo_cáo_Khai_Phá_Dữ_Liệu_Nhóm_6.pdf)

---

## 🚀 How to Run the Code (Optional)

If you're uploading code files:

```bash
# Step 1: Install dependencies
pip install -r requirements.txt

# Step 2: Run notebook
jupyter notebook student_data_analysis.ipynb
