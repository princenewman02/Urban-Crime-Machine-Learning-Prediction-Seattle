
# Seattle Crime Rate Prediction

Modeling Urban Crime Rates from Socioeconomic, Built Environment, and Emergency Response Indicators: A Spatial Analysis of Seattle.

**Authors:** Hayat Kimo, Prince Appiah Nyarko  

**Course:** CPSC 5071  

**Year of Analysis:** 2022

## Model

```

crime_rate = population_density + median_income + unemployment_rate +

             commercial_land_use_ratio + transit_access + EMS_call_rate + police_incident_rate

```

## Project Structure

- `/code` — Jupyter notebooks and scripts

- `/data/raw` — Raw datasets organized by variable

- `/data/processed` — Cleaned and merged datasets

- `/report` — Proposal, progress reports, and presentation

## Data Sources

- Seattle Police Department Crime Data (data.seattle.gov)

- OFM Population Estimates (ofm.wa.gov)

- ACS 5-Year Estimates B19013, B23025 (data.census.gov)

- Seattle Land Use / Zoning (data-seattlecitygis.opendata.arcgis.com)

- King County Metro GTFS (kingcounty.gov/metro)

- Seattle Fire 911 Calls (data.seattle.gov)

- TIGER/Line Census Tracts 2022 (census.gov)

## Setup

```bash

pip install -r requirements.txt

```

