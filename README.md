# Terrorism Analysis: Insights Through Visualization 🇮🇳💥

## Project Overview

This project focuses on analyzing historical terrorism incidents in India to uncover patterns, identify geographical hotspots, and visualize trends in attacks and casualties over time. Leveraging data from the Global Terrorism Database, this analysis aims to provide insights into the dynamics of terrorism within India.

## Problem Statement / Objectives

The primary objectives of this visualization project were to:

* **Explore Patterns:** Uncover temporal and geographical patterns of terrorism in India.
* **Geographical Hotspots:** Highlight regions most affected by different types of attacks.
* **Trend Analysis:** Analyze trends in casualties and attack frequencies over the years.
* **Impact Visualization:** Create compelling visualizations to communicate the severity and spread of incidents.

## Data

The analysis utilizes data from the **Global Terrorism Database (GTD)**.

* **Source:** National Consortium for the Study of Terrorism and Responses to Terrorism (START) at the University of Maryland.
* **Dataset Description:** Covers terrorism incidents specifically within India from 1970 to the present (based on the context of the dataset). It includes detailed information on attack types, casualties, geographical locations, and more.
* **Key Variables Used:**
    * `iyear`: Year of the incident.
    * `imonth`: Month of the incident.
    * `region_txt`: Region of the incident.
    * `attacktype1_txt`: Type of attack (e.g., Armed Assault, Bombing).
    * `nkill`: Number of people killed.
    * `latitude`, `longitude`: Geographical coordinates for mapping.
    * `success`: Whether the attack was successful (implied from analysis).
    * `nperpcap`: Number of perpetrators captured (implied from analysis).
    * `crit1`, `crit2`, `crit3`: Criteria for inclusion in GTD (implied from source).

## Methodology & Analysis

This project primarily involved **Exploratory Data Analysis (EDA)** and advanced **data visualization** techniques.

* **Data Cleaning and Preprocessing:** Handled missing values (e.g., for `nkill`, `nperpcap`). Ensured data types were appropriate for analysis and visualization.
* **Geospatial Analysis:** Utilized latitude and longitude to map attack locations and visualize severity.
* **Temporal Analysis:** Examined yearly and monthly trends in attack frequency and casualties.
* **Categorical Analysis:** Explored distribution of attack types and their impact.
* **Interactive Visualizations:** Employed libraries capable of creating interactive plots for better exploration of patterns (as suggested by the `.html` output).

### Key Visualizations & Insights

* **Geographical Map:** Visualized attack severity across India, highlighting high-severity areas (e.g., Mumbai, Northern India) and lower-severity areas (e.g., coastal regions on the western side).
* **Yearly Trends:** Showcased the number of attacks over the years, likely indicating peaks and troughs in terrorist activity.
* **Interactive Dashboards/HTML Outputs:** (If the HTML file is an interactive dashboard) Demonstrated the ability to create dynamic reports for deeper data exploration.

## Tools and Technologies

* **Languages:** R
* **Libraries:** `ggplot2` (for static and potentially interactive plots), `leaflet` (for interactive maps), `dplyr` (for data manipulation), and potentially `plotly`, `shiny` (if `651_project1 (3)-1.html` is a dashboard).
* **Tools:** RStudio, Quarto (implied by the HTML output, as it often uses Quarto for rendering).

## Files in this Repository

* `Terrorism_Analysis_R_Code.R` (or similar name for your R script/Rmd if not already named clearly): The R code used for data loading, cleaning, analysis, and visualization.
* `Global Terrorism Database (GTD) - India Subset.csv` (or similar): The cleaned dataset used for analysis. *Note: If the full GTD is very large, you might only include a subset or link to the original Kaggle/START source instead of uploading the full CSV.*
* `Attacks in India By Terrorist.pdf`: The project presentation slides (converted from PPTX).
* `651_project1 (3)-1.html`: The HTML output of your R Markdown or Quarto project, likely containing interactive visualizations.
* `README.md`: This file, providing an overview of the project.

## Collaborators

* Sreenivas Annagiri
* Sakshi Gundawar
* Ashutosh Kumawat

---
