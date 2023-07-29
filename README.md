# Final Project Proposal

Please complete your proposal following the outline below.

## Project title

Determining Optimal Movie Criteria

### Authors

- Dhruv Jagannath (dhruvj20@uw.edu)
- Vy Nguyen (nvy24@uw.edu)
- Pagna Keo (pagnakeo@uw.edu)
- Hao Zhu (zh1117@uw.edu)

### Date

Summer 2023
## Abstract

Our main question is, "How do various factors impact the box office performance of movies?".

The answer to this question will show the element that has the biggest impact on a movie's popularity or revenue as well as audience preferences. 

We will first examine the movie dataset to help us answer the question, after which we will make observations of various variables and plot the correlation between them to illustrate how they are related. 

We are worried about some data inconsistencies because they might cause results to be incorrect. To prevent this issue, we will attempt to clean/wrangle the dataset and make sure the data is organized and tidy so that the analysis can be set up more quickly.

## Keywords

Movies: 
- Distribution
- Genre
- Run Time
- Sales
- Dates
## Proposal

1. Introduction  

- Does the run time and genre affect the number of sales?

- Which distributor produces the highest number of films in the top 1000 movies?

- Does releasing a movie under various genres have an effect on the box office performance?

- Between which years did certain distributors peak in terms of sales and movies made?

- Has the amount of movie releases across the months of the year changed over the duration of this dataset?

- How does the generic tag offered by distributors impact the Movie Box office performance?

This research project aims to analyze the top 1000 highest-grossing movies, investigating the relationships between distributor, runtime, genre, and tags with sales from domestic to international. 

The research questions revolve around whether the runtime and genre have an impact on sales, which distributor produces the highest number of films in the top 1000, and whether releasing movies under various genres affects box office performance. 

Addressing these research questions is motivated by the desire to gain valuable insights into the intricate dynamics of the film industry. Understanding the potential influence of runtime and genre on the number of sales can offer invaluable information to filmmakers and movie studios while gaining valuable information about viewers and measuring elasticity. 

This knowledge can help them better comprehend audience preferences, refine marketing strategies, and optimize film production to cater to viewers’ tastes effectively.  By answering these questions, valuable insights can be gained into audience preferences, industry trends, and the strategies that lead to box office success. 

The findings will benefit filmmakers, distributors, and other stakeholders in the film industry, providing them with data-driven guidance to create more engaging and commercially successful films in the future. 

This helps shed light on the major distributors in the film industry and uncover their success in the film industry while still exploring the effect of releasing movies under multiple genres on box office performance can provide insights into audience responsiveness to genre-blending and diverse storytelling. This knowledge can foster new creation, and storytelling, and enhance the viewer experience.

2. Related Work  

The movie theater industry in North America and beyond has been a significant aspect of the entertainment landscape for decades. In our project, we would like to focus on the industry's success from the box office revenues aspect, which are influenced by factors such as film releases, audience preferences, and overall economic conditions. This topic explores the dynamics of movie theater circuits and their impact on the North American box office performance.

According to Statista, North America has seen steady growth in the number of movie theater circuits and screens. From the 1990s till now, there have been several major players dominating the market, including AMC Entertainment, Cineworld Group, and Cinemark Holdings. These circuits control a significant share of the total screens in North America, enabling them to influence film distribution and box office revenues.

The Numbers provides comprehensive market analysis for the movie industry, including box office performance and trends. The website offers valuable insights into box office numbers for individual movies, helping us to understand the financial success of films and their impact on theater circuits, which can also play as a comprehensive counterpart with our database to provide more insight on our analysis.

Furthermore, popular press articles, such as the CNBC piece from July 2023, highlighted challenges and opportunities faced by the current movie theater industry, which provides more insights on our research purpose. This article discusses the 2023 movie box office performance, emphasizing the need for a strong second half of the year after an inconsistent start. This exemplifies the industry's sensitivity to various factors that can significantly impact revenue streams.

In conclusion, the movie theater circuits' landscape and box office performance are influenced by several factors, including the number of screens, film releases, and audience behavior, especially focusing on the North American market. Studying this topic provides valuable insights into the economics of the entertainment industry and how it evolves in response to changing market conditions and audience preferences.

