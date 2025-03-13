Customer Churn Prediction using ANN
Hey there! 👋

This project is all about predicting customer churn using an Artificial Neural Network (ANN). We've cleaned the dataset, built a deep learning model using TensorFlow, and deployed it with Streamlit to make it super easy to use!

What’s Inside?
✅ Data Cleaning & Feature Engineering – We processed the raw data to improve model accuracy.
✅ Model Training – Used TensorFlow to build and fine-tune an ANN model.
✅ Deployment – Hosted the model on Streamlit so you can make predictions with a simple UI.

Tech Stack & Libraries Used
To make this work, we used:
📌 tensorflow==2.15.0
📌 pandas & numpy (for data handling)
📌 scikit-learn (for preprocessing & evaluation)
📌 tensorboard (for tracking training)
📌 matplotlib (for visualizations)
📌 streamlit (for deployment)
📌 scikeras (for seamless integration with Keras)

How to Run the Project?
Wanna try it out? Follow these steps:

1️⃣ Clone the repository:

bash
Copy
Edit
git clone https://github.com/psai0011/customer-churn-prediction-ann.git
cd customer-churn-prediction-ann
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
Now, just open the link in your browser and start predicting customer churn! 🚀

Project Structure
graphql
Copy
Edit
ANNCLASSIFICATION/
│── logs/                     # Training logs  
│── regressionlogs/           # Regression logs  
│── app.py                    # Streamlit app  
│── Churn_Modelling.csv       # Dataset  
│── experiments.ipynb         # Model experiments  
│── hyperparametertuning.ipynb # Hyperparameter tuning  
│── label_encoder_gender.pkl  # Encoded labels  
│── model.h5                  # Trained ANN model  
│── onehot_encoder_geo.pkl    # One-hot encoded features  
│── prediction.ipynb          # Notebook for predictions  
│── README.md                 # This file!  
│── regression_model.h5       # Regression model  
│── requirements.txt          # Dependencies  
│── salaryregression.ipynb    # Regression notebook  
│── scaler.pkl                # Saved scaler  
Results & What We Learned
✨ Our model does a solid job predicting customer churn!
✨ Feature engineering and tuning made a big impact on accuracy.
✨ Streamlit made it easy to create an interactive UI for real-time predictions.
