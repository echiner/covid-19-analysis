# COVID-19 Analysis
  
Simple analysis of different COVID-19 datasources (snapshot, time series, Spain data...) using Apache Zeppelin.

## Data Sources

* **CSSE COVID-19 Dataset**:
  * https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data
* **HDX - Novel Coronavirus (COVID-19) Cases Data**:
  * https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases
* **Ministerio de Sanidad**:
  * https://www.mscbs.gob.es/profesionales/saludPublica/ccayes/alertasActual/nCov-China/situacionActual.htm

## Sample Analysis

### Totals
![Totals](img/Analysis3.PNG)

### Evolution (global)
![Evolution analysis](img/Analysis1.PNG)

### Detailed analysis (Spain)
![Comunidades autónomas](img/Analysis2.PNG)

## TODO

* Pre-configure interpolation, spark max record set and helium visualization
* Automatically load the notebook
