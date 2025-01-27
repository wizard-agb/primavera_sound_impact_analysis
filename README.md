# Primavera Sound Impact Analysis

## Project Intro/Objective
The purpose of this project is to understand the impact of the Primavera Sound Festival on Hotel Prices in Barcelona. 

## Project Description
In this project, we determine the impact of the Primavera Sound Festival in Barcelona using a differences and differences analysis. 


### Differences and Differences Set Up
First, we selected a control city, Valencia. We selected this city using a combination of climate and population statistics, and also made sure that there was no significant event happening in Valencia during the Primavera Sound festival week. 

<div align="center">
  <img width="547" alt="Screenshot 2025-01-27 at 11 36 48 AM" src="https://github.com/user-attachments/assets/37f74074-113e-4840-858f-f9507b2af5d7" />
</div>

We selected comparable time frames for each location. For diff and diff, we select a control time frame (when a major event is not happening for both cities), and an event time frame for both cities.  

<div align="center">
<img width="469" alt="Screenshot 2025-01-27 at 11 37 32 AM" src="https://github.com/user-attachments/assets/45e5c300-be22-478a-88f6-df37b2fb50a1" />
</div>

### Data Overview

We created a scraper of Booking.com to get data for the selected weeks, and collected metadata for hotel advertisements in each city.

We engineered features including hotel distance from the event, review count, and review NLP analysis, and ran regressions.

### Model Overview

Here we see the baseline diff and diff analysis showing our city x event week control variable was highly significant, contributing to around a €106 increase in prices.

<div align="center">
<img width="782" alt="Screenshot 2024-04-12 at 7 03 36 PM" src="https://github.com/agbennett-bse/primavera_sound_impact_analysis/assets/145025558/fc877e9a-ade0-4759-b189-9557aeb649b2">
</div>

Here we see our more robust model with NLP description keyword and ratings features. Still, we observe that the city x event week control variable has the largest impact with high significance.

<div align="center">
<img width="571" alt="Screenshot 2025-01-27 at 11 42 26 AM" src="https://github.com/user-attachments/assets/df40de9c-06c1-48da-88d3-144d0cdeed4c" />
</div>

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
