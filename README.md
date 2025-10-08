# DS1 mini project - GDP of different regions in 2024
**Date: October 8th, 2025**

This README file describes the mini project for Data Science 1. Its purpose was to showcase reproducibility and to practise git and shell scripts.

This project used Word Bank data and showed a barchart of the 2024 GDP per capita of different regions.

## Data
World Bank Group provides accessible databank of world development indicators. Different indicators and timeframes can be selected. This project looked at: GDP per capita (current US$), Population, and Urban population growth (annual %). The selected year was 2024, as it was the latest available data.

## Folder Structure
DS_Project/
├── .gitignore          
├── LICENSE   
├── README.md      
├── environment.yml 
├── requirements.txt    
├── code/     
│   └── main.ipynb
├── data/      
│   └── raw/       
│       ├── data.csv
│       └── metadata.csv
└── output/
  │       └──regional_gdp_comparison.png

## Getting Started

The project can be run by code/main.ipynb. It will set the working directory and save the requirements into its file. 

### Requirements
There are two ways of setting up the environments to run.
1. using conda:
~~~python
conda env create -f environment.yml
conda activate ds1_env
~~~

2. using pip:
~~~python
pip install -r requirements.txt
~~~

### Main dependencies:
  - python=3.11
  - pandas
  - numpy
  - matplotlib

## Notes

This project's goal was to practice the taught material not to perform a normal analysis, so the analysis itself is irrelevant. 

For reproducibility, following the README file is enough.


