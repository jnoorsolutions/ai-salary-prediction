# 💼 Salary Prediction Web App (ML + Streamlit)

This project focuses on building a Salary Prediction model using a custom salary_prediction.csv dataset. The primary goal is to estimate an individual's salary based on key input features such as education level, years of professional experience, job role, industry sector, and location. Leveraging supervised machine learning techniques—particularly regression algorithms—the model aims to provide accurate salary estimations that can support data-driven decisions in HR analytics, talent acquisition, and career planning. The project includes data cleaning, feature engineering, model training, evaluation, and performance optimization, offering a complete end-to-end machine learning pipeline using:

- 🧠 **Keras** (for model training)
- 🧪 **Scikit-learn** (for preprocessing)
- 📊 **Pandas** and **NumPy** (for data handling)
- 🌐 **Streamlit** (for web interface)

The app predicts the **estimated annual salary** based on the following inputs:

- 🎓 Education Level
- 💼 Job Role
- 📆 Years of Experience

---

## 🚀 Features

- Easy-to-use Streamlit interface
- Uses a trained deep learning regression model (`.h5`)
- One-hot encoding for categorical variables
- StandardScaler for input normalization
- Real-time salary predictions

---
## 🧪 Application Url
https://annsalreg-gjsuaygxbrw2vvxaxrzma7.streamlit.app/

## 🧪 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/junaidnoor/ANN_SAL_REG.git
cd ANN_SAL_REG

2. Install dependencies
Make sure Python 3.11+ is installed.
pip install -r requirements.txt

3. Run the Streamlit app
streamlit run salary_app.py

📁 Project Files
File	Description
salary_app.py	Main application script
sal_reg_mdel.h5	Trained deep learning model
Sal_Reg_scaler.pkl	StandardScaler for input normalization
onehot_encoder_education.pkl	OneHotEncoder for education levels
onehot_encoder_job.pkl	OneHotEncoder for job roles
expected_columns.pkl	List of expected model input features

📌 Author
Made with ❤️ by **Junaid Noor**  
📧 Email: junaid.noor30@gmail.com

If you found this useful, please ⭐ the repository!
