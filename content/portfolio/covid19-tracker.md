---
title: "COVID-19 Tracker"
description: "Shiny app for easy country comparisons"
date: '2020-03-19'
link: 'https://mentalbreaks.shinyapps.io/covid19/'
screenshot: 'p_log10.png'
layout: 'portfolio'
featured: 'false'
---

This [COVID-19 Tracker Shiny app](https://mentalbreaks.shinyapps.io/covid19/) allows easy comparison of cumulative outcomes and growth rates of the COVID-19 coronavius between countries using the data provided by the [Johns Hopkins University Coronavirus Resource Center](https://coronavirus.jhu.edu/).      
  
Users can select any of the country/region units available in the entire JHU GSSE dataset, standardize them on the x-axis using "Days since *N*", and automatically generate clean level- and log- plots with dynamically rendered titles and axis labels. The data in the app is timestamped and updated automatically along with the JSU CSSE repo, and there are download buttons for the plots and filtered long-format data tables use for those plots in PNG and CSV formats, respectively.   
  
Currently, a maximum of six countries can be compared at a time to allow for better readability of the resulting plots. Users can select between *total confirmed cases*, *deaths*, and *total recovered* as the different y-axis outcome variables.   
  
Additional features and edits will be added on an ongoing basis.     
  
[Code for the app available on Github](https://github.com/anguyen1210/covid19-tracker). 
  
Feedback, comments and pull requests are welcome. Feel free to send me an email or leave your comments directly on the [COVID-19 tracker post](https://mentalbreaks.rbind.io/posts/covid-19-tracker/).