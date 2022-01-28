# Stanford Open Policing Project

## Introduction

This project uses data from ["The Stanford open policing project"](https://openpolicing.stanford.edu/) to analyse traffic stops by police officers in the Rhode Island State of the United States. After cleaning the data, several questions are answered by analysing it and by using visualisation tools. In particular, we are interested in analysing the impact of gender and race on the police behaviour. 

In addition, we combine this dataset with weather information from the ["National Centers for Environmental Information"](https://www.ncei.noaa.gov/) in order to understand how the weather conditions impact the police behaviour.

(Data mining, data cleaning, data visualisation, data analysis)

## The data
* Traffic stops data correspond to 509,671 stops during the period January 2005 to December 2015 in the Rhode Island state. It is taken from the ["The Stanford open policing project"](https://openpolicing.stanford.edu/).
* Weather data from the PROVIDENCE, RI US station corresponding to the period October 1942 to December 2021. It is taken from the ["National Centers for Environmental Information"](https://www.ncei.noaa.gov/). 

## About the repository
Contents of the repository:
* <code>RhodeIsland.ipynb</code>: commented jupyter-notebook with the analysed data and the conclusion reached.
* <code>data/</code>
  * <code>ri_statewide_2020_04_01.csv</code>: traffic stops dataset
  * <code>USW00014765.csv</code>: weather information dataset
