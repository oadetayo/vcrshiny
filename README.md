# vcrshiny
A data package and shiny app for visualizing research data collected as part of the Virginia Coast Reserve Long-Term Ecological Research (VCR LTER) program. This application is in early beta and should not be expected to work properly :ghost:. 

Read more about the program [here](https://www.vcrlter.virginia.edu/home2/).

Installation:
```
devtools::install_github("seanhardison1/vcrshiny")
```

To access up-to-date time series of air and water temperatures, precipitation, wind speeds, and tides from the VCR:
```
vcrshiny::vcr_phys_vars
```

To run the dev version of this app locally:
```
vcrshiny::run_app()
```
