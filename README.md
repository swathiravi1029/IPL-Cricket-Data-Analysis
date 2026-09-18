# 🏏 IPL Cricket Data Analysis

## 📌 Project Overview

This project performs an exploratory data analysis of Indian Premier League (IPL) cricket data using Python.

The analysis focuses on identifying team performance, player performance, winning trends, toss impact, venue statistics, batting and bowling performance, and season-wise trends.

The project uses match-level and ball-by-ball delivery data to generate meaningful insights through data analysis and visualization.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze IPL match and season trends
- Compare team performance and win percentages
- Analyze toss decisions and their impact on match results
- Identify the most frequently used IPL venues
- Analyze player performance
- Identify top run scorers and wicket takers
- Analyze batting first vs chasing performance
- Identify highest team innings scores
- Analyze individual player scores
- Identify players with the most sixes and fours
- Analyze IPL run-rate trends across seasons
- Analyze Player of the Match awards
- Perform team-to-team head-to-head analysis

---

## 📂 Dataset

The project uses two datasets:

### 1. matches.csv

This dataset contains match-level information such as:

- Match ID
- Season
- Teams
- Winner
- Toss Winner
- Toss Decision
- Venue
- Player of the Match

### 2. deliveries-1.csv

This dataset contains ball-by-ball information such as:

- Match ID
- Innings
- Batting Team
- Batsman
- Bowler
- Batsman Runs
- Total Runs
- Wicket Information
- Dismissal Type

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook / Python IDE**

---

## 🔍 Data Exploration

The first step of the project is understanding the datasets.

The analysis includes:

- Checking the number of rows and columns
- Viewing column names
- Understanding data types
- Checking missing values
- Checking duplicate records

python
matches.shape
deliveries.shape

matches.columns.tolist()
deliveries.columns.tolist()

matches.info()
deliveries.info()

matches.isnull().sum()
deliveries.isnull().sum()

matches.duplicated().sum()
deliveries.duplicated().sum()
