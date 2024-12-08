# Car Price Prediction System

## Project Overview
This project predicts the price of used or second-hand cars based on the following inputs: 
- **Car Name**
- **Company Name**
- **Year of Manufacture**
- **Kilometers Driven**
- **Fuel Type**

The system uses these inputs to estimate a fair market value for the car using machine learning models. The application is built using **Flask** to provide a web-based interface for users. This project is designed for academic purposes to demonstrate real-world applications of machine learning.

## System Requirements

- **Anaconda Environment** with Python 3.10 version
- **Required Libraries**: All dependencies can be installed via the `requirements.txt` file.

## Installation Instructions

1. **Create an Anaconda environment** with Python 3.10:
    ```bash
    conda create --name car-price-prediction python=3.10
    ```

2. **Activate the environment**:
    ```bash
    conda activate car-price-prediction
    ```

3. **Install the required dependencies** using pip:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask application** by executing the following command:
    ```bash
    python app.py
    ```

    This will start the Flask server. You can access the application in your browser at `http://127.0.0.1:5000`.

## Dataset Information

The dataset used for this project is available on **Kaggle**. It contains data about various cars, their features, and their market prices, which helps the model learn and make predictions.

- **Dataset source**: The dataset is available on Kaggle (no direct link provided).

## Credits

- The dataset used for training the model is sourced from Kaggle.
- This project was created for academic purposes to demonstrate the prediction of car prices using machine learning and web application development.

## License

This project is intended for academic purposes. Feel free to use and modify the code for non-commercial and educational purposes.
