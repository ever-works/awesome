# Skytrax Air Travel Reviews Dataset

**Category:** Datasets  
**Brand:** skytrax-data-by-quankiquanki  
**Source:** <https://github.com/quankiquanki/skytrax-reviews-dataset>

## Overview
A scraped air travel dataset containing user reviews from Skytrax (airlinequality.com). It aggregates reviews across airlines, airports, seats, and lounges, suitable for text mining, sentiment analysis, and service quality research in air transportation.

## Features
- **Data origin**
  - User reviews scraped from Skytrax (airlinequality.com)
  - Publicly viewable web content at time of collection
  - Robots.txt reportedly did not prohibit scraping at the time

- **Data structure**
  - Reviews split into **4 CSV files**, one per category:
    - Airline reviews
    - Airport reviews
    - Seat reviews
    - Lounge reviews

- **Dataset sizes**
  - **41,396** airline reviews
  - **17,721** airport reviews
  - **1,258** seat reviews
  - **2,264** lounge reviews

- **Example schema details** (as described in repository)
  - Airline dataset includes multiple columns (e.g., airline name and other review-related attributes; full column listing is in the repository’s README and CSV headers).

- **Supplementary materials**
  - `data/` folder with the four CSV files
  - `run_stats.py` for computing basic statistics on the datasets
  - README with documentation of format and sample counts

- **Use cases**
  - Analysis of airline and airport service quality
  - Sentiment analysis and opinion mining on travel reviews
  - Benchmarking for NLP models on user review data
  - Studying relationships between ratings and textual content

- **References / example analyses**
  - Blog post: “Exploring Reviews of Airline Services” – <http://www.quangn.com/exploring-reviews-of-airline-services/>
  - Article: “What Are the Worst Airports in the World?” – <http://priceonomics.com/what-are-the-worst-airports-in-the-world/>

## Licensing
- Repository is released under **CC0-1.0** (public domain dedication) for the code and packaging.
- The original Skytrax reviews’ license status is **unknown**; they were publicly accessible on the web at collection time.

## Pricing
- Hosted as an open GitHub repository; no pricing information is provided (effectively free to access/download from GitHub, subject to GitHub terms and original content rights).