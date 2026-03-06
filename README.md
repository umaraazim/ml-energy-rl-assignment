# Energy Consumption Optimization Using Reinforcement Learning

## Project Overview
This project applies Reinforcement Learning (RL) to optimize 
energy consumption in smart buildings using the UCI Energy 
Efficiency Dataset. We compare two RL algorithms: Q-Learning 
and SARSA.

## Team Members
- Member 1: [Full Name] - [Student ID] - [Email]
- Member 2: [Full Name] - [Student ID] - [Email]
- Member 3: [Full Name] - [Student ID] - [Email]

## Dataset
- Name: Energy Efficiency Dataset
- Source: UCI Machine Learning Repository
- Link: https://archive.ics.uci.edu/dataset/242/energy+efficiency
- Size: 768 rows, 10 columns

## Algorithms Used
- Q-Learning (Off-policy)
- SARSA (On-policy)

## Repository Structure
ml-energy-rl-assignment/
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_q_learning_agent.ipynb
│   ├── 03_sarsa_agent.ipynb
│   └── 04_comparison_results.ipynb
├── data/
│   └── ENB2012_data.xlsx
├── results/
│   └── (plots and charts)
├── members.txt
├── submission.txt
└── README.md

## How to Run
1. Clone the repository
git clone https://github.com/umaraazim/ml-energy-rl-assignment.git

2. Install required libraries
pip install numpy pandas matplotlib seaborn scikit-learn openpyxl

3. Open Jupyter Notebook
jupyter notebook

4. Run notebooks in order
- Start with 01_data_exploration.ipynb
- Then 02_q_learning_agent.ipynb
- Then 03_sarsa_agent.ipynb
- Finally 04_comparison_results.ipynb

## Results
- Q-Learning Test Reward: [fill after running]
- SARSA Test Reward: [fill after running]

## Tools Used
- Python 3
- Jupyter Notebook
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
