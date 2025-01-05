# Optimal State Estimation of Spinning Ping-Pong Ball Using Continuous Motion Model

## Project Overview

The goal of this project is to develop and apply an **optimal state estimation** approach for modeling the trajectory of a **spinning ping-pong ball** using a **continuous motion model**. The model leverages the physics of the spinning ball and real-time measurements to estimate its trajectory accurately. By integrating Bayesian techniques, the project aims to improve the estimation of the ball's state (position, velocity, spin) over time, which can be used in various applications such as sports analysis, robotics, and physical simulations.

In this repository, you will find the following key components:
- **Research Paper**: A detailed explanation of the theoretical framework, methodology, assumptions, and applications of the model.
- **R Markdown File**: The code implementation of the model, which includes data processing, trajectory prediction, and state estimation steps.
- **Knitted Report**: A comprehensive PDF report that summarizes the analysis and results generated from the R Markdown file.

## Workflow & Execution

To replicate the analysis, follow these steps:

### Prerequisites
Ensure you have the following installed:
- **R** (version 3.5 or higher)
- **RStudio** (recommended for ease of use, though not mandatory)
- Required R libraries: `rmarkdown`, `ggplot2`, `bayesm`, `dplyr`, `tidyr`, etc.

You can install the required packages by running the following command in R:

```r
install.packages(c('rmarkdown', 'ggplot2', 'bayesm', 'dplyr', 'tidyr'))
