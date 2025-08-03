# Titanic Project

## 📌 Overview
This project explores the Titanic dataset through data cleaning, preprocessing, exploratory analysis, and machine learning in Python, comparing logistic regression and random forest models. It concludes with a Power BI dashboard, highlighting both analytical and visualisation skills across tools.

## 🛠️ Tools & Technologies
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Power BI
- Jupyter Notebook

## 📁 Project Structure
- Part 1: Data Cleaning & Pre-processing
- Part 2: Exploratory Data Analysis
- Part 3: Machine Learning
- Part 4: Interactive Dashboard


## 🚀 Features
- [✓] Data cleaning and transformation
- [✓] Exploratory data analysis (EDA)
- [✓] Data visualisation using Power BI / matplotlib / seaborn
- [✓] Predictive modelling (Logistic Regression vs Random Forest)

## 📷 Screenshots
<figure>
  <img width="600" height="472" alt="Feature Correlation" src="https://github.com/user-attachments/assets/2d898f30-dc93-4518-88cd-5414e5b85e5e" />
  <figcaption><em>Figure 1: Correlation heatmap showing relationships between key passenger features.</em></figcaption>
</figure>

<figure>
  <img width="700" height="394" alt="Power BI Dashboard Main Summary" src="https://github.com/user-attachments/assets/df5eff2a-cf55-452d-a12a-6b51e12135e5" />
  <figcaption><em>Figure 2: Power BI dashboard overview showing survival distributions by class, gender, and model performance.</em></figcaption>
</figure>

<img src="https://github.com/user-attachments/assets/2d898f30-dc93-4518-88cd-5414e5b85e5e" width="600" alt="Feature Correlation" />

*Figure 1: Correlation heatmap showing relationships between key passenger features.*

<img src="https://github.com/user-attachments/assets/df5eff2a-cf55-452d-a12a-6b51e12135e5" width="700" alt="Power BI Dashboard Main Summary" />

*Figure 2: Power BI dashboard overview showing survival distributions by class, gender, and model performance.*

## 🔍 Key Insights
- Sex was the strongest predictor of survival: Women had a significantly higher survival rate than men, reflecting the "women and children first" evacuation policy.
- Passenger class influenced survival: First-class passengers had the highest survival rates, while third-class passengers had the lowest - highlighting socioeconomic disparities in access to lifeboats.
- Younger passengers had better outcomes: Children had increased chances of survival, particularly in higher classes.
- Fare price correlated with survival: Passengers who paid higher fares (often in first class) were more likely to survive, reinforcing the role of wealth and privilege.
- Embarkation port had some effect: Passengers who boarded at Cherbourg (C) had slightly higher survival rates, possibly linked to class distribution.
- Random Forest outperformed Logistic Regression: Random Forest captured complex, non-linear patterns in the data, leading to better predictive performance.

## 📦 Installation (for Python projects)
```bash
git clone https://github.com/Harry-N-00/Titanic-Project.git
cd Titanic-Project
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
