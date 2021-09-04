<!-- PROJECT LOGO -->
<!-- 
https://github.com/othneildrew/Best-README-Template/blob/master/README.md#about-the-project
-->
<p align="center">
  <img src="assets/Prevant_noBgr.png" alt="Logo" width="320" height="160">
  <h1 align="center">Prevnant</h1>
  <p align="center">Prevention before complication</p>
</p>


## About The Project

Prevnant is a tool for generating early warnings in pregnant women about both pregnancy morbidities as well as low weight cases in newborn. It has been developed within DS4A course by [Correlation One](https://www.correlation-one.com/), and data was provided by [Alcaldia de Bucaramanga](https://www.bucaramanga.gov.co/) with corresponding data registers for this municipality, RIPS repository and SIVIGILA repository.


### Data Built With

Data was built with:
* [AWS - RDS](https://aws.amazon.com/es/rds/) an cloud platform for creating and conecting cloud relational databases.
* [PostgreSQL](https://www.postgresql.org/) a python framework for building web applications and plotting.
* [SQLAlchemy](https://pypi.org/project/SQLAlchemy/)  a python SQL toolkit for database access.


## Data Description

The Data used for the project corresponds to:
* Maternal Morbidity: Cases of extreme health issue in pregnant woman, identified as maternal morbidity in Bucaramanga
* Maternal Mortality: Cases of deaths identified as maternal mortality in Bucaramanga
* Covid-19 Cases: Cases of Covid-19 in Bucaramanga
* Live Births: Total report of live bitrhs in Bucaramanga
* Low weight cases: Cases of extreme Low weight at bitrh in newborns in Bucaramanga
* RIPS data: Total report of health consultancies and hospitalizations in Bucaramanga

## Data Construction

The Central data follows the schema shown below:

![Screenshots_schema](https://user-images.githubusercontent.com/78127092/132079229-66b6057e-253a-48d6-99b8-72619ec77f5d.png)

