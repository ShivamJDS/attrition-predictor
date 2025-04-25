# TAO IQ Assignment

* Attrition Prediction Model - Silent Execution Pilot
* A complete end-to-end implementation of a Classical Machine Learning pipeline for HR dataset.


## 📁 Files and Folders in this Repository

- `taoiq.ipynb` - Main Jupyter Notebook (runs end-to-end on Google Colab).
- `requirements.txt` - List of required Python packages.
- `models` - Folder containing model files
    - `model.pkl` - Pickled Voting Classifier model.
    - `scaler.pkl` - StandardScaler object used for feature scaling.
    - `model_columns.pkl` - List of columns/features used for training the model.
- `model_testing.png` - Screenshot of the model testing output.
- `model_testing.png` - Screenshot of the streamlit deployment.

## 📌 Features

- Preprocessing with scaling and feature engineering.
- Voting Classifier (ensemble of multiple base models).
- Pickled model and scaler for easy reuse.
- Ready-to-run notebook (just upload your dataset).


## 🔧 Installation

* upload the taoiq.ipynb notebook in google colab
* copy csv file to google colab
* Just run the notebook from start to finish
* If you just want to test the Model
* copy all the files to colab and start running from (Save model and test it) cell in the notebook

--------------------------------------
* If you want to run in local follow below steps

```
# Clone the repository
git clone https://github.com/ShivamJDS/attrition-predictor.git
cd attrition-predictor

# Install requirements
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py

```


## 

# Links

1. [Colab Notebook](https://colab.research.google.com/drive/1vxiK81hY08maCDnCj5o85n9aVIf6V0GL?usp=sharing)
2. [Git repo](https://github.com/ShivamJDS/attrition-predictor)

## 🖥️ Live Demo

You can try the app here: [![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://predictor-attrition.streamlit.app/)


---