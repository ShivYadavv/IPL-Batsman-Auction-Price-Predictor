# 🏏 Predicting-IPL-2025-Mega-Auction-Player-Prices-Using-Machine-Learning

A Machine Learning project that predicts **IPL player auction prices** using historical performance statistics and past auction data.  
The goal is to estimate a player's expected market value in the **IPL Mega Auction** using a data-driven approach.

---

# Project Overview

The IPL auction is highly unpredictable, and teams often struggle to estimate the correct value of a player.  
Many auction decisions are influenced by recent performance, hype, or emotional bidding.

This project applies **Machine Learning techniques** to analyze historical player performance and predict their **auction selling price**.

The model helps demonstrate how **data analytics and machine learning can be used in sports economics and auction strategy**.

---

# Problem Statement

IPL auction prices are difficult to predict due to multiple influencing factors such as player performance, demand, and team strategy.

Teams may overpay or undervalue players due to limited statistical analysis.

This project aims to build a **predictive model that estimates player auction prices based on performance data and past auction results**.

---

#  Project Objectives

- Predict IPL player auction prices using machine learning
- Analyze player performance statistics
- Create meaningful performance features
- Evaluate prediction accuracy using regression metrics
- Demonstrate the use of data science in sports analytics

---

# 📊 Dataset Description

The dataset includes **player profile information, batting performance metrics, and historical auction data**.

### Player Profile Features
- Player Name
- Country (Indian / Overseas)
- Batting Style
- Right-handed Bat
- Left-handed Bat
- Age

### Batting Performance Metrics
- IPL Runs
- Batting Average
- Strike Rate
- Number of 50s
- Number of 4s
- Number of 6s
- Boundary Rate
- Six Ratio
- Runs per Match
- Impact Score
- Price Growth

### Target Variable
- **IPL 2022 Mega Auction Final Price**

---

#  Feature Engineering

Several new performance indicators were created to improve model accuracy.

### Boundary Rate
Measures how frequently a player scores through boundaries.


### Six Ratio
Represents the proportion of sixes among all boundary shots.


### Runs Per Match
Average runs scored per match.


### Impact Score
Combines strike rate and batting average to measure batting effectiveness.


### Price Growth
Shows how a player's auction price changed compared to the previous season.


---

# 📊 Exploratory Data Analysis (EDA)

EDA was conducted to understand the relationship between player performance and auction prices.

Key analyses include:

- Distribution of player auction prices
- Correlation between runs and auction value
- Strike rate vs price analysis
- Impact score analysis
- Feature importance visualization

---

#  Machine Learning Model

### Model Used

**Random Forest Regression**

Random Forest was selected because:

- Handles non-linear relationships well
- Works effectively with structured tabular data
- Provides feature importance insights
- Reduces overfitting through ensemble learning

---

# 📈 Model Performance

| Model | MAE | RMSE | R² Score | Result |
|------|------|------|------|------|
| Random Forest (Default) | ₹1.21 Cr | ₹1.70 Cr | 0.74 | Best Performance |
| Tuned Random Forest | ₹1.48 Cr | ₹2.10 Cr | 0.60 | Lower Performance |

The **default Random Forest model performed better than the tuned version**.

---

#  Sample Prediction Results

| Player | Actual Price | Predicted Price |
|------|------|------|
| Abhijeet Tomar | 40 Lakh | 46.3 Lakh |
| Nicholas Pooran | 10.75 Cr | 5.43 Cr |
| Quinton de Kock | 6.75 Cr | 6.86 Cr |
| David Miller | 3 Cr | 5.33 Cr |
| Ajinkya Rahane | 1 Cr | 3.40 Cr |

The model shows reasonable prediction accuracy for several players.

---

# 📂 Project Workflow
Data Collection
↓
Data Cleaning
↓
Feature Engineering
↓
Exploratory Data Analysis
↓
Model Training
↓
Model Evaluation
↓
Price Prediction
