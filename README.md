# 🌍 Earthquake Magnitude Prediction using LSTM

## 📌 Overview
This project leverages **Long Short-Term Memory (LSTM) neural networks** to predict earthquake magnitudes based on historical seismic data. By analyzing past earthquake records, the model aims to provide accurate magnitude predictions, contributing to better preparedness and risk assessment.

---

## 📊 Dataset Source
We use the **Earthquake Dataset**, which contains detailed historical earthquake data. You can obtain this dataset from **[Kaggle](https://www.kaggle.com/datasets/usgs/earthquake-database)**.

🔹 **Steps to get the dataset:**  
1. Download the dataset from Kaggle.  
2. Place the downloaded dataset in the same directory as the code files.

---

## ⚙️ Dependencies
Before running the project, ensure you have the following dependencies installed:

- **Python** (>=3.6)
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**
- **TensorFlow/Keras** (included in TensorFlow 2.x)

### 💡 Install Dependencies
Run the following command to install all required libraries:
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

---

## 🚀 Getting Started
Follow these steps to run the code and make earthquake magnitude predictions:

1️⃣ **Clone the repository** or download the code to your local machine.
```bash
git clone https://github.com/your-username/earthquake-magnitude-prediction.git
cd earthquake-magnitude-prediction
```

2️⃣ **Download the earthquake dataset** from Kaggle and place it in the project directory.

3️⃣ **Run the script** to start training the LSTM model:
```bash
python earthquake_magnitude_prediction.py
```

🔹 The script will:
- Load and preprocess the dataset
- Train the LSTM model
- Make predictions
- Display and save evaluation results

---

## 🏗️ Project Workflow
This project follows a structured approach to earthquake magnitude prediction:

### 1️⃣ Data Preprocessing
- Load and clean the earthquake dataset.
- Perform **feature engineering** to extract useful information.
- Split the dataset into **training (80%)** and **testing (20%)** sets.

### 2️⃣ LSTM Model Building
- Define the LSTM architecture, including **layers, activation functions, and hyperparameters**.
- Compile the model with an appropriate **loss function and optimizer**.

### 3️⃣ Model Training
- Train the LSTM model on the prepared dataset.
- Monitor training performance and fine-tune hyperparameters if necessary.

### 4️⃣ Making Predictions
- Use the trained model to predict earthquake magnitudes based on test data.

### 5️⃣ Evaluation
- Evaluate the model’s performance using:
  - **Mean Absolute Error (MAE)**
  - **Root Mean Square Error (RMSE)**
  - **Data visualizations**
- Save results for future analysis.

---

## 📈 Results & Visualization
- The model’s performance metrics will be displayed in the console.
- Prediction results and evaluation plots will be saved for analysis.

---

## 🎯 Future Enhancements
🔹 **Improve Model Performance:** Tune hyperparameters, increase dataset size, and explore different deep learning architectures.  
🔹 **Feature Engineering:** Integrate additional geophysical factors such as depth, location, and seismic wave properties.  
🔹 **Real-Time Prediction:** Implement real-time earthquake magnitude forecasting using live seismic data.

---

## 📜 License
This project is **open-source** and licensed under the **MIT License**.

---

## 💡 Contributing
Contributions are welcome! If you’d like to improve the project, feel free to fork the repository, make changes, and submit a pull request.

---

## 👨‍💻 Developer

Develop by Kishore M

