# Algo-Trading-Bot

## Analysis Report

### Overview:
The goal of this project is to create an algorithmic trading bot and tune it in order to find the best way to use the algorithm yielding the highest returns. The algorithm uses signals calculated from the actual returns, and a short and long simple moving average windows. A baseline algorithm is created with a short window of 5 days, long window of 100 days, and training set of 3 months. The baseline algorithm uses an SVM as the machine learning algorithm to create its predictions. The baseline algorithm is then tuned and re-evaluated. First tuning I increased the training dataset to 12 months. Second tuning I changed the short and long windows or the SMA to 20 and 150 days respectively. I then changed the Machine Learning model from an SVM to a Logistic Regression model. 


### Results

Baseline Trading Algorithm:

![Baseline Algorithm Classification Report](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/baseline-performance.png)

![Baseline Algorithm Graph](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/baseline.png)

Tuned Algorithm 12 Month Training Set:

![Tuned Algorithm 12 Month Training Set Classification Report](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/12-month-training-performance.png)

![Tuned Algorithm 12 Month Training Set Graph](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/12-month-training.png)

Tuned Algorithm wider SMA windows:

![Tuned Algorithm wider SMA windows Classification Report](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/tuned-sma-performance.png)

![Tuned Algorithm wider SMA windows Graph](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/tuned-sma.png)

Logistic Regression Model:

![Logistic Regression Model Classification Report](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/logistic-regression-performance.png)

![Logistic Regression Model Graph](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/Images/logistic-regression.png)


### Summary 
What impact resulted from increasing or decreasing either or both of the SMA windows?
Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?


---

## Technologies

This application runs on python version 3.7, with the following add-ons:

* [Jupyter Lab/Notebook](https://jupyter.org/) - A development tool for interactive programming.

* [Pandas](https://pandas.pydata.org/) - A python librart for data analysis and manipulation.

* [scikit-learn](https://scikit-learn.org/) - A python library for Machine Learning tools.

* [Numpy](https://numpy.org/) - a python library for scientific and mathematical computing. 

* []() - hvplot

---

## Installation Guide

Download and install [Anaconda](https://www.anaconda.com/products/individual-b)

Open terminal and install Pandas by running this command:

    pip install pandas

    pip install -U scikit-learn

Activate Conda environment:

    conda activate "environment name"

    conda install -c conda-forge imbalanced-learn


Open Jupyter Notebook and navigate to the notebook file. 

Click on each cell to run individually:

    Shift + Enter

---

## Example

Running 

![Code Example]()

---

## Contributors

*  Talib Kateeb

---

## License

[Click Here To View](https://github.com/talibkateeb/Algo-Trading-Bot/blob/main/LICENSE)
