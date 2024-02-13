# Netflix-Business-Case-Study
## Data Cleaning & Data Tidying

Steps: 

a) Pre-processing involves unnesting of the data in columns like Actor, Director, Country.

b) Remove the NaN/null values
1. Identification of null value: isnull().
2. Replace numerical column missing value with mean for that column.
3. Replace categorical column missing value with mode/'unknown' & numerical column missing values with mean

## EDA: 

1. Non-Graphical Analysis: Value counts and unique attributes

2. Visual Analysis - Univariate, Bivariate after pre-processing of the data

    2.1 For continuous variable(s): Distplot, countplot, histogram for univariate analysis

    2.2 For categorical variable(s): Boxplot

    2.3 For correlation: Heatmaps, Pairplots

## Business Insights 
Explore the data, answer the following:

Start by exploring a few questions: 

1. What type of content is available in different countries?
2. How has the number of movies released per year changed over the last 20-30 years?
3. Comparison of tv shows vs. movies.
4. What is the best time to launch a TV show?
5. Analysis of actors/directors of different types of shows/movies.
6. Does Netflix has more focus on TV Shows than movies in recent years
7. Understanding what content is available in different countries

### Recommendations

1) The most popular Genres across the countries and in both TV Shows and Movies are
Drama, Comedy and International TV Shows/Movies, so content aligning to that
is recommended.

2) Add TV Shows in July/August and Movies in last week of the year/first month of
the next year.

3) For USA audience 80-120 mins is the recommended length for movies and Kids TV Shows
are also popular along with the genres in first point, hence recommended.


4) The target audience in USA and India is recommended to be 14+ and above ratings while
for UK, its recommended to be completely Mature/R content .

5) Add movies for Indian Audience, it has been declining since 2018..

6) While creating content, take into consideration the popular actors/directors
for that country. Also take into account the director-actor combination which
is highly recommended.
