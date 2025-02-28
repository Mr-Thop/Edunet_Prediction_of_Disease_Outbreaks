# Prediction of Disease Outbreaks

This Streamlit-based web application predicts the likelihood of three major diseases: Diabetes, Heart Disease, and Parkinson's Disease. It utilizes machine learning models to analyze user inputs and provide a diagnosis.

## Features
- **Diabetes Prediction:** Uses various health parameters to determine the risk of diabetes.
- **Heart Disease Prediction:** Analyzes multiple factors to predict the presence of heart disease.
- **Parkinson's Disease Prediction:** Uses vocal measurements to detect potential Parkinson’s disease.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Streamlit
- Required Python libraries (listed in `requirements.txt`)

### Clone the Repository
```sh
git clone https://github.com/Mr-Thop/Edunet_Prediction_of_Disease_Outbreaks.git
cd Edunet_Prediction_of_Disease_Outbreaks
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

## Running the Application
```sh
streamlit run app.py
```

## Directory Structure
```
|-- Edunet_Prediction_of_Disease_Outbreaks/
    |-- datasets/
        |-- diabetes.csv
        |-- heart.csv
        |-- parkinsons.csv
    |-- models/
        |-- diabetes_model.sav
        |-- heart_disease_model.sav
        |-- parkinsons_model.sav
    |-- Jupyter_Files/
        |-- Multiple disease prediction system - diabetes.ipynb
        |-- Multiple disease prediction system - heart.ipynb
        |-- Multiple disease prediction system - parkinsons.ipynb
    |-- app.py
    |-- requirements.txt
    |-- README.md
```

## Usage
1. Run the application.
2. Select the disease prediction module from the sidebar.
3. Enter the required health parameters.
4. Click on the prediction button to see the result.

## Dependencies
- `streamlit`
- `pickle`
- `os`
- `streamlit_option_menu`

## License
This project is licensed under the MIT License.

## Contributing
Feel free to fork this repository and contribute by submitting pull requests.

## Author
[Your Name] - [Your GitHub Profile]

