# UFO Reports Analysis

## Overview
This repository contains a final project that I did as part of a data analytics course. It takes a look at UFO sighting locations, descriptions, and characteristics. It also looks at some of the top Science Fiction movies and their potential impact on UFO sightings. Did they cause an increase/descrease in sightings? 

# List of movies analyzed
- Alien (1979)
- Arrival (2016)
- District 9 (2009)
- E.T. (1982)
- The Fourth Kind (2009)
- Guardians of the Galaxy (2014)
- Independence Day (1996)
- Men in Black (1997)
- Signs (2002)
- War of the Worlds (2005)

## Link to dashboard
https://app.powerbi.com/view?r=eyJrIjoiNGQwMDkxMDUtY2E1ZS00OWVlLTg5ZGUtMjYwNDAzNTJhODMxIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9&pageName=ReportSection964e7f5c5e043479a460

## Table of Contents
- [Overview](#overview)
- [Project Details](#project-details)
- [Data Sources](#data-sources)
- [Methods and Tools](#methods-and-tools)
- [Conclusions](#conclusions)

## Project Details
- **Objective:** Explore common characteristics among UFO sightings in the U.S. and 
                 examine potential causes for an increase/decrease in reported sightings

- **Dataset:** The NATIONAL UFO Reporting Center Online Database

- **Analysis:** Scraped the data from NUFORC database. Imported data into PowerBI and compared report dates with popular Sci-Fi movie release dates

## Data Sources
- https://nuforc.org/databank/

## Methods and Tools
- Python
    Used requests and BeautifulSoup modules to webscrape from source site 
    Used pandas to clean and prepare data
- PowerBI

## Conclusions
- The findings are inconclusive. 
- The reported shapes do not appear to have been affected by the release of any of the movies. For example, a movie which featured sphere-shaped spaceships did not see an increase in reports of spherical UFOs. A movie which heavily featured alien abductions did not see an increase in reports of alien abductions.
- The majority of movies are viewed on Friday and Saturday. These days already have a higher than average number of reports compared to other days, which makes it more difficult to attribute the increase in reports to a movie release
- Would need more data to make an accurate conclusion




