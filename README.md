# Kuro's Notebook for the Competition - Everyone Can Learn Data Scholarship

Welcome to my project repository for the "Everyone Can Learn Data Scholarship" competition on DataCamp! This project explores two captivating datasets, empowering you to learn data analysis with Python and SQL.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Analysis Details](#analysis-details)
4. [Getting Started](#getting-started)
5. [Acknowledgements](#acknowledgements)

## Project Overview

This project is divided into two main parts:

### Part 1: Dinosaur Data Analysis (Python)
- **Objective:** Analyze dinosaur fossil records to uncover interesting insights and advise a museum on data quality.
- **Key Analyses:**
  - Identification and visualization of different dinosaur names, types, and occurrences.
  - Investigation of the relationship between dinosaur size and age.
  - Creation of compelling visualizations to present findings.
  - Development of an interactive map to display fossil discovery locations.

### Part 2: Movie Data Analysis (SQL)
- **Objective:** Analyze movie data to identify trends in successful films released before Titanic (1997).
- **Key Analyses:**
  - Ranking of top-grossing films from the era.
  - Analysis of movie runtime, languages, and countries of production.
  - Examination of the relationship between budget and box office revenue.

## Dataset Description

### Dinosaur Dataset
| Column Name   | Description                                                              |
|---------------|--------------------------------------------------------------------------|
| occurence_no  | The original occurrence number from the Paleobiology Database.           |
| name          | The accepted name of the dinosaur (genus name, footprint/egg fossil).    |
| diet          | The main diet (omnivorous, carnivorous, herbivorous).                    |
| type          | The dinosaur type (e.g., small theropod, large theropod, sauropod).      |
| length_m      | The maximum length from head to tail, in meters.                         |
| max_ma        | The age in which the first fossil records were found, in million years.  |
| min_ma        | The age in which the last fossil records were found, in million years.   |
| region        | The current region where the fossil record was found.                    |
| lng           | The longitude where the fossil record was found.                         |
| lat           | The latitude where the fossil record was found.                          |
| class         | The taxonomical class of the dinosaur (Saurischia or Ornithischia).      |
| family        | The taxonomical family of the dinosaur (if known).                       |

### Movie Dataset
| Column Name   | Description                                                              |
|---------------|--------------------------------------------------------------------------|
| id            | Unique movie identifier.                                                 |
| title         | The title of the movie.                                                  |
| release_year  | The year the movie was released to the public.                           |
| country       | The country in which the movie was released.                             |
| duration      | The runtime of the movie, in minutes.                                    |
| language      | The original language the movie was produced in.                         |
| certification | The rating given based on their suitability for audiences.               |
| gross         | The revenue the movie generated at the box office, in USD.               |
| budget        | The available budget for producing the movie, in USD.                    |

## Analysis Details

### Dinosaur Data Analysis (Python)
1. **Different Dinosaur Names:** 
   - Counted the unique dinosaur names in the dataset.
2. **Largest Dinosaur:** 
   - Identified the largest dinosaur and handled missing data.
3. **Dinosaur Type Occurrences:**
   - Visualized the number of dinosaurs per type.
4. **Dinosaur Size Over Time:**
   - Illustrated the relationship between dinosaur length and their age.
5. **Interactive Map:**
   - Created a map showing fossil discovery locations.

### Movie Data Analysis (SQL)
1. **Number of Movies:**
   - Counted the total movies in the dataset.
2. **Missing Data in Gross and Budget:**
   - Analyzed the missing data and provided recommendations.
3. **Different Certifications:**
   - Counted the different movie certifications/ratings.
4. **Top Five Countries:**
   - Identified the top five countries in terms of movie production.
5. **Average Duration of English vs. French Movies:**
   - Compared the average duration of movies based on language.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- SQL database setup (e.g., SQLite, PostgreSQL)
- Required Python libraries: pandas, numpy, matplotlib, seaborn, folium

## Acknowledgements
- DataCamp for providing the opportunity and resources for this project.