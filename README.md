# diabetes-prediction

## Overview
The Diabetes Prediction Web App is a machine learning project that predicts whether a person is diabetic or not based on their health data. The model is trained on the diabetes dataset from Kaggle. The app features a user-friendly interface built using Streamlit, allowing users to input their health data and receive predictions in real time.

## Features
- **Diabetes Prediction:** Predicts whether a person is diabetic based on input health data.
- **Streamlit Interface:** User-friendly interface for interacting with the model.
- **Kaggle Dataset:** Utilizes the diabetes dataset from Kaggle for training the model.

## Technologies Used
- **Python:** Programming language used for model development.
- **TensorFlow:** Machine learning framework used for building and training the prediction model.
- **Streamlit:** Framework used for creating the web application interface.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/abhisek-13/diabetes-prediction.git
    cd diabetes-prediction
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```
2. Open your web browser and go to `http://localhost:8501` to access the web app.
3. Input your health data and click the predict button to see the prediction results.

## Project Structure
- `app.py`: Main application file for running the Streamlit web app.
- `model.py`: Contains the code for building and training the diabetes prediction model.
- `requirements.txt`: List of required Python packages.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any questions or feedback, please contact [abhisekmaharana9861@gmail.com](abhisekmaharana9861@gmail.com).
