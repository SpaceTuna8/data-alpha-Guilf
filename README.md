# BioscreenC Data Assistant
Automated Data Analyzer: Python-Google Spreadsheet-R pipeline
##What is this?
A data analytics platform to automate the computation of data stored locally and in Google Cloud Applications and output to the web for remote access.  

Allows for users with minimal to no knowledge of programming to import large raw csv datasets, automate computations, analysis, visualizations, add their own specialized computational functions and share their results.

###Index
* [Example]()
* [Installation]()
 * [Scheduler]()
 * [Spread Sheet]()
 * [plotly]()
* [Configuration Settings]()

##Example
####Input data:
* BioscreenC derived .CSV file
* Well names
* Well groupings

![CSVexample](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/csv.png)

![labelEx](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/labelEx1.PNG?raw=true)

![groupingEx](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/groupingEx1_sm.png?raw=true)

####Output:
 * Updated Google Spreadsheet
 * [Plotly ggplots](https://dashboards.ly/ua-3iqBAQDFa93xVVHraRB3Tm "Plotly Dashboard")
 * updated CSV file
 * dynamically generated R script
 * ggplot png files

![Updated Google Spreadsheet](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/well_dataEx1.PNG?raw=true)

![PlotlyEx](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/plotlyEx1.PNG?raw=true)

![RscriptEx](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/groupingRex1.PNG?raw=true)

![local_fileEx](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/local_filesEx1.PNG?raw=true)

###Plate-reader Wells
####[Well Label-Replacement Sheet](https://docs.google.com/spreadsheets/d/1fJhE1hOMqVvf5T8YHxRATOQ8QHKfujZRym2wk-tYq4I/pubhtml)
![Well Guide](https://github.com/SpaceTuna8/data-alpha-Guilf/blob/master/readme_images/Microplate_simple.PNG?raw=true)

##Installation
* [Obtain OAuth2 credentials from Google Developers Console](http://gspread.readthedocs.io/en/latest/oauth2.html) (Steps 1-4)
* Setup Google Spreadsheet
* Download Zipfile
  * Place JSON authorization file in the same directory as main.py
  * Check config.ini preferences
    * Set google spreadsheet name
    * Set [plotly credentials (username and api key)](https://plot.ly/)
    * Set desired preferences, tolerances
* [Install & Add to PATH R](https://cran.r-project.org/mirrors.html)
* [Install & Add to PATH Python35](https://www.python.org/ftp/python/3.5.2/python-3.5.2.exe)
  * Install python modules gspread & oauth2client

####To Install python modules on Windows:
1. Run commandprompt
2. python -m pip install gspread
3. python -m pip install oauth2client

####Setup Task Scheduler/Cron job (optional)

####Spread Sheet Setup

####Plotly Setup

##Configuration Settings
