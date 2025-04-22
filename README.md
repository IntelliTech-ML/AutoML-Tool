# 🚀 AutoML Tool (Python + Shiny UI)

This repository contains a fully functional **AutoML tool** built using **Python** and the **Shiny for Python** framework. It allows users to upload a CSV dataset, preprocess the data, engineer features, compare multiple models, select and train the best model, and make predictions via an intuitive web interface.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Application Flow](#application-flow)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 Overview

This project aims to simplify the process of applying machine learning models to structured data by providing an easy-to-use GUI for users who may not be familiar with programming. It covers the entire ML workflow including:

- Data Uploading
- Preprocessing
- Feature Engineering
- Model Comparison
- Model Selection
- Prediction

The app is hosted locally using the Shiny server in Python and features sidebar-based navigation.

---

## 🎯 Features

✅ Upload CSV data directly into the app  
✅ Impute missing values (Drop, Mean, Median)  
✅ Change column data types (Integer, Float)  
✅ Apply encoding (One Hot or Label Encoding)  
✅ Create polynomial features  
✅ Select features and target variable  
✅ Compare regression and classification models  
✅ Select and train a model  
✅ Input new data to get predictions  

---

## 🛠 Technologies Used

- **Python**  
- **Shiny for Python**  
- **Pandas**  
- **Scikit-learn**  
- **Nest_asyncio** (for compatibility with Jupyter environments)  

---

## 💾 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/automl-tool.git
cd automl-tool
```

2. Install the required packages:
```bash
pip install pandas scikit-learn shiny nest_asyncio
```

---

## 🚀 Usage

Run the Shiny app using:
```bash
python app.py
```

The app will open in your default browser at `http://localhost:8000`.

---

## 🔄 Application Flow

1. **Upload File** – Upload your CSV file.
2. **Impute Missing Values** – Drop or fill missing data.
3. **Change Data Types** – Convert columns to int/float.
4. **Encoding** – Choose between One Hot or Label Encoding.
5. **Polynomial Features** – Generate interaction and polynomial terms.
6. **Feature Selection** – Choose input features and target.
7. **Model Comparison** – Automatically compare suitable models.
8. **Model Selection** – Choose the best model and train.
9. **Prediction** – Enter custom feature values to predict the target.

---

## 📁 Project Structure

```bash
.
├── app.py                  # Main Shiny app file
├── auto_ml_functions.py    # (Optional) Logic separation for reusability
├── README.md
```


## 📈 Future Improvements

- Add more advanced preprocessing methods (scaling, normalization)
- Hyperparameter tuning options
- Evaluation metrics dashboard
- Export trained model
- Save user sessions

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request. You can also open issues for bugs or feature requests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Ajay Soni** 

---

Give a ⭐ if you found this project helpful!

