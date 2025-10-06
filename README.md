# Open Season: Developing a Collections Response to the Draft, Tri-Agency Open Access Policy on Publications at the University of Toronto Libraries 

## Overview
This repository contains all input files necessary for extracting institutionally affiliated author publications in a given date range for a specific publisher. The data corpus formed through htis code include corresponding and non-corresponding author information for open access and closed articles. The resulting corpus can provide insights into the number and types of articles and adjacent documents that affiliated authors publish, which can be used to inform future open access publishing policies. 

The University of Toronto Libraries 'Respond to Updated Tri-Agency OA Mandate' Working Group used this data corpus to identify publishers for evaluation of author rights and compliance in light of the Tri-Agency Policy on Open Access Publications. A selection of Working Group members presented data obtained from this repository's code alongside their publisher evaluation criteria at the [1st Canadian Conference on Open Science and Open Scholarship](https://oscanada.github.io/en/) on October 8, 2025, in Montreal, QC, Canada.

## Requirements 
The code require RStudio. To run the code stored in this github, you will need to have both of these installed. We recommend using RStudio on your local computer or Posit Cloud as your IDE. 

Following the download of RStudio, you will need to download the packages associated with this project. These are:
* dplyr
* writexl
* readr
* openalexR
* tidyverse
* readxl

## Downloading Data
Instructions to download data needed to run this code is available [here](https://acrobat.adobe.com/id/urn:aaid:sc:VA6C2:1692e4dc-701d-4344-b38b-0fa9e4b491db) and within the repository files. This document provides an overview of the manual data downloading required and describes the process undertaken by the code to pull in OpenAlex data using an API, clean the individual data source code, and compile the deduplicate results. 

## Using the Repository
* Download the repository as a ZIP file to your computer
* Input data collected into their respective folders (i.e., Scopus data in "scopus" and WOS data in "wos"
* Open the Rproj and Rmd file
* Follow the "UPDATE" comments throughout the Rmd file to make changes to the code to suit your needs
* Run code
* A CSV and XLSX version of the results (corresponding author and not) will be available in the output folder.

## Acknowledgments
The code presented within this repository was originally created by [Marco Chau](https://www.linkedin.com/in/marco-chau-8897091b1/?originalSubdomain=ca). It has since been updated by [Chloe Thierstein](https://www.linkedin.com/in/chloe-t-850246249/). 

The University of Toronto Libraries Respond to Updated Tri-Agency OA Mandate Working Group consists of:
* [Naz Torabi](https://onesearch.library.utoronto.ca/library-staff/naz-torabi) (Co-Lead)
* [Graeme Slaght](https://onesearch.library.utoronto.ca/library-staff/graeme-slaght) (Co-Lead)
* [Erin Calhoun](https://onesearch.library.utoronto.ca/library-staff/erin-calhoun)
* [Shelby Thaysen](https://onesearch.library.utoronto.ca/library-staff/shelby-thaysen)
* [Chloe Thierstein](https://www.linkedin.com/in/chloe-t-850246249/)
* [Kate Johnson](https://onesearch.library.utoronto.ca/library-staff/kate-johnson)
* [Garni Assadourian](https://onesearch.library.utoronto.ca/library-staff/garni-assadourian)
* [Andrew Ip](https://onesearch.library.utoronto.ca/library-staff/andrew-ip)
* [Holly Inglis](https://onesearch.library.utoronto.ca/library-staff/holly-inglis)
* [Madeline Gerbig](https://onesearch.library.utoronto.ca/library-staff/madeline-gerbig)
* [Yayo Umetsubo](https://onesearch.library.utoronto.ca/library-staff/yayo-umetsubo)
* [Michelle Spence](https://onesearch.library.utoronto.ca/library-staff/michelle-spence)








