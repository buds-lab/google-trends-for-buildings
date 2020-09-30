# google-trends-for-buildings

## Objectives:
In research related to building performance simulation or prediction, how to quantify the occupant behaviors in different building types, countries and regions is a very difficult topic. Google Trends can provide search volume of various keywords in specific country/zone, and can probably infer the occupant behavior from these time-series trends. This research has the following research goals: (1) **Find holiday/vacation feature that can be used in different countries and different building types (regression-related research)**, (2) **derive countries/regions/building_type from the time series of electricity meters (classification-related research)**, and (3) **analyze residuals of ASHRAE GEPIII submissions**

## Dataset:
Currently, daily and hourly google trends data were downloaded for multiple countries, including keywords: `Google docs`, `Microsoft office`, and `Adobe`. In addition, the best submissions of the top 50 teams in GEPIII were also downloaded.

Google trends data (please use `pd.read_pickle()` to read data):
- [Daily trend](Dataset/Daily%20data)
- [Hourly trend](Dataset/Hourly%20data)

GEPIII best submissions from top50 teams (please use `pd.read_pickle()` to read data):
- [Top50 submissions in GEPIII](Dataset/Top50%20submissions%20in%20GEPIII)

Python notebooks for downloading data:
- [Download daily trend](DownloadData/DownloadDailyTrend.ipynb)
- [Download hourly trend](DownloadData/DownloadHourlyTrend.ipynb)

## Analysis:
Derive occupant behavior from the time series of electricity meters, and compare it with google daily trends:
- [PCA_powerMeter[site13].ipynb](Analysis/PCA_powerMeter%5Bsite13%5D.ipynb)

Analyze residuals of ASHRAE GEPIII submissions (please download `html notebooks` to see interactive visualizations):
- [Residual Analysis [School].html](Analysis/Residual%20Analysis%20%5BSchool%5D.html)
- [Residual Analysis [Office].html](Analysis/Residual%20Analysis%20%5BOffice%5D.html)

## Draft of the paper:
[Google Doc](https://docs.google.com/document/d/1xGRByKGvMDlM1S6nzoV_yyFTpnxAaCHqgThruhyCWvs/edit?usp=sharing)
