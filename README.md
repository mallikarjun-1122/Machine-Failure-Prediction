# 🚀 Machine Failure Prediction using Machine Learning
This project predicts machine failure using multiple Machine Learning algorithms. It includes data preprocessing, visualization, model training, evaluation, and hyperparameter tuning.
---
## 📊 Dataset
The dataset contains the following features:
- Footfall
- Temperature Mode
- Air Quality (AQ)
- USS
- CS
- VOC
- RP
- IP
- Temperature
- Target: **fail (0 = No Failure, 1 = Failure)**
---
## 🧠 Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
---
## ⚙️ Workflow
1. Data Loading and Exploration  
2. Data Cleaning (handling missing values)  
3. Feature Scaling (StandardScaler)  
4. Data Visualization:
   - Correlation Heatmap  
   - Count Plot  
   - Pair Plot  
5. Model Training  
6. Model Evaluation:
   - Accuracy  
   - Confusion Matrix  
   - Classification Report  
   - ROC-AUC Score  
7. Hyperparameter Tuning (GridSearchCV)  
---
## 📈 Results
| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~86.7%   |
| Decision Tree       | ~79.3%   |
| Random Forest       | ~87.8%   |
| XGBoost             | ~85.7%   |
| Tuned Random Forest | ~87.3%   |
👉 **Best Model: Random Forest**
---
## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  
---
## ▶️ How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the project:
```bash
python main.py
```
---
## 📌 Future Improvements
- Add Deep Learning models  
- Deploy using Flask or Streamlit  
- Improve feature engineering  
- Add real-time prediction  
---
## 👨‍💻 Author
**Swarup**  
B.Tech – Computer Science and Design (CSD)
---
## 📄 License
This project is for educational purposes.
