

# Austin Animal Center Needs Analysis

**Author**: [Mohammed Siddiqui](mailto:saifword@live.com)

## Overview

This project analyzes data regarding box office returns and genres in order to make a recommendation as to which types of movies tend to do best at the box office.  

## Business Problem

Microsoft would be a new player in the movie making industry.  In order to best prepare for our entry, it is necessary to investigate market trends in order to plot the right trajectory.  Our primary objective, like most businesses is to garner the greatest return for the money invested.

## Data

There are two sources of data we will be working with. The first is The Numbers which provides us with the budgets as well as the domestic and worldwide grosses for various films.
    tn.movie_budgets.csv

The second source is IMDB which will provide basic information about the movies as well as ratings based on user votes.
    title.basics.csv
    title.ratings.csv

## Methods

For the purposes outlined above, we will use descriptive analysis in order to understand how the following factors contribute to the return on investment.  Budget, genre and release month.

## Results

As budgets increase, it appears there is an increase in returns.



The genres of Animation, Science Fiction and Comedy movies show the highest rates of return.  The Crime genre appears to be particularly weak in this regard.



Movies released in June, July, November and December tend to me most successful.


## Conclusions

Based on the above analysis, we can make the following recommendations:

- **Allow for higher budgets.** 
There does appear to be a positive relationship between budget and profitability.  As such, higher budgets would make sense for our company.
- **Prioritize the Science Fiction and Comedy genres.** 
Given the reduced activity during this period, AAC should consider ways to temporarily reduce costs by changing space utilization or staffing.
- **Aim to release our movies in June, July, November or December.**
These months have the highest rates of return, particularly July which sees the highest returns. 

### Next Steps

Further analyses in the following areas could help us understand the industry even better:

- **Analyze performance within specific budget ranges.**
While overall data is quite helpful, there might be patterns that are specific to low budget, mid budget or high budget films.
- **Explore genre patterns by season.**
Once we know which movie we want to make, it would be very helpful to know when in the year that particular genre tends to do best at the box office.
- **Account for revenues that could be generated from home viewers.**
The data we used in the above analysis is limited only to box office performance.  With the advent of streaming services as well as modern delivery systems for video rentals and sales, home viewing is of particular interest in understanding avenues for reveneue.

## For More Information

See the full analysis in the [Jupyter Notebook](./student.ipynb) or review this [presentation](./movie_studio_pres.pdf).

For additional info, I can be reached at  at [saifword@live.com](mailto:saifword@live.com)


## Repository Structure

```
├── data
├── images
├── README.md
├── movie_studio_pres.pdf
└── student.ipynb
```