# Overview
This repository is for storing my work with TransitMatters.

## Setting up Google Vertex AI Workbench

Using a VAI workbench with Debian 11 and R 4.3, the following lines of code must be run to install the necessary packages:

Run the following in terminal to be able to install most packages: `sudo apt install libudunits2-dev libgdal-dev libgeos-dev libproj-dev`

Run the following in R to install package `XML`, a dependency of `tmaptools`: `Sys.setenv(XML_CONFIG="/usr/bin/xml2-config")`