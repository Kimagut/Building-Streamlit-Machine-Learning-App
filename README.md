# Building-Streamlit-Machine-Learning-App
## Embedding Machine Learning Models in GUIs
This project implements a web application for predicting customer churn in the telecommunications industry. Customer churn prediction is crucial for businesses to retain customers by identifying those at risk of leaving. The application allows users to input customer information such as demographics, service subscriptions, and billing details through an intuitive interface built using Streamlit. Based on this input, the app predicts whether a customer is likely to churn and provides the probability of churn.

## Key Features:
- Machine Learning Models: Includes Logistic Regression and AdaBoost classifiers trained on customer data to predict churn.
Interactive Interface: Users can input customer data through dropdowns and numeric inputs, making predictions easily accessible.
- Historical Predictions: A history page displays past predictions with details like prediction result, probability, and timestamp.
Deployment: The app is deployed on Render, making it accessible via the internet for real-time use.

## Technologies Used:
- Python: Programming language used for data preprocessing, model training, and web app development.
- Streamlit: Framework used for creating the interactive web interface.
- Pandas: Library for data manipulation and analysis.
- Scikit-learn: Library used for building and evaluating machine learning models.
- Render: Cloud platform used for deploying the web application.
  
## How to Use:
- Clone the repository.
- Install necessary dependencies (pip install -r requirements.txt).
- Run the Streamlit app (streamlit run app.py).
- Access the app through the provided local URL or deploy it on Render for online access.
  
## Contributors:
Brian Kimagut & Team Curium Azubi Africa

## License:
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments:
This project was inspired by the need to apply machine learning to real-world business challenges.
Special thanks to Streamlit and Render for providing tools that simplify web app development and deployment.
Feel free to explore the repository, contribute, or use the app to gain insights into customer churn prediction in the telecom industry.
