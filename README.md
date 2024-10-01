# Paper-Analysisoff1regchange
In my paper, I have used the FastF1 python package. FastF1 gives you access to F1 lap timing, car telemetry and position, tyre data, weather data, the event schedule and session results.
Main features:
-Access to F1 timing data, telemetry, sessions results and more
-Full support for Ergast to access current and historical F1 data
-All data is provided in the form of extended Pandas DataFrames to make working with the data easy while having powerful tools available
-Adds custom functions to the Pandas objects specifically to make working with F1 data quick and simple
-Integration with Matplotlib to facilitate data visualization
-Implements caching for all API requests to speed up your scripts
FastF1 is open source. Everyone can download it onto a jupyter notebook and use it to access telemetry data. The data sources are from FastF1 telemetery. To show how the codes are open source, we can look at the file titled Open Source Codes, which is a Jupyter Notebook that shows how the codes can be accessed and used by anyone
Formula 1 Race Data (2019-2023)
This repository contains race data from the 2019, 2020, 2021, 2022, and 2023 Formula 1 seasons, extracted using the FastF1 Python package. The data includes race telemetry, lap times, and session results for multiple races each season.
Data Overview
The data is organized by year and includes the following for each season:
- Race Telemetry: Speed, throttle, braking, gear, etc., for each car during the race.
- Lap Times: Detailed lap times for each driver.
- Session Results: Final standings and key statistics for each race session.
Data Structure
The data is organized as follows:
- `/data/2019`: Data for the 2019 season.
  - `race_telemetry_2019.csv`: Telemetry data for various races.
  - `lap_times_2019.csv`: Lap-by-lap times.
  - `session_results_2019.csv`: Results from qualifying, practice, and races.
- `/data/2020`: Data for the 2020 season.
- `/data/2021`: Data for the 2021 season.
- `/data/2022`: Data for the 2022 season.
- `/data/2023`: Data for the 2023 season.
Data Extraction:
All data was extracted using the [FastF1 Python package](https://github.com/theOehrly/Fast-F1). You can reproduce the data extraction using the following steps:

Reproducing Data Extraction:
1. Install FastF1:
   ```bash
   pip install fastf1

