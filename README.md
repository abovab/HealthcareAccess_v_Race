# HealthcareAccess_v_Race
<p>
Data visualizations of racial disparity in healthcare access across US counties. Interactive dashboard allows users to explore relationships
between healthcare access, income, life expectancy, and race on the state and county level.



Contents:

readme.md -- You're looking at it
H.pkl — Dataframe of county data
S.pkl — Dataframe of State data
hospital.pkl — Datframe of hospital data
Dashboard.py — runs dashboard
data_prep.py — program used to clean and prep data (original data not included)


Motivation:

Project to show racial disparities in healthcare. Dashboard allows for user to explore relationships
between healthcare access, income, life expectancy, and race on the state and county level. Unfortunately, I couldn’t directly save dashboard as
html, so it will have to be run from command line.


Requirements to Run Dashboard:

dash
geopandas
json
bumpy
pandas
pickle
plotly
urllib.request


To run from command prompt:

1. python3 Dashboard.py
2. copy displayed url into browser to open dashboard
