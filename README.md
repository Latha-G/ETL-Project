# ETL Project

## Team Members

Dianne Jardin**e**z, Aas**t**ha Arora, Swarna **L**atha

## Project Proposal
    -
    -

## Finding Data

The following Data Sources were used below:
- [IMDb Website](https://www.imdb.com/chart/top/?ref_=nv_mv_250)
    - Method: Webscraping
    - Used for: Collecting the Top 250 IMDB rated movie list

- [OMDb API](http://www.omdbapi.com/)
    - Method: API Extraction
    - Used for: Collecting IMDb id and other movie related details like actor, director, etc.

- [Utelly API](https://rapidapi.com/utelly/api/utelly?endpoint=apiendpoint_3cad787b-ca7b-449a-84b4-23b40d64fd73)
    - Method: API Extraction
    - Used For: Collecting streaming options for Top 250 IMDb movies

- [uNoGS API](https://rapidapi.com/unogs/api/unogs/endpoints)
    - Method: API Extraction
    - Used For: Collecting movies on Netflix in released in the United States which have an IMDb rating greater than or equal to 7

- [Google Search Engine](https://www.google.com/search?&q=)
    - Method: Webscraping
    - Used for: Collecting viewing Streaming Service availability and price 

## Data Cleanup & Analysis

- Data extracted were formated in CSV and JSON files
- The data formated files were manipulated in pandas to clean, join, and filter 7 tables

## Project Report
- **E**xtract: 

- **T**ransform:  

- **L**oad: 