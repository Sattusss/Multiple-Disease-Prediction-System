# Multiple Disease Prediction System

This project is a web application for predicting multiple diseases using machine learning models. The diseases included are Diabetes, Heart Disease, and Parkinson's Disease. The application is built using Streamlit and allows users to input various health parameters to get predictions for these diseases.

## Features

- **Diabetes Prediction**: Predicts if a person is diabetic based on input parameters like pregnancies, glucose level, blood pressure, etc.
- **Heart Disease Prediction**: Predicts if a person has heart disease based on parameters such as age, sex, chest pain types, resting blood pressure, and more.
- **Parkinson's Disease Prediction**: Predicts if a person has Parkinson's disease based on vocal measurements.

## Models

The application uses pre-trained machine learning models for predictions. These models are loaded using the `pickle` library.

- Diabetes Prediction Model
- Heart Disease Prediction Model
- Parkinson's Disease Prediction Model

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/sattusss/multiple-disease-prediction-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd multiple-disease-prediction-system
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
2. Open the web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).

## Application Structure

- **Diabetes Prediction Page**: 
    - Users can input data such as number of pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.
    - Click the "Diabetes Test Result" button to get the prediction.

- **Heart Disease Prediction Page**:
    - Users can input data such as age, sex, chest pain types, resting blood pressure, serum cholesterol, fasting blood sugar, resting ECG results, maximum heart rate, exercise induced angina, ST depression, slope of the peak exercise ST segment, major vessels colored by fluoroscopy, and thal.
    - Click the "Heart Disease Test Result" button to get the prediction.

- **Parkinson's Disease Prediction Page**:
    - Users can input various vocal measurements such as MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP, MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA, NHR, HNR, RPDE, DFA, spread1, spread2, D2, PPE.
    - Click the "Parkinson's Test Result" button to get the prediction.

## Customization

The application is designed to be easily customizable. You can modify the colors and styles in the `app.py` file by editing the CSS section.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

Special thanks to the creators of the models and the Streamlit community for their support.

## Contact

For any questions or inquiries, please contact [itssatyam.345@gmail.com].
