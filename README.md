# COVID-19

This repo is pretty basic: 
 - `covid-19.Rmd` is the Rmarkdown file which contains the data analysis and visualization. This is intended to give a visual snapshot of the progression of coronavirus: by state, by region, or in total. Data is graciously provided by the NY Times [(accessible via Github)](https://github.com/nytimes/covid-19-data).
 - `covid-19.hmtl` is the HTML output produced by Rmarkdown, which is also shared on the blog.
 - `census-population-estimates.csv` contains population estimates from the U.S. Census Bureau, which are used in the analysis to scale new cases and deaths to the state's overall population (as of 2019).

TO DO: Change to a self-updating or refreshable dashboard using Shiny or other package. Of course, there is still a lot of room for cooler or interactive graphs, or more detailed analysis.
