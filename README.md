# Metis Data Science Bootcamp | Project 1
---

## Exploratory Data Analysis (EDA): NY Metro Transit Authority Turnstile Data

---
Project timeline: 4 days

**OUR TEAM**
- Elliot Wiens
- Wei Zhao
- Liam Isaacs

**BACK STORY**

WomenTechWomenYes (WTWY) holds an annual gala at the beginning of each summer in New York City. To promote the Gala, WTWY will place street teams at entrances to subway stations. The street teams collect email addresses and those who sign up are sent free tickets to their gala. *View the full backstory [here](etc/project_background.txt)*


**OUR GOAL**

To use MTA subway data to help WTWY optimize the placement of their street teams such that they can gather the most signatures, ideally from those who will attend the gala and contribute to their cause.

**DELIVERABLES / PRESENTATION**

 * 8-10 minute group presentation in which all group members speak. This includes: 
   * slide presentation (final pdf version [here](presentation_project1.pdf))
   * visual and oral communication in group presentations
   * organized project repository

---
**TECH STACK**

The following Python libraries were used to gather, clean, merge, and analyze the data:
- jupyter notebook
- pandas
- numpy
- pandas
- matplotlib
- seaborn
- google geocode API
- geopy
- geopandas
- json
- requests

**REQUIRED RESOURCES TO REPRODUCE LOCALLY**

- Python 3.x
- the above Python libraries (most of them included in anaconda distribution)
- free Google 'Geocode' API key (in order to look up zipcode using latitude & longitude)
- jupyter notebook (also built-in with anaconda)
- the US Census data file called '18zpallagi.csv' that can be downloaded directly [here](https://www.irs.gov/downloads/irs-soi?C=M%3BO%3DD&sort=desc&order=Ng%C3%A0y&page=3) 
  - this is not included in the repository, as it is too large.
  - the other necessary data files are in the [data](data/) folder

**NAVIGATING THIS REPOSITORY**

Our code for gathering, cleaning and merging the data can be found in [clean2.py](clean2.py)
  - the code in ``clean2.py`` was generated using jupyter notebook files.
  - some of this code is retained in [``wtwy_data_merge.ipynb``](wtwy_data_merge.ipynb)

**OUR CONCLUSIONS**
