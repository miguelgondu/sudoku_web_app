# Sudoku web-app with Bayesian Optimization

This repo contains the code for the first experiment of the paper we plan to write for AAAI 2020. This experiment, summarized, consists of a sudoku web app that optimizes the sudokus it serves for them to be solved in a given time.

## Some details

### Modifying the config file

The web app depends on a prior (that can be constructed using `create_priors.py`) and on some sudokus that were downloaded from [Kaggle's databases](https://www.kaggle.com/bryanpark/sudoku). This files are loaded from the app from the paths established in a config file (which is in this repo), so feel free to change them in your case.

In my case, I created a data folder in this repo with the following structure:

```
.
├── data
│   ├── experiments
│   │   └── sudoku
│   ├── images
│   ├── priors
│   ├── sudokus
│   │   ├── sudokus_9x9.csv
│   └── updates
```
