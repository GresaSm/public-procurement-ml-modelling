# Sustainable Public Procurement through Machine Learning

Public procurement significantly influences public policy and is a critical area of focus for both academic research and civil society oversight. Traditionally focused on anti-corruption and the monitoring of public spending, this repository explores a new dimension—leveraging public procurement to mitigate climate change and enhance sustainability in public purchases.

## About the Research

This project delves into the potential of using decision tree models, to understand and optimize the environmental impact of public procurement. This work is part of the Master Thesis research implemented by Gresa Smolica for the program Master of Data Science for Public Policy, at the Hertie School in Berlin.

### Objectives

- **Explore** the untapped potential of public procurement in the context of climate change mitigation.
- **Develop** Machine Learning models that aid in making sustainable decisions in public procurement.
- **Analyze** the effects of sustainable procurement practices using real-world data from the EXIOBASE dataset.

### Methodology

The research employs decision tree models to analyze procurement data. The study focuses on:
- **Dataset**: EXIOBASE, a detailed multi-regional input-output table.
- **Period**: 2010-2019.
- **Geographic Focus**: case study - Germany, examining the final demand of the government for various products.

## Walk-through the files

#### Data

Access the datasets used in this project:

- [Main Dataset](https://github.com/GresaSm/public-procurement-ml-modelling/blob/main/Final_data/data_combined_final.csv.zip)
- [Supplementary Data](https://github.com/GresaSm/public-procurement-ml-modelling/tree/main/Final_data)

#### Notebooks

Explore the interactive analysis of the project:

- [Data Downloading and Parsing](https://github.com/GresaSm/public-procurement-ml-modelling/blob/main/parsing_datasets.ipynb) - shows a step-by-step process of downloading, agreggating and handling EXIOBASE files, to create a final dataframe with all needed information from different matrices of the large EXIOBASE file.
- [Data Preprocessing](https://github.com/GresaSm/public-procurement-ml-modelling/blob/main/more_data_tuning.ipynb) - shows the process of grouping variables and downsizing the dataframe to its final version.
- [Analysis and ML modelling](https://github.com/GresaSm/public-procurement-ml-modelling/blob/main/modelling_and_analysis.ipynb) - shows the ML modelling, and analysing the most optimal model for the research task.

#### Graphs and visualisations

See the results visualized in the [Figures folder](https://github.com/GresaSm/public-procurement-ml-modelling/tree/main/Figures).

### Main sources

- [EXIOBASE data](https://zenodo.org/records/5589597) - the official EXIOBASE website where all zip files can be downloaded for further analysis. (Stadler, K., Wood, R., Bulavskaya, T., Södersten, C.-J., Simas, M., Schmidt, S., Usubiaga, A., Acosta-Fernández, J., Kuenen, J., Bruckner, M., Giljum, S., Lutter, S., Merciai, S., Schmidt, J. H., Theurl, M. C., Plutzar, C., Kastner, T., Eisenmenger, N., Erb, K.-H., … Tukker, A. (2021). EXIOBASE 3 (3.8.2) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.5589597)
- [PYMRIO package](https://pymrio.readthedocs.io/en/latest/) - an open source tool for analysing global environmentally extended multi-regional input-output tables (Stadler, K. (2021). Pymrio – A Python Based Multi-Regional Input-Output Analysis Toolbox. <i>Journal of Open Research Software</i>, <i>9</i>(1), 8. https://doi.org/10.5334/jors.251)
- [sklearn Random Forest Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
- [sklearn Gradient Boosting Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)

## Getting Started

To get started with this project, you can clone this repository and explore the datasets and models provided.

```bash
git clone https://github.com/yourusername/sustainable-procurement.git
cd sustainable-procurement




