# Overview
This repository is for storing my work with TransitMatters.

## Setting up Google Vertex AI Workbench

Using a VAI workbench with Debian 11 and R 4.3, the following commands must be run in the terminal to install the necessary packages:

For most packages run: sudo apt install libudunits2-dev libgdal-dev libgeos-dev libproj-dev

For package `tmaptools` run in R: `Sys.setenv(XML_CONFIG="/usr/bin/xml2-config")`