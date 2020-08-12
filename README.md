# google-trends-for-buildings

## Objectives:
In research related to building performance simulation or prediction, how to quantify the occupant behaviors in different building types, countries and regions is a very difficult topic. Google Trends can provide search volume of various keywords in specific country/zone, and can probably infer the occupant behavior from these time-series trends. This research has the following research goals: (1) **Find holiday/vacation feature that can be used in different countries and different building types (regression-related research)**, (2) **derive countries/regions/building_type from the time series of electricity meters (classification-related research)**, and (3) **analyze residuals of ASHRAE GEPIII submissions**

## Dataset:
Currently, daily and hourly google trends data were downloaded for multiple countries, including keywords: `Google docs`, `Microsoft office`, and `Adobe`. In addition, the best submissions of the top 50 teams in GEPIII were also downloaded.

Google trends data (Please use `pd.read_pickle()` to read data):
- [Daily trend](Dataset/Daily%20data)
- [Hourly trend](Dataset/Hourly%20data)

GEPIII best submissions from top50 teams (Please use `pd.read_pickle()` to read data):
- [Top50 submissions in GEPIII](Dataset/Top50%20submissions%20in%20GEPIII)

Python notebooks for downloading data:
- [Download daily trend](DownloadData/DownloadDailyTrend.ipynb)
- [Download hourly trend](DownloadData/DownloadHourlyTrend.ipynb)
