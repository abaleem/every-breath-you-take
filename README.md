# Every Breath You Take
 An interactive visualization that analyses the air quality of different states and counties across United States.  
 
  
## **[Click here to view the visualization](http://shiny.evl.uic.edu:3838/g3/Every_Breath_You_Take/)**
 
 
 
 ## Purpose
 `I’m supposed to be in school, but instead I’m out here trying to make sure that my kids don’t grow up in a wasteland.` — Arielle Geismar, 17, An excerpt from The New York Times.
 
The above statement was stated by a teen student from Manhattan concerning the Climate Change. When many such youngsters took to the roads on March the sixteenth, concerned about their progeny at such a young age, we know that something is really not going the way it should. Today, Climate Change is an impending doom that we are facing collectively. It is not something that we can afford to be negligent or ignorant about.  

But, is it just a myth? Are we really doomed? Where's the proof? What do we do about it? WHAT DO WE KNOW ABOUT IT?  
  
The changes in climate and air quality are very gradual and hard to notice in the environment. In this project we tried studying the Air Quality data, by drawing meaningful patterns from it, by infering a sequence of events correlating a consequence which could serve as a forewarning to us, and help save the environment.  
  
We collected data regarding various attributes which correspond to the Air Quality such as Temperature, Levels of various Pollutants in the air such as Carbon Monoxide, Nitrous Oxide, Sulphur Dioxide, Ozone, etc. We have analysed the trends of the above stated components over the span of the last forty years to establish a significant change in our ecosystem. We have toyed with the data from all angles and explored best visualization practices to effectively communicate this message accross.  


## Setup

Softwares required:- **R** and **RStudio**  

Download and install R: https://cran.cnr.berkeley.edu/. (R (20178-12-20 Eggshell Igloo))  
Download ans install RStudio: https://www.rstudio.com/products/rstudio/download/. (R-Studio (1.1.463))

Libraries used:- **shiny, shinydashboard, ggplot2, lubridate, DT, grid, leaflet, scales, shinycssloaders, shinyWidget, tidyverse, tmap tmaptools, sf, splitstackshape, cdlTools, plotly**

To check currently installed libraries, type the following in R terminal
    installed.packages()[,1:2]
    
Libraries can be installed using the following command. Replace shiny with name of library you want to install.
    install.packages(shiny)
    
