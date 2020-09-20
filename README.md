# WWC-DataScience-Mission-Predictable-Hackathon


## :memo: Table of Contents

- [About Mission Predictable Hackathon](#AboutMissionPredictableHackathon)
- [Problem Statement](#ProblemStatement)
- [Solution](#Solution)
- [Libraries](#Libraries)
- [Training](#Training)
- [Dataset](#Dataset)
- [Contributing](#contributing)
- [Team](#team)
- [Future Work](#FutureWork)

---
## :round_pushpin: About Mission Predictable Hackathon
![Mission Predictable](https://s3-us-west-2.amazonaws.com/wwcodefroala/uploads%2F1595013116901-WWCode+Data+Science+AWS+Hackathon+%282%29.png)
Credits: WWC

## :lock: Problem Statement
<h3> How many beds will we need to accommodate the surging number of COVID infected patients in California? </h3>

With COVID hospitalizations rising steeply in California, the state is on the brink of facing the worst-case scenario: the possibility of cases exceeding capacity. ICU doctors are forced to make brutal decisions: prioritizing and rationing medical care for patients with more severe conditions. The goal of this project is to estimate the amount of beds needed to meet the growing number of patients.

<p align="center">
  <img src="https://github.com/Spark-20/Mission-Predictable-Hackathon/blob/master/Images/three.png"/>
</p>


## :key: Solution

With the continued spread of Covid, the number of hospital beds needed to accommodate patients with the covid is unknown. Our solution is to use machine learning and come up with a model that would predict the number of beds needed in the future. Using California and its counties, our model can predict the number of beds needed three days in advance. This better prepares the hospital for the number of new patients admitted in need of beds with laboratory-confirmed COVID.

We decided to use a time series model (LSTM), trained with AWS SageMaker to predict the future demand of hospital beds in California based on the data of past few months. We also developed an interactive map using plotly which on hovering will provide estimations on the bed availability in different counties. 

Disclaimer: The interactive map is not being displayed properly on Jupyter Notebook when viewed on Github but will run properly otherwise. Please see attached screenshots of map below:
![Map](https://github.com/Spark-20/Mission-Predictable-Hackathon/blob/master/outputs/Available%20ICU%20beds.gif)
![Map](https://github.com/Spark-20/Mission-Predictable-Hackathon/blob/master/outputs/Available%20hospital%20beds.gif)

## :closed_book: Libraries

- tensorflow
- sklearn
- pandas
- numpy
- matplotlib
- plotly-geo
- geopandas==0.3.0
- pyshp==1.2.10
- shapely==1.6.3

## :arrow_forward: Training
 - LSTM Model trained with Amazon Sagemaker

## :page_facing_up: Dataset

- <a href="https://github.com/Spark-20/Mission-Predictable-Hackathon/blob/master/dataset/hospitals_by_county.csv" target="_blank"> Hospitals by county California Dataset </a>
- <a href="https://github.com/Spark-20/Mission-Predictable-Hackathon/blob/master/dataset/statewide_cases.csv" target="_blank"> Statewide cases dataset</a>

## :point_down: Contributing

> To get started

### Step 1

- **Option 1**
    - 🍴 Fork this repo!

- **Option 2**
    - 👯 Clone this repo to your local machine using https://github.com/Spark-20/Mission-Predictable-Hackathon.git
### Step 2

- **HACK AWAY!** 🔨🔨🔨

### Step 3

- 🔃 Create a new pull request using <a href="https://github.com/Spark-20/Mission-Predictable-Hackathon" target="_blank"> https://github.com/Spark-20/Mission-Predictable-Hackathon</a>

## :star: Team Spark 20

- Amma Ofori
- Devika Thampi
- Dhruva Bhavsar
- Tiffany Lau Joa
- Violeta Gotcheva

## :rocket: Future Work
- Expanding this model for Country wise predictions
- Deeper insights on the hospitals in each county including total ICU beds, available ventilators, percent capacity remaining, and more.
- Build a dashboard using AWS QuickSight for easy visualization.
- Building time-enabled maps.
- Prediction of worse-case, best-case and average-case scenarios.

## :link: Links and References
- Google Slides presentation: https://docs.google.com/presentation/d/1O0bA_chjaAFnx6PK2XJrnDuPZaMCWXqVLT7cQbP0WsY/edit?usp=sharing

---
### :pray: Thanks to Women Who Code Data Science Community for organizing this Hackathon
---

