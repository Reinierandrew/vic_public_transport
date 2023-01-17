Analysis of Public Transport to aid demand and capacity planning at PTV

Team Members:
Laszlo Kiss
Zakia Afrin Aziz
Reinier Van Vuure
David Jenkins

Project Outline:
PTV planning  team requested  Group2's support to  establish the relationship between current public transport infrastructure and population in Victorian suburbs. 
The key questions the would like to have an answer on are:
 -  What is the current correlation between public transport availability and population.
 -  What are the top three suburbs in 2023 for public transport availability
    (additionally rule out CBD etc and look at reasons for correlation)
 -  What are the top 5 areas/suburbs that will require the highest level of development.
 - What number of stops and additional equipment will be required to reach the current “best of class” levels of the top suburbs of question 2
   If there’s going to be 50% growth in x suburb - they’re going to need \
   Population to pt stop ratio (eg, CDB has 1:1000 ratio)
   cut the data into groups

The request is to present a summary  and visualisation of the analysis on January  17 to aid PTV in future infrastructure planning.

The team will obtain data sets through APIs and other available sources to aid in answering the above questions.

A presentation of a summary of the project results will be given on January 17th to the PTV management team.


The following files are to be run:

PTV_GTFS_Analysis.ipynb (Note this can be bypassed as it takes too long) 
To run this PTV GTFS data needs to be downloaded (200+ Meg) and unzipped to the Resources/GTFS folder
The GTFS data set is analysed and combined to obtain data on number of trips per stop
Each step is saved as csv, some of which is over 100Meg. The final output that is smaller is then used in PTV_Growth_Analysis.

PTV_Growth_Analysis.ipynb
This file calculates trips per stop data and compares this dat a to population growth data which is then analysed.
Various other data analysis and visualisation is done in the code 
