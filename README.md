# Movie Cast & Crew Analytics

## About the Project

This project is about analyzing movie cast and crew data using Python.

I used the dataset to find information about actors, directors, characters, and the number of titles they were involved in. I also created some graphs to make the results easier to understand.

## What I Analyzed

- Total number of records
- Number of unique people
- Number of unique movie titles
- Actor and director records
- Top actors by number of titles
- Top directors by number of titles
- Most frequently appearing characters
- People who worked as both actors and directors
- Actors and directors with 10 or more titles

## Some Results

- Total records: **124,179**
- Unique people: **80,508**
- Unique titles: **8,861**
- Actor records: **115,793**
- Director records: **8,386**
- Actors: **93.25%**
- Directors: **6.75%**
- People who worked in both roles: **1,105**

The person with the highest number of records was **George 'Gabby' Hayes** with 49 records.

The director with the highest number of titles was **Joseph Kane** with 41 titles.

The most frequently appearing named character was **Henchman**, with 237 records.

## Visualizations

The project contains these graphs:

- Top 10 Actors
- Top 10 Directors
- Top 10 Characters
- Actor vs Director Distribution
- Actors vs Directors with 10+ Titles

The graphs are available in the `visualizations` folder.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code
- Git & GitHub

## Project Structure

```text
Movie_Cast_Crew_Analytics/
│
├── data/
│   └── movies.csv
│
├── notebooks/
│   └── Movie_Analytics.ipynb
│
├── visualizations/
│   ├── actor_vs_director.png
│   ├── actors_vs_directors_10plus.png
│   ├── top_10_actors.png
│   ├── top_10_characters.png
│   └── top_10_directors.png
│
├── README.md
└── requirements.txt