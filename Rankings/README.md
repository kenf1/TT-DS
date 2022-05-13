# ITTF Rankings

### Two scripts, one purpose.

Each script `ITTF_Rankings.qmd` (written in Python) and `Rankings_rvest.Rmd` (written in R) does the following: web scrape, tidy, and store an ITTF rankings dataset inside a comma-separated-value (.csv) file based on the link passed into the `url` variable. Each separate competition type will have its own separate .csv file. All .csv files are named following the format of: `Competition Type` + `Year` + `Week`.

Python version: [link](https://kenf1.github.io/Rendered/Scraper-Py/)

R version: [link](https://kenf1.github.io/Rendered/Scraper-R/)