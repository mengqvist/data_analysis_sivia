# Reproducing "Data Analysis - A Bayesian Tutorial" Examples with Pyro

![Pyro Logo](https://pyro.ai/img/pyro_logo.png)

## Description
This project is part of my journey to learn Pyro, a universal probabilistic programming language. I'm working through examples from the book "Data Analysis - A Bayesian Tutorial" (Second edition) by D. S. Sivia and J. Skilling, implementing solutions using Pyro instead of the mathematical approaches in the book.

## Key Features
- Implementation of Bayesian analysis examples using Pyro
- Focus on examples with extractable data from the book
- Comparative analysis between mathematical solutions and Pyro implementations

## How to Use
1. Clone this repository
2. Install the environment using Miniconda:
   ```bash
   conda env create -f environment.yml
   conda activate pyro
   ```
3. Open the Jupyter notebook in the repository

**Alternatively**, click the badge below to launch this project in a Binder environment in your browser.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mengqvist/data_analysis_sivia/HEAD)

## Notebooks
1. [Main Notebook](https://github.com/mengqvist/data_analysis_sivia/blob/master/data_analysis_sivia.ipynb) - Implementation of book examples using Pyro
2. [Bayesian Linear Regression](https://github.com/mengqvist/data_analysis_sivia/blob/master/bayesian_linear_regression.ipynb) - An extension to the book's content, implementing and testing a Bayesian Linear Regression model on simulated data.

## Technologies Used
- Python 3.x
- Pyro 1.4.0
- Jupyter Notebook
- PyTorch
- Matplotlib

## Future Work
- Implement more examples from the book
- Implement all examples in [NumPyro](https://num.pyro.ai/en/latest/index.html)

## How to Contribute
This is a personal learning project, but suggestions and discussions are welcome! Feel free to open an issue or submit a pull request.

## Status
This project under sporadic development. Content and implementations may change as I progress through the book and deepen my understanding of Pyro.

## Resources
- [Pyro Documentation](https://pyro.ai/)
- [Data Analysis - A Bayesian Tutorial (Book)](https://global.oup.com/academic/product/data-analysis-9780198568315)
