
# PMGSY Scheme Classifier

This project leverages **machine learning** to intelligently classify rural infrastructure projects under the **Pradhan Mantri Gram Sadak Yojana (PMGSY)** scheme using IBM Cloud AutoAI. It involves data preprocessing, model training, evaluation, deployment, and API testing — all hosted on **IBM watsonx.ai Studio**.

---

## 🚀 Project Overview

The goal of this project is to:

- Predict outcomes or classify PMGSY project records
- Use a trained model to identify characteristics based on input fields
- Deploy the model as an API for real-time predictions

---

## 🧠 Model Details

- **Model Type**: XGBoost Classifier
- **Training Method**: IBM AutoAI
- **Performance Metric**: F1 macro score = **0.861**
- **Deployment Type**: Online REST API

---

## 🗂️ Project Structure

```
📦pmgsy-scheme-classifier/
├── PMGSY_Scheme_Classifier_Exp1.ipynb       # Notebook used to build and train the model
├── pmgsy_clean.csv                          # Cleaned dataset (original version)
├── pmgsy_enhanced_clean.csv                 # Enhanced cleaned version used for best results
├── PMGSY_Scheme_Deployment_test_result.json # JSON output from deployed model test
├── screenshots/                             # Screenshots of IBM Cloud setup
└── README.md                                # This file
```

---

## ⚙️ Technologies Used

- 🧠 IBM Watsonx.ai Studio (AutoAI, Deployment Spaces)
- 📊 Python (Notebook)
- ☁️ IBM Cloud Lite
- 🔍 GitHub for version control

---

## 📈 How to Reproduce

1. Upload the `pmgsy_enhanced_clean.csv` to IBM Cloud
2. Run AutoAI with classification goal
3. Deploy the best model (e.g., XGB Classifier) as an **Online** service
4. Use the provided `JSON` format to test your deployment
5. (Optional) Clone this repository to explore the code and data

---

## 🔗 API Endpoint

Model deployed at IBM watsonx.ai as an **Online deployment**  
Use the API reference section in IBM Cloud to submit real-time JSON test data.

---

## 📸 Screenshots

See the `/screenshots` folder for:
- Model creation
- Deployment setup
- JSON API test results

---

## 🙌 Author

SRIHARI  
[GitHub](https://github.com/srihari3007)

---

## 📄 License

This project is under the [MIT License](LICENSE).
