### Data Visualization Portfolio

A small personal site of data visualization case studies, built for DST 490 (Spring 2026) with Quarto. Each post walks through a real dataset end-to-end: cleaning, an analytical question, and a finished visualization with the reasoning behind the design choices.

#### Posts

**Housing Prices and Square Footage** - exploring the relationship between home size and sale price using Zillow sample data.

**SNAP Enrollment Boxplots** - a starter visualization for the Hennepin County SNAP/MFIP project (see the companion [Hennepin County SNAP/MFIP Capstone Analysis](https://github.com/vjrupp49/hennepin-county-snap-mfip-analysis) repo for the full group project). Boxplots showing the spread of census-tract-level enrollment gaps within each city, to make the point that a single city-wide number can hide a lot of internal variation.

**Interactive SNAP Participation Gap Map** - an interactive Leaflet map of SNAP/MFIP participation gaps across Hennepin County census tracts, letting a viewer explore gap rate by year and surface the highest-gap tracts directly rather than reading them off a table.

#### Data note

The SNAP/MFIP dataset used in the last two posts comes from the Hennepin County group capstone project (with Brandon Bloss and Ini Udomah) - these two visualizations are Vincent's individual extensions of that shared dataset for this portfolio assignment. Underlying census tract/place boundary shapefiles (US Census TIGER/Line) and a couple of large generic reference datasets (Education, Unemployment) are not included here for size; they're standard public data available from census.gov and the BLS.

#### Tech

Quarto, R (tidyverse, sf, leaflet)
