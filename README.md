# Cutting Stock Problem Solver

![Python](https://img.shields.io/badge/language-Python-blue.svg)
![Algorithm](https://img.shields.io/badge/algorithm-FirstFit%20%7C%20Greedy%20%7C%20Reinforcement-green.svg)
![Status](https://img.shields.io/badge/status-academic--project-success.svg)

## 📌 Introduction
This repository provides an implementation of the **Cutting Stock Problem (CSP)** using three different solution approaches:

1. **First-Fit Algorithm**  
2. **Greedy Algorithm**  
3. **Reinforcement Learning (RL)**  

The cutting stock problem is a classic optimization problem in operations research, where the objective is to minimize waste when cutting raw materials (e.g., metal bars, paper rolls, wood planks) into smaller pieces required for demand.

---

## 🎯 Objectives
- Model the cutting stock problem in Python.  
- Implement and compare different solution strategies:
  - **First-Fit**: place each item in the first available stock roll where it fits.  
  - **Greedy**: prioritize placing larger items first to minimize waste.  
  - **Reinforcement Learning**: train an agent to learn cutting policies that reduce waste over time.  
- Provide performance benchmarks and visualize results.  

---

## 🚀 How to Run
1. Compile:
   ```bash
   pip install -r requirements.txt
2. Run:
   ```bash
   python main.py

## 🧩 Implemented Approaches
1. First-Fit
- Simple heuristic.
- Place each item into the first roll that has enough remaining length.
- Fast but not always optimal.

2. Greedy
- Sort items by size (descending).
- Place the largest items first to reduce waste.
- Often produces better results than First-Fit.

3. Reinforcement Learning
- Formulated as a sequential decision-making problem.
- The agent learns a cutting policy via trial-and-error.
- Can achieve near-optimal solutions after sufficient training.

##⚡ Future Work
- Implement Column Generation (linear programming approach).
- Add visualization (bar charts showing waste per roll).
- Explore Deep Reinforcement Learning with policy gradient methods.
