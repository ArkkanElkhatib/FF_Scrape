# FF Scrape

## Purpose
* FF Scrape utilizes Python alongside the Pandas and Numpy libraries to scrape speicified website to gather data corresponding to the Final Fantasy series

## Usage
* Each game will contain the corresponding data for that game in 'csv' format as well the Python notebook utilized to scrape the data
``` Bash
# For an isolated Python environment run the following 
# prior to running pip command
python -m venv .venv

# Pip command to install packages
pip install -r requirements.txt
```
* To view the data from scraped by the script, you can visit the associated 'kaggle.com' link listed below

## Running the Script
* Running the .ipynb wil require you the ability to run the notebook through Jupyter Lab or to convert the file using the following command
``` Bash
jupyter nbconvert --execute <path-to-.ipynb-file>
```

## Currently Supported Final Fantasy Scrape
* Final Fantasy 1
    * Weapons - Data: https://www.kaggle.com/datasets/arkkanelkhatib/final-fantasy-1-weapons
    * Armors - Data: https://www.kaggle.com/datasets/arkkanelkhatib/final-fantasy-1-armors
