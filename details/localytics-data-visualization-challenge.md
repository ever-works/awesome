# Localytics Data Visualization Challenge

**Category:** Data Competitions  
**Tags:** data-visualization, datasets, challenges  
**Source:** https://github.com/localytics/data-viz-challenge

## Overview
The Localytics Data Visualization Challenge is a GitHub-hosted competition focused on building visual analytics for a fictional mobile crowdfunding app called **BootLoader**. Participants use a provided event dataset to design visualizations that identify which users are most likely to be interested in a new 3‑speed bicycle project.

## Scenario
- BootLoader is a mobile app for crowdfunding creative projects.
- A user, Dennis Ridesalot, launches a bicycle project: 3‑speed bike, recycled parts, $20 price point.
- The BootLoader team wants to send targeted push notifications about this project to users who are likely to be interested, rather than the entire user base.
- Participants play the role of the “resident data expert,” creating visualizations to answer: **Which kinds of users would be interested in the bicycle project?**

## Dataset & Attributes
Participants receive a sampled time series of **50,000 analytics events** from one month. Each event includes both action and user attributes.

### Event Types
- `View Project` – user views project details.
- `Fund Project` – user funds a project.

### Event Attributes
- `category` – project topic, e.g. `"Sports"`, `"Fashion"`, `"Technology"`, etc.  
  - Bicycle project belongs to **two categories**: `"Sports"` and `"Environment"`.
- `client_time` – UNIX timestamp of when the event occurred.
- `amount` – donation amount (present only for `Fund Project` events).

### User Attributes (embedded in each event)
- `session_id` – unique identifier for each user.
- `age` (age range) – one of:
  - `"18-24"`
  - `"25-34"`
  - `"35-44"`
  - `"45-54"`
  - `"55+"`
- `gender` – one of: `"M"`, `"F"`, `"U"` (unknown/unspecified).
- `location` object:
  - `city` – U.S. city.
  - `state` – U.S. state.
  - `latitude`
  - `longitude`
  - (example JSON also references `zip_code`).
- `marital_status` – one of: `"single"`, `"married"`.
- `device` – one of: `"iOS"`, `"android"`.

### Behavioral Assumption
- From past experiments, each user tends to prefer projects within a single category (e.g., a user who consistently views/funds `"Technology"` projects is assumed to like that category).
- The bicycle project is associated with both `"Sports"` and `"Environment"`, so affinity to either category may indicate interest.

## Challenge Goal
Create data visualizations that help:
- Identify users or user segments most likely to be interested in the new bicycle project.
- Inform how to **segment push notifications** using attributes such as:
  - location (city, state, coordinates),
  - age range,
  - gender,
  - device type.

Example segmentation capability: send a push notification to **all iOS users in Chicago, IL** with a tailored message.

## Features
- **Realistic mobile analytics dataset** with 50,000 timestamped events.
- **Two core event types** (`View Project`, `Fund Project`) with monetary amounts for funding.
- **Rich user demographic and device attributes** embedded into each event.
- **Geospatial information** (city, state, latitude, longitude) to enable mapping and location-based analysis.
- **Behavioral categorization** via project `category`, including multi-category projects (`"Sports"` and `"Environment"` for the bicycle project).
- **Segmentation-ready structure** suitable for targeting based on demographics, location, and device.
- **Time-series component** using UNIX timestamps for temporal and trend analysis.
- **Competition framing** encouraging exploration of data visualization libraries and techniques.

## Pricing
Not applicable (open data challenge; no pricing information provided).
