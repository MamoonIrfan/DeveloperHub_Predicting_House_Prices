# DeveloperHub_Predicting_House_Prices
Initial commit: Added Boston Housing Price Prediction project with preprocessing, Linear Regression model, and evaluation using RMSE.

🏡 Predicting House Prices using Boston Housing Dataset

📌 Overview

This project demonstrates how to predict house prices using the Boston Housing Dataset with a Linear Regression model.
The goal is to show a complete machine learning workflow: data preprocessing, model training, and evaluation using RMSE.

📊 Dataset

Boston Housing Dataset (506 rows × 14 columns).

Features include: crime rate, number of rooms, tax rate, etc.

Target variable: MEDV → Median house price.

🚀 Steps in the Project
1️⃣ Preprocessing

Load dataset and assign column names.

Normalize features using StandardScaler to bring them to the same scale.

2️⃣ Model Training

Split dataset into 80% training and 20% testing.

Train a Linear Regression model using scikit-learn.

3️⃣ Evaluation

Predict house prices on test data.

Evaluate using Root Mean Squared Error (RMSE).

Final RMSE ≈ 4.92, showing good model accuracy.

🛠️ Tech Stack

Python (3.8+)

Pandas (data manipulation)

NumPy (mathematical operations)

Scikit-learn (ML model & preprocessing)

📥 Installation & Usage

Clone the repository:

git clone https://github.com/your-username/boston-house-prices.git
cd boston-house-prices


Install required dependencies:

pip install -r requirements.txt


Run the script:

python house_price_prediction.py

📈 Results

Trained Linear Regression model successfully.

RMSE achieved: 4.92 on test dataset.

Model can be extended with other regression algorithms (Ridge, Lasso, Random Forest).

📌 Future Improvements

Add more regression models for comparison.

Build a visualization dashboard (using Matplotlib / Seaborn).

Deploy model using Flask or FastAPI.

🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Your Name

📧 Email: mamoonirfan786@gmail.com

🌐 www.linkedin.com/in/muhammad-mamoon-irfan-0632b5271
