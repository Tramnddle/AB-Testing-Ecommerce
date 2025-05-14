# A/B Testing in Production Environment

## Project Description

This project demonstrates a practical approach to conducting A/B testing in a production-like environment, focusing on an e-commerce platform aiming to improve product page conversion rates. It covers both the statistical foundations of A/B testing and the production-level code architecture for running multiple A/B tests simultaneously.

## Overview

A/B testing (split testing) is a method used in marketing and product development to compare two versions of content (e.g., web page, advertisement, email) to determine which performs better. 

- **Version A**: Control group (original version)
- **Version B**: Treatment group (modified version)

By measuring and comparing user responses from both groups, we can assess whether changes in version B have a statistically significant impact.

In production environments, A/B testing requires careful design to avoid affecting user experience negatively. This project demonstrates a hands-on approach for implementing and analyzing A/B tests, simulating a real-world production setup.

### Project Structure

- **Part 1**: Conducting A/B tests using Jupyter Notebook with statistical analysis (T-Tests, Permutation Tests).
- **Part 2**: Simulating production-level A/B tests using a scalable code base, analyzing multiple tests on generated event logs, processing data, visualizing results, and integrating A/B testing workflows.

## Aim

- Analyze logged events via A/B tests.
- Understand challenges of building scalable A/B testing solutions at production level.
- Develop statistical and coding practices for production-ready A/B testing pipelines.

## Data Description

The data is generated using the **fake-web-events** library, which simulates semi-random web events for prototyping purposes. This synthetic data represents user interactions with an e-commerce platform.

## Tech Stack

- **Language**: Python 3.10.4
- **Libraries**:
  - pandas
  - requests
  - jupyter
  - notebook
  - duckdb
  - fake-web-events
  - statsmodels
  - matplotlib
  - tqdm
  - customtkinter
  - pandera
  - black
  - ipykernel

## Approach

### Part 1: Statistical Analysis with Jupyter Notebook
- Generate synthetic events log data using **fake-web-events**.
- Perform data processing and statistical analysis:
  - T-Tests
  - Permutation Tests
- Visualize experiment results.
- Analyze statistical significance.

### Part 2: Production Code Setup
- Simulate production-level A/B tests with multiple experiments.
- Generate complex event logs using **fake-web-events**.
- Use **Pandas** and **DuckDB** for efficient data querying and processing.
- Compute T-Tests and Permutation Tests for significance analysis.
- Visualize results with **Matplotlib**.
- Explore production code architecture for scalable A/B testing.

## How to Run

1. Clone the repository.
2. Set up a Python environment (Python 3.10.4 recommended).
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
