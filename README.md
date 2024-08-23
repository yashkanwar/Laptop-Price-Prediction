# Laptop Price Predictor

This project predicts laptop prices based on user inputs using a machine learning model. It includes a web application for interacting with the model, as well as various data files and scripts used in the development and deployment of the project.

## Project Files

- **`pipe.pkl`**: Serialized model pipeline used for predicting laptop prices.
- **`requirements.txt`**: List of Python packages required to run the project.
- **`app.py`**: Main script for running the Streamlit web application.
- **`df.pkl`**: Pickled DataFrame containing the dataset used for training the model.
- **`laptop-price-predictor.ipynb`**: Jupyter notebook with exploratory data analysis and model training.
- **`laptop_data.csv`**: CSV file containing the dataset used for the laptop price prediction.

## Usage

1. **Run the Streamlit Application**:
    ```bash
    streamlit run app.py
    ```
    Open your web browser and go to `http://localhost:8501` to view the application.

2. **Explore the Jupyter Notebook**:
    You can open and run `laptop-price-predictor.ipynb` in Jupyter Notebook or JupyterLab to see the model training and evaluation process.

## How It Works

- The **`app.py`** script uses Streamlit to create a web interface where users can input laptop specifications and receive real-time price predictions.
- The **`pipe.pkl`** file contains the trained model pipeline that processes user inputs and makes predictions.
- The **`laptop-price-predictor.ipynb`** notebook includes code for data preprocessing, model training, and evaluation.
- The **`df.pkl`** and **`laptop_data.csv`** files are used to store and access the dataset for model training and testing.
