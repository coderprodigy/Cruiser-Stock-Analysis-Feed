# Cruiser: Stock Analysis & Feed

![Olympics Logo](https://www.kindpng.com/picc/m/160-1607796_transparent-png-stocks-statistics-symbol-png-png-download.png)

Cruiser is a great dashboard where users can add an RSS feed URL of their choice into the application and the data will be processed and the trending stocks will be displayed to them.

## 🚀 About Me
I'm an upcoming Software Engineer at JP Morgan and Chase. I love to code and explore various technical stacks. I am an aspiring Dataset.
Feel free to connect with me and I would love to work together on various projects 👨🏻‍💻.

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dilreet-singh-0007/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/dilreetsingh/)

## Live App Prototype
https://cruiser-stocks.herokuapp.com/

[comment]: <> (## Why Cruiser?)

[comment]: <> (As Tokyo Olympic Games just drew to an end, I wanted to review 120 years history of Modern Olympic Game. Modern Olympic Games are leading international sport events. The creation was inspired by the ancient Olympic Games, held in Olympia, Greece from the 8th century BC to 4th century AD. The first modern Games was held in Athens in 1896.)

## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform

## The Dataset
This dataset contains the list of the Top 500 companies 

## Data Exploration
There are two csv files under this dataset. AthleteEvents contains the detail of the athlete participating in each event. It have the height, weight, age and name of athletes, the sport and the event and the result(medal won). nocRegion contains the three letters NOC name and respective regions.

## Dataset Source: 
https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results




## The Pipeline
1. Extract and Clean the data from both CSV files.
3. Create an overall medal tally with customisation for each year and each country.
4. EDA is performed to visualise the participation of nations over time, find the most successful athletes of all time and much more.
4. To understand the performance of countries over time and their best athletes various visualisations have been done.
5. Use Streamlit to create a user interface that connects to the Python functions coded on the back-end. Those functions return data that is converted into charts and displayed on the application.


## Libraries Used in the Project

### For Analysis and i/o operations
Pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with "relational" or "labelled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real-world data analysis in Python.

### For Visualization
Plotly is Python's graphing library which makes interactive, publication-quality graphs. Various plots like line plots, scatter plots, area charts, bar charts, error bars, box plots, histograms, heatmaps, subplots, multiple-axes, polar charts, and bubble charts can be created with ease. <br>
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.

### For the Front End
Streamlit is an open-source Python library that makes it easy to build beautiful apps for visualizing data. It provides a blazingly fast, iterative, and interactive development loop. It is a great way to build highly interactive web applications around their data, machine learning models, and pretty much everything.


## For Deployment
### The App is deployed here:
https://olympics-dashboard-view.herokuapp.com

