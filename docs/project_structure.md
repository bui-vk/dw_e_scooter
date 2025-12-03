---
title: Value Proposition
nav_order: 1
---

[Team Member Name]
{: .label }

# Project Structure

<details open markdown="block">
  <summary>
    Table of contents
  </summary>

- [Project Title](#target-groups)
- [Persona Definition](#portfolio-creation)
- [Data Sources](#conclusion)
- [Key Analytical Questions](#conclusion)
- [Technology Stack ](#conclusion)

</details>

## Project Title

**Project Title**

Optimizing Micro-Mobility Fleet Operations in Washington D.C. using Vehicle and Environmental Data

## Persona Definition

**Persona Definition**

An Operations Manager at a Micro-mobility company in Washington D.C. that wants to optimise fleet management, including their e-scooters, e-bikes and service team

## Data Sources

**Data Sources**

- Data on e-scooters + bikes for Lime in Washington (JSON) (data.lime.bike/api/partners/v1/gbfs/washington_dc/free_bike_status.json)
  - start, end points
  - e-scooter or e-bike
  - duration of trip
  - bike/scooter ID
- Weather Data Washington (OpenWeatherMap API)
- Terrain Data Washington (OpenStreetMap API)
- maybe: docked bike data

## Key Analytical Questions

**Key Analytical Questions**
Rebalancing: What are the top 5 "dead zones" where scooters are frequently dropped off (e.g., a residential neighborhood) but rarely picked up, requiring me to retrieve them?
Predictive Maintenance: Which specific scooters are showing unusually high battery drain relative to the distance and terrain (e.g., draining fast on flat ground) that might signal a bad motor or battery? (AI generated battery data?)
Demand: User app data shows many people opening the app in the entertainment district around 6 PM, but trip data shows few rides starting. Are all the scooters there low on battery, or are there simply not enough? (AI generated App data?)
Asset Recovery: Which scooters haven't moved or checked in for more than 48 hours, and are they in unusual locations (like a private backyard or off-street) where they might be lost or stolen?
How much time (on average) do vehicles remain idle before being used again?
Which areas require frequent manual retrievals? lime only
Are e-bikes more popular than e-scooters in certain neighborhoods or terrain types?
How do usage patterns differ by time of day, day of week, and weather condition?
if using docked bike and lime data:
Where are e-bikes/scooters being used more frequently by Lime users, which could inform where we can build another bike station?


Technology Stack (Example):

Google Cloud 
Power BI for viz
