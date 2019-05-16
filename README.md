# StatMethods-in-Finance


This repository contains stocks data and R markdown file in which the portfolio optimization will be discussed.


<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

## Table of Contents

- [Quick Start](#quick-start)
  - [Technical Requirements](#techincla-requirements)
- [Introduction](#introduction)
- [Description of the data source](#description-of-the-data-source)
- [Analysis of missing values](#analysis-of-missing-values)
- [Results](#results)
- [Interactive Component](#interactive-component)
- [Conclusion](#conclusion)

<!-- /TOC -->



## Quick Start

### Technical Requirements

R and Shiny application were used to demonstrate the data visualization.

## Introduction:

Citi bike is a privately owned public bicycle sharing system based in new york city, having stations in Manhattan, Queens, Brooklyn and Jersey city. It was named Citi bike because Citigroup lead the sponsorship. It was first opened in May 2013 with 332 stations and 6,000 bikes. Now, they have 757 active stations with around 12,000 bikes.

As of July 2017, there are 130,000 annual subscribers. Citi Bike riders took an average of 38,491 rides per day in 2016, and the system reached a total of 50 million rides in October 2017

We decided to analyze the Citi bike data because we wanted to bring insights out of something related us since we are living in NYC. We used Citi bike multiple times if there is a heavy traffic or even just to exercise little bit. We wanted to analyze what is going on with the usage of Citi bike data, not limiting ourselves from just using the bike for fun.


## Description of the data source

The **link** for the data source is [Here](https://www.citibikenyc.com/system-data).

If you go in there and click “downloadable files of Citi Bike trip data” you can see lists of downloadable files by each month in a csv type.

Motivate international, a private company, is responsible of collecting the data. The company is a global leader in bike share. Motivate currently manages all of the largest bike shares systems such as Ford GoBike, Citi Bike, Divvy, Capital Bike Share, etc.


Here are the packages needed for the project.

```r
library(tidyverse)
library(lubridate)
library(shiny)
library(leaflet)
library(leaflet.extras)
library(magrittr)
library(ggridges)
library(ggplot2)
library(dplyr)
library(plotly)
```

## Analysis of missing values

## Results

## Interactive component


## Conclusion

Limitations: we were not able to analyze the whole year cycle or couple years cycle because the size of the data. The dataset is very clean and well-organized, but contains around 10 NULL values. Out of 1.3 million observations, this is a very miniscule problem. We had a limited GPS data, because the dataset had latitudes and longitudes of where the bikes were checked out and checked in. If we had a full GPS data of the path in fixed intervals, we could have build a plot that shows the actual trip paths of each bikes.

Future directions: It would have been better if we had more features in the dataset. For example, we could have done another analysis if we had the weather data and see the correlation of the bike usage vs temperature or bike usage vs weather conditions. Apart from additional data, if we analyze more than one month of data, we will be able to see more clear trends and have more confidence in our analysis or assumptions.

Lessons learned: A lot of people use the Citi bike than we expected and the age range of users is quite wide. We can clearly see that Citi bike is a favorable public transportation by full-time workers. For the maintenance purposes, Motive could prioritize popular stations for more efficient repairs. This could possibly cut the cost they are spending on precautionary measures.


## Notes:
+ _/analysis_ folder stores the _report.html_, _report.rmd_, _header.html_, _footer.html_, and _style.css_:
	+ _report.html_ is the result of our project
	+ _report.rmd_ is the file that creates the report
	+ _header.html_ contains the stylesheet of our font--[Open Sans](https://fonts.google.com/specimen/Open+Sans) and the [GitHub icon](https://github.com/tholman/github-corners) in the upper-right corner.
	+ _footer.html_ contains the codes for creating the [footer](https://holtzy.github.io/Pimp-my-rmd/#footer_and_header)
	+ _style.css_ contains the stylesheet
	