Sources: 
Statista. "North American movie theater circuits by number of screens." https://www.statista.com/statistics/188565/north-american-movie-theater-circuits-by-number-of-screens/ 

The Numbers. "Comprehensive market analysis for the movie industry." https://www.the-numbers.com/market/ 
CNBC. "2023 movie box office needs strong second half after inconsistent start." https://www.cnbc.com/2023/07/04/2023-movie-box-office-needs-strong-second-half-after-inconsistent-start.html 

(lack of access to the following article, would be helpful if we can have access to it)
https://journals.sagepub.com/doi/10.1177/0093650209356396 

3. The Dataset

> Where did you find the data? Please include a link to the data source  

We find this movie-related dataset from Kaggle:

Top 1000 Highest Grossing Movies

https://www.kaggle.com/datasets/sanjeetsinghnaik/top-1000-highest-grossing-movies 

The data was updated 2 years ago by Sanjeet Singh Naik. This data was collected from various websites and combined for use in a variety of data operations. The information came from numerous websites, including imdb, rotten tomatoes, and others. This data set includes 918 observations (rows) and 11 features (columns). 

> Why was the data collected?  

The data is gathered for the public's use, particularly for those who are interested in movies because it contains a lot of observations (movies) and information about genre, duration, and sales value. 

Producers and directors can use it to research audience preferences and current movie trends. Additionally, by collecting information on domestic and foreign sales, this data is also made for business purposes by giving investors a more thorough picture of the movie's revenue.

>How many observations (rows) are in your data?

This data set includes 918 observations (rows).

> How many features (columns) are in the data? 

This data set includes 11 features (columns).

> What, if any, ethical questions or questions of power do you need to consider when working with this data?  

1.  Is the dataset biased in any way that might favor a particular genre?

2.  Does the content of the movies reflect racism or sensitivity to a particular culture or minority group?

> What are possible limitations or problems with this data? 

Possible limitations and problems with this data is that there are some missing values in this data, which could potentially lead to biased results because the data does not fully represent the whole.  

Furthermore, the dataset only includes movies from the United States, so it cannot be used to analyze other countries or to examine diversity. 

4. Implications

> Assuming you answer your research questions, briefly describe the expected or possible implications for technologists, designers, and policymakers. (at least 150 words)

The expected implication is an optimized methodology for movie planning and production in terms of net income. One of our questions also uses historical data to compare how different movie distributors have performed monetarily over the years encompassed by the dataset. 

In terms of production, we want to address the timing of movie production and then compare that with income to predict what months are the best to produce films, if so at all. We also want to see the relevance of generic tags; does the presence of fewer or more tags allow producers to perform better monetarily? 

The most basic implication is how film producers can fit their moves to certain runtimes or genres, and maybe if specific runtimes are better for different genres. All in all, if a film director wants to produce a movie, what sorted guidelines can they follow based on genre, runtime, distributor, and timing to get optimal income? Do these criteria differ based on domestic and international markets?

5. Limitations & Challenges
>What challenges or limitations might you need to address with your project idea more broadly? Briefly discuss. 

The main limitation of this project is that the dataset we're using only consists of the top 1000 movies income-wise. 

This data doesn't account for any of the movies closer to the median or minimum of a dataset that would include all movies (a dataset with a much higher sample size) in terms of gross-income, so the set in general lacks breadth, which limits our ability to convey generalizable information about movies worldwide. 

Our dataset is also limited to income as the main categorization of movie response, but movie reviews are an important factor missing from the data, which could limit our ability to create the best possible criteria to produce a movie based on certain descriptors. 

Lastly, there are some NA values under different categories of the dataset, which omits some of the movies depending on the target of our analysis, thus reducing an already-skewed sample size and further constraining the breadth of our dataset.

Acknowledgements
> Is there anyone you would like to thank? A librarian who helped you with your research? A Teaching Assistant? A friend who helped you find your data? Say thank you in this section.

Thank you to Phyllis for pointing out to Dhruv that creativity is possible with categorical variables and quality analysis can still be performed with them. 
