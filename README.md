# Deep Learning: Forecasting with Keras

This repository contains a project that leverages the power of neural networks to create time series forecasts. The project is divided into two parts to demonstrate different approaches to temporal analysis using historical data.

## Project Overview
### Part 1: Airline Demand Forecasting
The first part of the project predicts airline demand using historical data from 1949 to 1960. The data is split into training and testing sets. For time series, it's a good practice to train the model using shifted values, where the training values are passed both as input and output with a lag, enabling the forecast to be based on previous values. This technique shows an accuracy improvement in the model.

### Part 2: Bike Rental Forecasting
The second part uses a bike rental dataset from 2015 to 2017. The same shifting technique is applied for input and output data. This time, an LSTM (Long Short-Term Memory) network is used, which retains data for up to 10 days, achieving high accuracy with the test data.

## Course Details
This project was completed as part of the 'Advanced Machine Learning' course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-machine-learning-avancada).

## Objectives Achieved
- Learn how to use Keras
- Discover data structures for forecasting
- Apply neural networks for regression
- Understand recurrent networks
- Make predictions with an LSTM

## Technologies Used
- Python
- Jupyter Notebook
- Keras
- TensorFlow
- Pandas
- NumPy

## Project Structure
The directory structure of the project is as follows:
```
deep-learning-previsao-com-keras/
│   database-project-03.csv
│   database-project-04.csv
│   project-03.ipynb
│   project-04.ipynb
│   README.md
```

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/deep-learning-previsao-com-keras.git
   ```
2. Navigate to the project directory:
   ```sh
   cd deep-learning-previsao-com-keras
   ```
3. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

## Running the Notebooks
1. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Run the `project-03.ipynb` and `project-04.ipynb` notebooks to see the analysis and forecasting models in action.

## Language
The language used in this project is Brazilian Portuguese (pt-br).

## Author
GitHub Username: [goosekiing](https://github.com/goosekiing)
