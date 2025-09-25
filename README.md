# Spotify-Analysis
Power BI Project
## 📋Project Overview
Transforms raw Spotify streaming exports into an interactive Power BI dashboard.
Shows total plays, yearly trends, and top artists, albums, and tracks.
Reveals weekday vs. weekend habits and changes in music preferences over time.
## ❓Problem Statement
Spotify provides detailed streaming data, but the raw export is hard to interpret and doesn’t easily reveal listening habits or trends.
This project transforms personal Spotify data into an interactive Power BI dashboard that highlights total plays, year-over-year trends, top artists, albums, and tracks—making it simple to understand music preferences and how they change over time.
## 🖥️Live Dashboard
Link for the Spotify Analysis Dashboard -  [Live Dashboard]( https://app.powerbi.com/groups/me/reports/19e26e67-b09b-4763-bb5c-80b22cff067d/f4f13cf6c6cb9ded175d?experience=power-bi)
## Spotify Dashboard
  - overview page
    ![spotify overview](https://github.com/Shahna-k25/Spotify-Analysis/blob/main/spotify%20overview.png)
- Listening Patterns
   ![spotify listening](https://github.com/Shahna-k25/Spotify-Analysis/blob/main/spotify%20listening.png)
## Tools Used
## Analysis Requirements
- Albums
    - Total Albums Played Over Time – Track monthly and yearly album-listening trends.
    - Number of Albums Listened by Year – View annual listening volume.
    - Top 5 Albums – Identify the most played albums by frequency.
    - Latest Year vs Previous Year – Compare album plays, including
                LY vs PY trend,
                YOY growth
- Artists
     - Total Artists Played Over Time : Track how artist listening trends evolve across months and years.
     - Number Of Artists  Listened By Year : Identify annual listening habits and artist diversity.
     - Top 5 Artists :  Identify the most played artists based  on listening frequency.
     -  Latest Year vs Previous Year –Compare artists plays, including
                LY vs PY trend,
                YOY growth
- Tracks
     - Total Tracks Played Over Time :  Monitor how Track listening trends change across months and years.
     - Number Of Tracks Listened By Year : Identify annual listening habits and track diversity.
     - Top 5 Tracks:  Identify the most played tracks based  on listening frequency.
     -  Latest Year vs Previous Year –Compare tracks plays, including
                LY vs PY trend,
                YOY growth
      
## Project Steps
- Requirement Gathering / Business Requirements – Defined KPIs and visuals.
- Data Connection – Imported personal Spotify streaming history CSV into Power BI
- Data Cleaning & Quality Check – Removed duplicates, standardized dates/time zones.
- Data Modeling – Built star schema with fact tables for plays and dimensions for artist, album, track, date.
- DAX Calculations – Created measures for YOY growth, LY vs PY comparisons.
- Dashboard Creation – Designed interactive visuals with slicers for year, artist, album, track.
- Insights Generation – Interpreted trends and surfaced listening patterns.
## Insights Highlights
- Total Plays Trend – Clear growth or drop patterns across years.
- Top Artists/Albums/Tracks – Immediate view of favorites.
- Weekday vs Weekend Listening – Understand when you listen most.
- Year-over-Year Change – Quick comparison of latest vs previous year.
## Tech Stack
- Power BI – Data modeling, DAX, dashboard visualization
- Excel / CSV  – Source data from Spotify export
- DAX – Measures for growth, comparisons, and aggregations
## Conclusion
This project turns raw Spotify export files into an easy-to-navigate, insight-rich Power BI dashboard.
It reveals your top artists, albums, and tracks while exposing listening habits such as weekday vs. weekend preferences and annual growth trends.
The result is a clear, data-driven view of evolving music tastes—something a simple CSV could never show on its own.
