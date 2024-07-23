# Olympic_Medal_Analysis
ALL python jupyter notebook
<h1><b> Olympics History Data Analysis(1896-2020)</h1></b>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Olympic_rings_without_rims.svg/1200px-Olympic_rings_without_rims.svg.png">

# Olympic Data Analysis

This repository contains the analysis of Olympic Games data, focusing on various aspects such as the number of unique editions countries have participated in, athlete participation in Summer vs Winter seasons by gender, and more.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
  - [Participation by Country](#participation-by-country)
  - [Season and Gender Analysis](#season-and-gender-analysis)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The purpose of this project is to perform data analysis on the Olympic Games dataset. The analysis covers various aspects including the number of unique editions each country has participated in and the distribution of athlete participation across seasons and genders.

## Dataset

The dataset used in this project contains information about athletes who participated in the Olympic Games. The main columns of interest include:
- `Name`: The name of the athlete.
- `Sex`: The gender of the athlete (M for male, F for female).
- `Age`: The age of the athlete.
- `Height`: The height of the athlete.
- `Weight`: The weight of the athlete.
- `Team`: The team the athlete represents.
- `NOC`: National Olympic Committee 3-letter code.
- `Games`: The year and season of the Olympic Games.
- `Year`: The year of the Olympic Games.
- `Season`: The season of the Olympic Games (Summer or Winter).
- `City`: The host city of the Olympic Games.
- `Sport`: The sport the athlete competed in.
- `Event`: The event the athlete competed in.
- `Medal`: The medal won by the athlete (Gold, Silver, Bronze).

## Installation

To run the analysis, you need to have Python and the following libraries installed:
- pandas
- plotly

You can install the required libraries using pip:
```bash
pip install pandas plotly\
Analysis\
Participation by Country\
#The script olympic_participation.py analyzes the number of unique Olympic editions each country has participated in. Here is a brief overview of the steps:

Rename the region column to Country.\
Group by Country and count the number of unique Year values.\
Create a DataFrame with the results and reset the index.\
Season and Gender Analysis\
#The script season_gender_analysis.py creates a histogram of athlete participation in Summer vs Winter seasons, grouped by gender. Here is a brief overview of the steps:

Import the required libraries.\
Create a histogram using Plotly Express to visualize the data.\
#Contributing:
Contributions are welcome! Please read the contributing guidelines for more details.**
