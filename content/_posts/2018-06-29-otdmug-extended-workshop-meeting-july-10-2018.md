---
author: AndrewTheTM
date: '2018-06-29'
title: OTDMUG Extended Workshop Meeting - July 10, 2018
---

## Introduction

This class will be a basic introduction to R in the context of travel modeling and transportation planning.

The class particulars (location, time) have been sent via email. Please remember to bring money for lunch and donations to the OTDMUG Refreshment Fund.

## Preparation

Students will need their own laptop with R and R Studio installed, and will be provided data to work with.

R can be installed from https://cran.r-project.org/

RStudio can be installed from https://www.rstudio.com/products/rstudio/download/ (the Open Source License distribution is free)

Upon installing R and RStudio, there will be some packages needed for the training - these should be installed in advanced, as we don’t know if (or how good) the Wifi is in the ODOT Training Facility.

Open RStudio, and go to Tools - Install Packages. In the “Packages…” textbox, paste this text:  
dplyr tidyr rmarkdown ggplot2 foreign reshape2 openxlsx scales RColorBrewer kableExtra

RStudio will download and install these packages.

Additionally, download the Data File and decompress it onto your computer. All scripts are included in the file so everyone can follow along without delay for people to type commands. You should be able to open the data file in RStudio by opening RStudio and opening the project from there (don't worry if you can't get **there**, we can do that in class).

## Data
There are five data files in the zip archive, none of it official:

 * Amtimecompare.xlsx: transit-highway time comparison of unknown vintage.

 * C_D15HASSIGN.DBF: Loaded highway network.

 * HHList.csv: random sample of 1,000 households from ABM.

 * PerList.csv: persons corresponding to HHList.csv.

 * Trips.csv: random sample of 10,000 trips from ABM.

The schedule will be provided at the training session.
