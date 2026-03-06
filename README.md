# OneMax Optimization Benchmark 🧬📊

In evolutionary computation and discrete optimization, the **OneMax problem** is the ultimate benchmark—the "Hello World" of Genetic Algorithms. The objective is elegantly simple: maximize the number of ones in a binary string. However, it serves as a critical diagnostic tool to evaluate how efficiently an algorithm explores a search space and converges toward the global optimum.

This repository contains a comparative experimentation suite (`exp.ipynb`) that pits different discrete metaheuristics against each other to analyze their convergence speed, stability, and exploration-exploitation balance on the OneMax landscape.

## 🎯 Project Overview
This project focuses on **Discrete Optimization**. While continuous algorithms navigate infinite decimal landscapes, the algorithms here deal with binary representations. 

The core Jupyter Notebook (`exp.ipynb`) acts as a benchmarking arena. It instantiates multiple optimization algorithms, runs them through the OneMax objective function under identical constraints, and logs their performance across generations to see which approach finds the optimal binary string the fastest.

## 🚀 Key Features
* **Classic Benchmark Integration:** Implementation of the OneMax objective function for evaluating discrete binary strings.
* **Algorithm Comparison:** A structured experimental pipeline designed to run parallel comparisons between different evolutionary approaches (e.g., Genetic Algorithms, EDAs).
* **Convergence Analytics:** Tracks the best, worst, and average fitness scores of the populations across generations.
* **Visual Benchmarking:** Automated generation of overlaid convergence plots to visually prove which algorithm outperforms the baseline.

## 🛠️ Tech Stack
* **Language:** Python
* **Computation & Arrays:** `numpy`
* **Data Tracking:** `pandas`
* **Visualization:** `matplotlib` / `seaborn`

## ⚙️ How to Run
1. Clone the repository.
2. Ensure you have the foundational algorithm scripts or dependencies ready.
3. Open `exp.ipynb` and execute the cells to run the benchmark. The notebook will automatically output the convergence plots and the generation-by-generation comparison.
