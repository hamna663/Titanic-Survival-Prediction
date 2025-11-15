<h1 align="center">🚢 Titanic Survival Prediction</h1>

<p align="center">
  <img src="coverPhoto.png" alt="Titanic" style=" width:100%; margin: 2px; border-radius: 5px; "/>
</p>

---

<h2>📝 Project Overview</h2>

<p>
This project predicts the survival of passengers aboard the Titanic using machine learning techniques. 
It is based on the famous <a href="https://www.kaggle.com/c/titanic">Kaggle Titanic dataset</a> and aims to explore, visualize, and model the factors affecting passenger survival.
</p>

---

<h2>🔍 Features & Dataset</h2>

<p>The dataset contains the following key features:</p>

<ul>
  <li><strong>PassengerId</strong> – Unique ID of each passenger</li>
  <li><strong>Survived</strong> – Survival status (0 = No, 1 = Yes)</li>
  <li><strong>Pclass</strong> – Passenger class (1st, 2nd, 3rd)</li>
  <li><strong>Name, Sex, Age</strong> – Personal details</li>
  <li><strong>SibSp, Parch</strong> – Family details</li>
  <li><strong>Ticket, Fare, Cabin</strong> – Ticket and fare details</li>
  <li><strong>Embarked</strong> – Port of embarkation</li>
</ul>

---

<h2>📊 Project Workflow</h2>

1. **Data Exploration & Visualization**  
   - Analyze survival rates by gender, class, and age.  
   - Use plots to visualize patterns and distributions.

2. **Data Cleaning & Feature Engineering**  
   - Handle missing values.  
   - Transform categorical variables.  
   - Engineer new features (e.g., family size, title extraction).

3. **Modeling & Prediction**  
   - Train machine learning models (Logistic Regression, Random Forest, etc.).  
   - Evaluate models with metrics such as accuracy, precision, recall, and F1-score.  
   - Generate predictions on test data.

4. **Evaluation & Interpretation**  
   - Visualize feature importance.  
   - Interpret results to understand factors influencing survival.

---

<h2>💻 Installation & Usage</h2>

<p>Clone the repository and run the notebook:</p>

```bash
git clone https://github.com/hamna663/Titanic-Survival-Prediction.git
cd Titanic-Survival-Prediction
pip install -r requirements.txt
````
---

<h2>📈 Results</h2>

<p>The model predicts passenger survival based on the trained features. Key insights include:</p>

<ul>
  <li>Females had higher survival rates than males.</li>
  <li>First-class passengers had higher survival rates.</li>
  <li>Children had higher chances of survival compared to adults.</li>
</ul>

<p>Predictions can be exported for Kaggle submission using `submission.csv`.</p>

---

<h2>🛠 Tools & Libraries</h2>

<p>
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook
</p>

---

<h2>📚 References</h2>

<ul>
  <li><a href="https://www.kaggle.com/c/titanic">Kaggle Titanic Competition</a></li>
  <li>Seaborn & Matplotlib Documentation</li>
  <li>Scikit-learn Machine Learning Guide</li>
</ul>

---

<h2>🤝 Contributions</h2>

<p>
This project is beginner-friendly and open for improvements:
</p>
<ul>
  <li>Add more advanced feature engineering.</li>
  <li>Try additional models (XGBoost, LightGBM, ensemble methods).</li>
  <li>Improve data visualization and interpretation.</li>
</ul>

---

<h2>⚠ Disclaimer</h2>

<p>
This project is for educational purposes and demonstrates basic machine learning techniques on a classic dataset.
</p>
