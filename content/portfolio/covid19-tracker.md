---
title: "COVID-19 Tracker"
description: "Shiny app for easy country comparisons"
date: '2020-03-20'
link: ''
screenshot: 'mentalBreaks_covid-19-tracker.png'
layout: 'portfolio'
featured: 'false'
---

This COVID-19 Tracker Shiny app allows easy comparison of cumulative outcomes and growth rates of the COVID-19 coronavius between countries using the data provided by the [Johns Hopkins University Coronavirus Resource Center](https://coronavirus.jhu.edu/).      
  
Users can select any of the country/region units available in the entire JHU GSSE dataset, standardize them on the x-axis using "Days since *N*", and automatically generate clean level- and log- plots with dynamically rendered titles and axis labels. 

Currently, a maximum of six countries can be compared at a time to allow for better readability of the resulting plots. Users can select between *total confirmed cases*, *deaths*, and *total recovered* as the different y-axis outcome variables.   

The data in the app is time-stamped and updated automatically along with the JSU CSSE repo, and there are download buttons for the plots and filtered long-format data tables use for those plots in PNG and CSV formats, respectively.   

A separate tab in the app allows for the generation of bar charts of daily case and death totals for the same selection of countries, including a 5-day moving average trend line.
  
>**UPDATE (5 Oct. 2021)**: I created this app so that I could quickly visualize and compare data for the countries that I was personally most interested in during the early days of the pandemic, before the subsequent explosion of dashboards and apps appeared online relating to all things COVID-19. I haven't had time to work on this in over a year, and others have created far better versions, so I've decided to archive the project. For reference, the [code for this app remains available on my Github](https://github.com/anguyen1210/covid19-tracker). 

![](/portfolio/covid19-tracker_files/mentalBreaks_covid-19-tracker_daily.png)
  
