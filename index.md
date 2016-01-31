---
title       : Pace conversion
subtitle    : A Shiny and Slidify Project
author      : Salvatore Lenza
job         : Jan 31, 2016
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---
## Pace conversion - Introduction


My application, Pace conversion, was created for a class project in the Developing Data Products course. course is part of the Data Science Specialization currently being offered by Johns Hopkins University on Coursera https://www.coursera.org/jhu

The peer assessed assignment has two parts:
  1. Create a Shiny application and deploy it on Rstudio's servers.
  2. Use Slidify or Rstudio Presenter to prepare a reproducible pitch presentation about your application.

You can find my application here:

https://sallen68.shinyapps.io/shiny/

---
## Pace conversion - Tool function


The application provides at the runners the ability to convert 
the pace in veloci.y value . Is possible to set units in kilometers
or in miles. After every parameters change is necessary to click 
the refresh button .

---
## Pace conversion - Input

With Shiny User Interface, Runner can set pace in minutes and seconds
for two different kind of distance unit: kilometer or mile. 
For minutes and seconds input is possible use a "Slider Input Widget" 
while for the unit distance selection there is a 
"Select list input control".

---
## Pace conversion - Output


The converter outputs are:

  1. minutes per km;
  2. km per hour";
  3. minutes per mile;
  4. miles per hour.

