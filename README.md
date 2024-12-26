
# Student Mark Predictor

A Flask-based web application that predicts student marks based on study hours. The project demonstrates a simple machine learning deployment using Flask and `joblib` for model loading.

---

## Features

- Predict marks based on study hours entered by the user.
- Input validation to ensure hours are within a valid range (1-24).
- Saves predictions to a CSV file (`smp_data_from_app.csv`).

---

## Prerequisites

- Python 3.6+
- Flask
- Pandas
- NumPy
- Joblib
- Markupsafe

---

## Setup Instructions

1. **Clone or Download the Repository**
   Ensure you have the project files, including the model file `student_mark_predictor.pkl`.

2. **Install Dependencies**
   Run the following command to install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   Execute the following command in the terminal:
   ```bash
   python app1.py
   ```
   The app will be available at `http://127.0.0.1:5000`.

4. **Use the Application**
   - Open the link in a web browser.
   - Enter study hours to predict the marks.

---

## File Structure

- `app1.py`: The main application script.
- `student_mark_predictor.pkl`: The pre-trained machine learning model.
- `index.html`: The frontend template for user interaction.
- `smp_data_from_app.csv`: CSV file where predictions are stored.

---

## How It Works

1. User inputs the number of study hours (1-24).
2. The app validates the input and uses the machine learning model to predict marks.
3. The predicted marks are displayed on the web page.
4. Input and predictions are saved in `smp_data_from_app.csv`.
