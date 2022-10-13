# Dutch household waste

In this project, I explore data about Dutch household waste in the years 2001-2020. Study topics include:
* waste per person, including trends over time
* breakdown of waste into different waste types
* correlation between waste figures and municipality characteristics

## Results

To display the result, simply [click the .ipynb file](https://github.com/jasperquak/dutch_household_waste/blob/main/DutchHouseholdWaste.ipynb) in this repository. It will open in a Notebook viewer.

## Reproduction

In case you want to reproduce the project in a Jupyter Notebook in your own environment.

Download the .zip file, and unpack it. The .ipynb file and the data files should be in the same folder.

Before starting Jupyter Notebook, ensure that you have the following packages installed:
* pandas
* numpy
* matplotlib.pyplot
* seaborn
* googletrans

In particular the last one (used for data translation) may be less common. To install it, I first ran (in an Anaconda prompt):

*conda install -c conda-forge googletrans*

However, when using it to translate, it resulted in error message: "AttributeError: 'NoneType' object has no attribute 'group' in googletrans". Then, after searching online, I upgraded the package via:

*pip install googletrans==4.0.0rc1*

After which it worked.

## About the data sources

The data that is used in this study was taken from:
* [CBS](https://www.cbs.nl/), Centraal Bureau voor de Statistiek, or "Central Agency for Statistics", a Dutch governmental institution that gathers statistical information about the Netherlands.
* [Afvalmonitor](https://afvalmonitor.databank.nl/), or "Waste Monitor", another website regarding Dutch household waste.

See the contents of the Notebook for more details about the precise data sources.


