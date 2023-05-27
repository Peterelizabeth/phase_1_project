  
 
 
 # PHASE 1 PROJECT

## Predictive Exploratory Analysis: Case Study Microsoft Company

### Business Problem

Microsoft sees many big companies creating original video content and want to establish their own movie studio to compete within the digital content market.

To assist Microsoft in solving this problem, I will consider:

a. How many movies are being made of each genre?

b. What genres are the most successful, in terms of gross earnings?

c. Of the top grossing films, which genres were most successful (had the highest gross earnings)?

Answering these questions would help Microsoft develop a better understanding and decide the kind of movies to create in order to match its competitors.

### Date Understanding

The data for this analysis has come from:

a. IMDb (average ratings, title, year, genres)

b. Box Office Mojo (movie title, total earnings, movie title)

The target variables for this analysis are release year, total earnings, genres, and audience ratings. These variables are all important and necessary to address Microsoft’s business problem. Audience ratings, gross earnings, and release year are numeric variables (though gross earnings is continuous) and genres are categorical.

The data used in this analysis has been compiled from two platforms and includes all movies these platforms monitor. Since we are providing Microsoft with recommendations for success, we can safely assume these platforms accurately account for the movies of interest.

As we consider this data however, we should note that the data includes movies from 2014 to 2019. This is noteworthy because the data does not include the most recent three years of movie-making; since movie-watching trends can shift dramatically year to year, the conclusions and recommendations presented here may change based on more recent movies.

### Data Preparation

To prepare the data for analysis, I needed to combine three individual csv files into one master file. Then I dropped the irrelevant rows with NaN values. I made this decision because movies with missing any data from these sources would not be mainstream popular nor would have gross earnings of significance and therefore could be dropped without worrying about significantly altering the analysis. For movies with multiple genres, I split each movie to account for each genre individually to make the analysis of genre more precise.

For the IMDb files, I did drop the ‘original_title’, ‘runtime_minutes’, and ‘numvotes’ columns as they are not relevant or pertinent to the business questions being addressed. The data for total earnings was also modified by dividing the value by 1mil. This would make the value more readable since the total earnings for the movies I was analyzing are obviously more than just 1 million. 

The final data was prepared by selecting movies with an average rating of 7.5 or greater and with total gross above 27.9 million. These parameters represent the top 25% of movies based on rating and total earning. 

### Results

The stated business problem presented by Microsoft is establishing their own movie studio to compete within the movie market, and needing to know what kind of movies will be the most successful.

This analysis solves the stated business problem by determining the most successful kind of movies - in audience rating and total gross earnings from 2014-2019. In utilizing two large datasets from industry-standard giants of IMDb and Box Office Mojo, the data is comprehensive and trustworthy.

This analysis of movies from 2014-2019 shows the following:

a. All movies had almost the same level of rating, but music movies had the highest rating.

b. Adventure, action and drama  are the three most successful movies in the industry in terms of earnings.

c. Documentary, drama and comedy are the most common genres over the five years period.

d. Drama movies had the highest rate of production.

### Recommendations and Conclusion

This analysis leads to three recommendations of what movies to produce for Microsoft’s new movie studo:

a. For successful, sustained gross earnings over time, the company should produce Adventure, action and drama movies. These three genres have demonstrated consistent success over five years in amassing the most amount of gross earnings.

b. Further, the most common in the market over the five years period are drama, documentary and comedy movies for immediate success of gross earnings.

c. All movies had almost the same average ratings. Thus, the company should concentrate more on producing adventure, action, drama, documentary and comedy movies to successfuly compete in the market.


### Further Insights

a. Analyze more recent data from 2020-2023. this would provide more current data and incorporate the changes in viewing practices as a result of Covid-19 pandemic. More people watched movies from home throughout the pandemic and movie studios did direct-to-stream releases. Pulling data from streaming services on number of streams will be highly informative in terms of what people have been watching.

b. Analyze streaming data. Microsoft should compare ratings and earnings of traditional theatre-released movies vs. ratings and number of streams of released-to-streaming platforms. This could help determine the success of traditional theatre-released movies over streamed movies.

c. Analyze demographics of movie-makers and movie-watchers. the company become the home for diverse movies based on movie-makers and movie-watchers. It could succeed by creating films for marginalized and underrepresented populations within the film industry - women, people of color, women of color, LGBTQIA people, multilingual films.



