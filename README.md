# 🩺 AI Heart Disease Classification

This project uses Machine Learning to classify the presence of heart disease based on patient health data. The dataset includes various medical attributes such as blood pressure, cholesterol levels, and more.

## 🚀 Features

✅ Data preprocessing and visualization  
✅ Machine learning model training and evaluation  
✅ Uses Logistic Regression, Random Forest, and SVM for classification  
✅ Performance metrics like accuracy, precision, and recall  

## 📂 Project Structure

```
AI-Heart-Disease-Classification/
│── dataset/               # Contains heart disease dataset
│── models/                # Saved machine learning models
│── notebooks/             # Jupyter notebooks for EDA & training
│── src/                   # Source code for model training & evaluation
│   ├── data_preprocessing.py  
│   ├── train_model.py  
│   ├── evaluate.py  
│── requirements.txt       # Required Python libraries
│── README.md              # Project documentation
```

## 📊 Dataset

The dataset used for this project is a heart disease dataset that includes features such as:

- Age, Sex  
- Chest Pain Type  
- Blood Pressure, Cholesterol  
- Fasting Blood Sugar, ECG results  
- Maximum Heart Rate, Exercise-induced Angina  
- ST Depression, Slope, and more  

## 🔧 Installation & Setup

Clone this repository:

```bash
git clone https://github.com/Ashfaq03/AI-Heart-Disease-Classification.git
cd AI-Heart-Disease-Classification
```

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Preprocess Data:

```bash
python src/data_preprocessing.py
```

Train Model:

```bash
python src/train_model.py
```

Evaluate Model:

```bash
python src/evaluate.py
```

## 📈 Results

The best-performing model achieves an accuracy of **XX%**.  
Precision, Recall, and F1-score are used to evaluate performance.

## 🛠️ Technologies Used

- Python, Pandas, NumPy  
- Scikit-Learn, Matplotlib, Seaborn  
- Jupyter Notebook  

## 📌 Future Improvements

- Hyperparameter tuning for better accuracy  
- Implementing deep learning models  
- Deploying as a web application  

## 📝 License

This project is open-source and available under the **MIT License**.

## 👨‍💻 Author

**[Syed Ashfaquddin](https://www.linkedin.com/in/syedashfaquddin/)**  

Feel free to contribute or suggest improvements! 🚀

