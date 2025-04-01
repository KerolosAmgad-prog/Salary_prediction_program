# Salary Prediction Project

## Overview
The Salary Prediction project aims to estimate the salary of an employee based on their years of experience. This project utilizes a simple linear regression model to predict the salary, providing an intuitive and efficient way for HR professionals and employers to make salary estimations.

## Project Structure
- **Model Training:** Uses a linear regression algorithm to train the model on a dataset of employee experience and salaries.
- **Model Saving:** The trained model is saved using Pickle for quick reuse without retraining.
- **GUI Interface:** Built using Tkinter, the GUI allows users to input their years of experience and view the predicted salary.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/salary-prediction.git
   cd salary-prediction
   ```
2. Install the required packages:
   ```bash
   pip install numpy scikit-learn
   ```

## Usage
1. Run the script:
   ```bash
   python main.py
   ```
2. Enter the years of experience in the GUI and click "Predict" to see the estimated salary.

## Dependencies
- Python 3.x
- Numpy
- Scikit-learn
- Tkinter

## Model Training
- The dataset used consists of employee salaries and years of experience.
- The model is trained using simple linear regression from the Scikit-learn library.

## Contributing
Feel free to fork the repository and make improvements. Pull requests are welcome.

## License
This project is licensed under the MIT License.

