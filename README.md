# Microsoft Movie Studios Recommendations

## Project Overview

This project analyzes movie data from movie aggregation websites to create proposals for a hypothetical new Microsoft Movie Studios. The analysis shows that movies which met a budget threshold or released during peak months typically yielded greater profits. Additionally, documentaries were the top-rated genre. Microsoft can leverage these three business insights for producing successful movies.

## Business Understanding

Our client is a hypothetical new Microsoft Movie Studios. The goal of our analysis is to provide suggestions to help Microsoft decide what kind of movies to produce. We conducted an analysis on movie data to construct three actionable insights that Microsoft can utilize to find success in their movie-making venture.

## Data Understanding and Analysis

Our data is stored in a folder named zippedData. The data is sourced from a variety of movie aggregation sites: IMDB, Box Office Mojo, Rotten Tomatoes, TheMovieDB, and The Numbers. 

Data gathered from IMDB included movie genres, average ratings, and the number of votes received. The data was joined to view all relevant data on one table. 

The data we analyzed from the other sources includes budgets, domestic/worldwide gross, and release date.

## Results

Using the tmdb data, we plotted the popularity score against month to see if any month had more popular movies overall.

December movies had the highest average popularity score with June's and July's as almost identical runner-ups.

Another aspect to consider for a movie's release month is the quantity of movies released during that month. This can provide some insight into how popular certain months are and how much competition a movie might have during its release.

Again, December stands out with the greatest number of movie releases. The other 6 months with the most releases are October, September, August, April, and March.

The following stacked bar chart takes our budget/gross dataset and plots the mean gross values grouped by month. A month with a greater mean/median movie gross could indicate more consumers are watching movies during that time.

Graphing the same data limited to movies released in the past 25 years revealed similar trends. We focused on the last 25 years to better reflect modern market trends and reduce the effect of inflation.

The similarity between the mean and median charts indicates that these measures are weighted heavily by releases from the past 25 years. May had the strongest performing movies, followed closely by June, July, and November. December lagged behind the front-runner months but still stood significantly above the remaining months.

We also graphed the median movie gross grouped by month. Using the median reduces the effect of super-performer movies such as "Avatar". This can give us a better look at how an "average" movie might perform in a given release window.

May was the most strongly affected by using the median instead of the mean. This indicates that May had some outlier movies with high gross. The median could be a better metric for a fledgling movie studio. 

Now that we've looked at trends in gross data, we added in budget as another variable for consideration. Return on investment (ROI) here was calculated as the difference between gross and budget, divided by the budget. This provided a ratio of movie profits versus movie costs. Similarly to the gross plots, the mean and median ROI for movies grouped by release month were plotted.

July stands out above the rest with a mean ROI of 5.07. The month with the second greatest mean ROI is May at 3.68. After plotting the median ROI of movies against their release month, we saw how ROI is greatly affected by overperformers.

June, July, November, and December also had high mean gross, a trend reflected by the median gross as well. Based on this analysis, we could say that movies releasing in these 4 months generally experienced the best gross performance. 

The greatest median ROI of movies based on month was 1.18, lower than any value of the mean ROIs. The difference between the means and medians reflects how uncertain the movie market is. Movies that excel can return great profits but are not the norm. Only three months had median ROIs that surpassed the break-even ratio of 1.0.  Here we see the best performing months match those highlighted in our median gross by month analysis. June, July, November, and December return as the best performers.

After our analysis of movies based on their release months, we concluded that there are clear months in which movies displayed better financial performance.


![]()

We wanted to analyze the relationship between worldwide gross and production budgets. The color separation distinguishes between newer and older movies, to reflect how return on investment trends changes between newer and older movies.

The first graph covers movies in our datasets released before 2005. The second graph covers movies in our datasets released after 2005. No trend is apparent in the pre-2005 graph, while the post-2005 graph displays an upward trend in return on investment.
In these graphs, a line indicates the 150 million dollar budget mark. Past this threshold, most movies have positive return on investment. 

![Newer Worldwide Gross Values](./visualizations
/new_worldwide.png)
![Older Worldwide Gross Values](./visualizations
/old_worldwide.png)

As a particular example, we looked at "The Social Network" as a dramatized documentary-style movie that Microsoft could use as a case-study. The bar chart below shows the wordlwide gross and budget for the film. 

![The Social Network Budget v Gross](./visualizations
/Tech_movies.png)

To visualize the highest rated films by genre, we plotted the movie counts for the 50 top rated movies to show that Documentary was the genre with the highest movie count. We also plotted the movie counts for the 50 lowest rated movies to show that Documentaries were not as common in the lowest rated movies.

![Highest Ratings Genre Graph](./visualizations
/highest_genre_graph.png)
![Lowest Ratings Genre Graph](./visualizations
/lowest_genre_graph.png)


## Conclusion

We developed three recommendations from our analysis for Microsoft Movie Studios:
- **Release films in peak months:** Microsoft Movie Studios should consider releasing movies in June, July, November, and December to optimize movie profits.
- **Allocate a budget of 150 to 200 million dollars:** Since movies with a budget over 150 million dollars displayed a greater return-on-investment, Microsoft Movie Studios should invest within the recommended budget range.
- **Focus on documentaries:** Our analysis found that the documentary genre has the most top rated movies. Microsoft Movie Studios should prioritize documentaries as a safe choice for movie genre.

## Next Steps

Here are other ideas to explore for future analysis:

- **Streaming Platforms vs Movie Theaters:** Streaming services are becoming increasingly popular. Further analysis can focus specifically on movies released through streaming services.
- **Investigate success of film adaptations:** Microsoft has many properties that could be adapted to movies. Analysis on adaptation success could help Microsoft leverage those properties.


