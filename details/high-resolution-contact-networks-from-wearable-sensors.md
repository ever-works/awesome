# High-Resolution Contact Networks from Wearable Sensors

**Category:** Datasets  
**Source:** [SocioPatterns – Datasets](http://www.sociopatterns.org/datasets/)  
**Brand:** awesomedata

## Overview
A collection of high-resolution temporal contact network datasets obtained through the SocioPatterns sensing platform. The datasets capture close-range proximity and interaction patterns between individuals (humans and animals) using wearable sensors and, in some cases, complementary observational data.

## Features
- **High-resolution temporal contact networks**
  - Time-resolved records of face-to-face or close-proximity interactions.
  - Data suitable for dynamic network analysis and temporal graph modeling.

- **Wearable proximity sensors**
  - Contacts measured via the SocioPatterns sensing platform.
  - Objective, sensor-based detection of spatial proximity.

- **Multiple social settings and populations**
  - **Human social contacts** (e.g., rural village in Malawi):
    - 86 individuals living in a village in rural Malawi.
    - Observational contact data collected and analyzed for social contact pattern characterization.
    - Dataset file example: `tnet_malawi_pilot.csv` (time-resolved network data).
  - **Animal social interactions** (e.g., Guinea baboons):
    - Group of 20 Guinea baboons in an enclosure at a Primate Center in France.
    - Data collected between June 13, 2019 and July 10, 2019.
    - Includes both wearable sensor data and detailed observational records.

- **Detailed observational annotations (Baboons’ interactions dataset)**
  - `OBS_data.txt` file containing behavioral events with 8 columns:
    - **DateTime** – Timestamp of the event (start time for state events).
    - **Actor** – Name/ID of the individual performing the behavior.
    - **Recipient** – Name/ID of the individual receiving the behavior.
    - **Behavior** – Labeled behavior type. Registered behaviors include:
      - Resting, Grooming, Presenting, Playing with, Grunting-Lipsmacking,
        Supplanting, Threatening, Submission, Touching, Avoiding, Attacking,
        Carrying, Embracing, Mounting, Copulating, Chasing.
      - Additional categories: Invisible, Other.
    - **Category** – Behavior classification:
      - Affiliative, Agonistic, Other.
    - **Duration** – Duration of the observed behavior (POINT events have no duration).
    - **Localisation** – Zone of the enclosure where the behavior occurs.
    - **Point** – Indicator for point vs. state events (as described in the dataset docs).

- **Published and documented datasets**
  - Datasets are linked to peer-reviewed publications detailing data collection and analysis methodologies (e.g., EPJ Data Science, Proc. R. Soc. A).
  - Each dataset page provides download links (e.g., `*.csv.gz`, text files) and study context.

- **Use cases**
  - Modeling and simulation of infectious disease transmission via contact networks.
  - Analysis of human social mixing patterns in real-world environments.
  - Study of animal social structure and comparison of sensor-based vs. direct observation methods.
  - Methodological research in temporal networks and behavioral ecology.

## Data Access
- Data are available through the SocioPatterns website under the **DATA / Datasets** section:  
  [http://www.sociopatterns.org/datasets/](http://www.sociopatterns.org/datasets/)
- Individual dataset pages provide direct links to data files (e.g., `tnet_malawi_pilot.csv.gz`, `OBS_data.txt`) and detailed documentation.

## Pricing
- No pricing information is provided in the source content. Access conditions (e.g., open data, licensing) should be checked on each dataset’s page on the SocioPatterns website.