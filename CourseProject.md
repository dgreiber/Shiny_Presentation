Developing Data Products Course Project
===

author: Dan Greiber
date: April 25, 2015

Goal of this presentation
=== 

This is the final course project for the Developing Data Products course of the Data Science Specialization class.
The goal of this presentation is two fold:
- Create a Shiny application 
- Present that application for viewing

The Shiny application results presentation slide pages can be built using either Slidify or Rstudio Presenter.  Mine was built using Rstudio Presenter.


Application Description
========================================================
I used the mtcars data set as my reference to create a dynamic data frame. The data is dynamically generated upon the viewers selection preferences. Some of the display options available to the viewer are:

- Column sorting
- Column filtering
- Custom search filtering

A link to the site can be found <a href="http://dgreiber.shinyapps.io/Shiny/">**here**</a>

Application results
========================================================
Data results can be dynamically generated quickly and easily then displayed with embedded R code as shown below.


```r
plot(cars)
```

![plot of chunk unnamed-chunk-1](CourseProject-figure/unnamed-chunk-1-1.png) 

Final analysis
===
Shiny applications can be quickly designed and developed.  The results can be designed and displayed quickly and easily using either Slidify or Rstudio Presenter.  Either of the two options are perfectly suited to create professional looking test results with little web programming experience.  R code can be easily embedded into Shiny applications giving them additional flexability and functionality.


<font color='blue' size="4">Good luck to everybody on their final course project and the upcoming Data Science Capstone!</font>
