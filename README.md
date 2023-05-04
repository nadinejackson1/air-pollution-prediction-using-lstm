### 100 Days of Machine Learning: Day 21

# Air Pollution Prediction using LSTM

This project aims to predict air pollution levels using Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN). The dataset used in this project is the Beijing PM2.5 Data from the UCI Machine Learning Repository.

### Introduction

Air pollution is a significant issue affecting the health and well-being of people worldwide. Accurate predictions of pollution levels can help governments and individuals take necessary precautions to mitigate the impact of air pollution on public health.

This project uses LSTM networks to predict PM2.5 (particulate matter with a diameter of 2.5 micrometers or less) concentration levels, which are a key indicator of air pollution. LSTMs are well-suited for this task because they can learn and remember long-term dependencies in sequences of data, such as time series.

### Installation

To run the project, you need to have Python 3.x installed along with the following libraries:

    numpy
    pandas
    matplotlib
    scikit-learn
    keras

You can install these libraries using pip:

    pip install numpy pandas matplotlib scikit-learn keras

### Dataset

The dataset used in this project can be found [here](https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data). It contains hourly PM2.5 concentration levels from 2010 to 2014 in Beijing, China.

### Usage

1. Clone the repository:
    
        git clone https://github.com/nadinejackson1/air-pollution-prediction-using-lstm.git

2. Change into the project directory:

        cd air-pollution-prediction-using-lstm

3. Run the main Python script:

        python main.py

4. The script will train the LSTM model and output the results, including predicted PM2.5 concentration levels.

### Model

The LSTM model used in this project consists of:

- An input layer with 50 LSTM units and a dropout rate of 0.2.
- A hidden layer with 50 LSTM units and a dropout rate of 0.2.
- Another hidden layer with 50 LSTM units and a dropout rate of 0.2.
- A dense output layer with a single unit for the predicted PM2.5 concentration.

The model is trained using the Adam optimizer and mean squared error loss.

### Results

The performance of the LSTM model can be assessed by comparing the predicted PM2.5 concentration levels with the actual levels in the test dataset. A lower mean squared error indicates better predictive accuracy.

### License

This project is released under the MIT License.

### Acknowledgements

The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).
The project is inspired by the [100 Days of ML Challenge](http://github.com/nadinejackson1/100daysofML), and is Day 21's project of the challenge.
