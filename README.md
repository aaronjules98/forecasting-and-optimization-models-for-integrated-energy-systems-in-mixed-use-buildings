# Forecasting and Optimization Models for Integrated Renewable-Storage Energy Systems in Mixed-Use Buildings
This repository contains forecasting and optimization models for integrated renewable-storage energy systems in mixed-use buildings, which were developed as part of a thesis for a degree in Master of Science in Mechanical Engineering at De La Salle University.

## Abstract
The rise of mixed-use buildings is seen as an essential path to the sustainable development of cities. However, the energy management of these buildings remains a challenge due to their unpredictable energy consumption characteristics and the lack of design guidelines for energy efficiency and sustainability solutions. Thus, this study aimed to develop and prototype a prediction model to characterize and forecast the energy consumption of mixed-use buildings and develop an optimization model to determine the design capacities of the proposed integrated renewable-storage energy system in a mixed-use building. Furthermore, the study applied machine learning algorithms, which can leverage the increasing amounts of open data in the industry. The k-means clustering algorithm and support vector machines were applied in developing and prototyping the prediction model, while mixed-integer linear programming and genetic algorithm were used in the optimization model. The prediction model was initially developed on simulated data and later prototyped using actual data of buildings obtained from The Building Data Genome Project, which was also used in developing the optimization model. The results of the study show that the prediction model had a performance better than statistical approaches previously developed in the literature and conform to building modeling standards.  Improvements in model performance due to clustering were also observed from the initial model and specific cases in the prototype. Finally, the results of optimization modeling show that the proposed integrated energy system is viable and more economically attractive than stand-alone energy systems and the business-as-usual case for mixed-use buildings.

## Conceptual Frameworks
__Prediction Model Framework__
<p align="center">
  <img width="800" height="400" src="/Figures/PredictionModelFramework.jpg">
</p>

__Optimization Model Framework__
<p align="center">
  <img width="800" height="300" src="/Figures/OptimizationModelFramework.jpg">
</p>

## About the Data Sources
The building energy consumption dataset was obtained from Open Energy Information (OpenEI) database. The dataset consists of simulated energy consumption data of 30 buildings, modeled using Energy Plus. The buildings were based from the United States Department of Energy (US DOE) reference buildings, with various types and purposes. The dataset can be accesed [here](https://openei.org/datasets/dataset/simulated-load-profiles-17year-doe-commercial-reference-buildings).

The National Solar Radiation Data Base (NSRDB) is an open dataset of solar radiation and weather data across various locations in the United States. Weather data were acquired from meteorological stations while the solar radiation data were modeled using National Renewable Energy Laboratory's (NREL's) Physical Solar Model (PSM). The dataset was accessed through its application programming interface (API). Documentation on the dataset can be found [here](https://doi.org/10.1016/j.rser.2018.03.003), while the dataset can be accessed [here](https://nsrdb.nrel.gov).

The Building Data Genome Project (BDG) is an open dataset containing a year-long hourly electricity consumption data of 507 buildings, which come from different industries with various primary use types. The dataset also contains metadata and weather files of the buildings that can be used for modeling. Documentation on the dataset can be found [here](https://doi.org/10.1016/j.egypro.2017.07.400), while the project repository can be found [here](https://github.com/buds-lab/the-building-data-genome-project).

## About the Model Scripts
The prediction model and prototype, and the optimization model data gathering scripts were written in MATLAB R2019a using [MATLAB Live Editor](https://www.mathworks.com/products/matlab/live-editor.html), an interactive script editor that enables the model code to be integrated with formatted text and graphics.

The optimization model was developed in [Homer Grid 1.5 Optimizer Software](https://www.homerenergy.com/products/grid/docs/latest/index.html), an optimization software dedicated for distributed, behind-the-meter energy system projects. 


## Directory
* [__/1-PredictionModelDevelopment/__](/1-PredictionModelDevelopment/) - contains the model script and files for the initial development of the prediction model to predict the energy consumption of mixed-use buildings
* [__/2-PredictionModelPrototyping/__](/2-PredictionModelPrototyping/) - contains the script and files of the mixed-use building energy consumption prediction model prototype
* [__/3-OptimizationModelDevelopment/__](/3-OptimizationModelDevelopment/) - contains the model script and files of the optimization model to determine the optimal design capacities of an integrated renewable-storage energy system in mixed-use buildings

## Contact Details
Aaron Jules R. Del Rosario, Graduate Student, Mechanical Engineering Department, De La Salle University (DLSU), Manila, Philippines | [E-mail](aaron_jules_delrosario@dlsu.edu.ph) | [DLSU Mechanical Engineering Department](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/mechanical-engineering/)
