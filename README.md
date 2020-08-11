### Reproduction of examples from Data Analysis book using Pyro
The notebook contained in this repository is part of my journy to learn Pyro. As stated on the project webpage: 
> Pyro is a universal probabilistic programming language (PPL) written in Python and supported by PyTorch on the backend. Pyro enables flexible and expressive deep probabilistic modeling, unifying the best of modern deep learning and Bayesian modeling.


Specifically, I am working through the examples from the book
"Data Analysis - A Bayesian Tutorial", Second edition (ISBN 978-0-19-856831-5) by D. S. Sivia, with J. Skilling. In this book the problems are solved mathematically. But I am interested in finding ways to use Pyro to solve these problems. Since this book is quite mathematical most examples have no data which one can work with. Here I am only working with the subset of examples that do have data, although on several occasions I have to extract these from plots.

### Requirements
For this project I have made use of version 1.3.0 of Pyro. The computational environment can be installed using Miniconda (https://docs.conda.io/en/latest/miniconda.html) from the yml file `environment.yml`. In a terminal execute:
```bash
conda env create -f environment.yml
conda activate tf1
```

### Status
I am actively working on this so it should by no means be considered finished...
