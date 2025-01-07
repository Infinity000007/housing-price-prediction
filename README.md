House Price Prediction App
This project is a Flask-based web application that predicts house prices based on user input features . It utilizes a machine learning model trained on a housing dataset. 

Features

    • User-friendly interface: Easy-to-use web form for inputting house features. 
    • Machine learning model: Predicts house prices with high accuracy. using a log-transformed Linear Regression model.  
    • Dynamic predictions: Displays the predicted price in real-time on the web application. 

Installation

Follow these steps to set up and run the project locally:
Prerequisites

    • Jupyter Notebook , or
    • Google Colab 
Steps

    • Download the project files to your local machine.
    • Open the project in Google Colab or Jupyter Notebook.
      Execute the cells in sequence 
    • Run the Flask application

Usage

    1. Input Features:
      
    • area (size in square feet)
    • bedrooms (number of bedrooms)
    • bathrooms (number of bathrooms)
    • stories (number of stories)
    • mainroad (yes or no)
    • guestroom (yes or no)
    • basement (yes or no)
    • hotwaterheating (yes or no)
    • airconditioning (yes or no)
    • parking (number of parking spaces)
    • prefarea (yes or no)
    • furnishingstatus (furnished, semi-furnished, or unfurnished) 
       
    2. Get Prediction:
        ◦ Click on the Predict button to display the estimated house price. 
           
Dataset

The project uses a publicly available housing dataset from Kaggle. 

Link :  https://www.kaggle.com/datasets/yasserh/housing-prices-dataset?resource=download. 
      

Preprocessing Steps:

    • Log transformation was applied to the target variable (price) for better prediction performance. 
    • Data was split into training and testing sets for model evaluation. 
Model

The model used is a Linear Regression model trained on log-transformed prices. The following steps were implemented:
    1. Log transformation of the target variable (price). 
        
Model Performance:

    • Mean Absolute Error (MAE): 0.1999 on training data. 
    • Cross-validation Log-MAE: 0.2131 ± 0.0771 
      
Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to:

    1. Fork the repository. 
    2. Create a new branch (feature/my-feature). 
    3. Commit your changes (git commit -m 'Add new feature'). 
    4. Push to the branch (git push origin feature/my-feature). 
    5. Open a Pull Request. 

Contact

For questions or feedback, feel free to contact:

    • Name: Shreekant Jadhav
    • Email: shreejadhav4625@gmail.com
    • Linkdein: https://www.linkedin.com/in/shreekant-jadhav-3b8340292/
