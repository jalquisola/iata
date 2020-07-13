# iata
This repo contains notebooks for data analysis, feature engineering & model generation

## Getting Started

### Requirements
Ensure that [Python3](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/) are installed globally.

Ideally, you'll also work in a [Virtual Environment](https://packaging.python.org/tutorials/installing-packages/#creating-and-using-virtual-environments) using [virtualenv](https://packaging.python.org/key_projects/#virtualenv), [venv](https://docs.python.org/3/library/venv.html), or a similar package.

### Install & develop

1. Git clone the project locally
2. Initiate a virtual environment (first time only), run: `python3 -m venv env`
3. Activate the virtual environment, run: `source env/bin/activate`
4. Install required python packages by running `pip install -r requirements.txt`
5. Open Jupyter notebook by running on your terminal: `jupyter notebook`
In case there are errors related to web settings when running the notebook, try running `jupyter notebook --no-browser`

### Python Notebooks
1. Data Exploration - check if the dataset has duplicates and missing values
2. Feature Engineering - transforms event dataset into new dataset w/ new feature columns
3. Model Generation - builds classification algorithm using the transformed dataset

