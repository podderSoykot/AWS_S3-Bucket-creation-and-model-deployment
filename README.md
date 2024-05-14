Deploy Machine Learning Model In AWS SageMaker-Training Xgboost ML ALgo  with House price predection dataset(Kaggle)
Dataset link:https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data


# House Price Prediction with XGBoost and SageMaker

This project demonstrates how to train an XGBoost model using SageMaker for predicting house prices. It includes the following steps:

1. **Data Preparation**: The dataset is downloaded from Google Drive and loaded into a DataFrame.

2. **Data Splitting**: The dataset is split into training and testing sets using a 70-30 split ratio.

3. **Data Preprocessing**: The numerical features are scaled using StandardScaler, and the categorical features are one-hot encoded using OneHotEncoder.

4. **Model Training**: The preprocessed data is used to train an XGBoost model using SageMaker.

5. **Model Evaluation**: The trained model is evaluated using the Mean Squared Error (MSE) metric on the testing set.

6. **Model Deployment**: The trained model is deployed and made available for making predictions.

## Setup

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the `train.py` script to train the XGBoost model:

    ```bash
    python train.py
    ```

2. Once the training is complete, the trained model will be deployed automatically.

3. Use the deployed model endpoint to make predictions.

## File Structure

- `train.py`: Python script for training the XGBoost model.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project documentation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
