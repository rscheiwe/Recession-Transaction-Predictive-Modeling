# Recession Transaction Predictive Modling

This project is in two stages. The first stage is to predict housing transaction prices with an average error of under $70k, based on available financial data of a housing investment trust during a timeframe which spans the housing market recession of ~2008-2009. The second stage is to use the predicted housing transaction prices to analyze said prices in relation to the recession and any future recession(s) in the housing market. 

![home-values-over-10-years-sparkrental](https://user-images.githubusercontent.com/29715062/37129972-791a7528-224f-11e8-8814-8c51994e5037.png)

*image courtesy of Home Value Index*

## Scope

In this project, we will evaluate the performance and predictive output of a model that has been trained and tested on data collected from Real Estate findings in Upper New York. A model is understood as a good fit if we can predict transaction prices with an average error of under $70,000. 

* Deliverable: Trained model file (.pkl)
* Machine-Learning Task: Regression
* Target Variable: Transaction Price
* "Win" Condition: Average Prediction Error < $70,000

In this hypothetical situation, the given Real Estate Trust (RET) invests in houses, apartments, and condos. They try to predict the fair transaction price of a property before it's sold, contingent on market fluctuations. Since this practice is based on human valuations, it is highly varied and requires stabilization. 

## Structure

The datasets can be found in `/data`, which includes both raw data and an analytical base table dataset. 

The notebooks are meant to be reviewed in the following order:

1. `Exploratory Analysis`
2. `Analytical Base Table Construction`
3. `Classification Algorithms`
4. `Model Training`

and the final model is available at `final_model.pkl`. 
