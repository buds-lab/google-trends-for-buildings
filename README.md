# google-trends-for-buildings

## Objectives:
In research related to building performance simulation or prediction, how to quantify the occupant behaviors in different building types, countries and regions is a very difficult topic. Google Trends can provide search volume of various keywords in specific country/zone, and can probably infer the occupant behavior from these time-series trends. 

## Dataset:
Currently, daily google trends data were downloaded for multiple countries.

Google trends data:
- [Hourly trend](data/google-trends-data_2016-2018.csv)

Python notebooks for downloading data:
- [Download-Google-trends-data.ipynb](notebooks/Download-Google-trends-data.ipynb)

## Analysis:
Derive occupant behavior from the time series of electricity meters via PCA, and caculate correlations between meter readings (daily values) and google trends:
- [Correlation-between-energy-and-topics.ipynb](notebooks/Correlation-between-energy-and-topics.ipynb)

## Draft of the paper:
[Google Doc](https://docs.google.com/document/d/1xGRByKGvMDlM1S6nzoV_yyFTpnxAaCHqgThruhyCWvs/edit?usp=sharing)
