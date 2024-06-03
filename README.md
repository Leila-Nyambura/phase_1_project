## Box Office Success Analysis

### Overview

The project analysis goal is to provide insights to Microsoft for a new movie studio on what types of films are currently successful at the box office. I will analyze a movie dataset from The Movie Data Base website to identify key trends and patterns, ultimately providing actionable recommendations. Microsoft can use this analysis to decide on what type of film to create.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. I will explore what types of films are currently doing the best at the box office. I will then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create. Objectives:

- Identify genres that are performing well at the box office.
- Determine key attributes associated with successful films.
- Provide three actionable recommendations for the new movie studio.

## Data

The movie dataset is from [The Movie Data Base](https://www.themoviedb.org/) website and I used it to identify key trends and patterns, ultimately providing actionable recommendations.

## Methods

This project used Exploratory Data Analysis to provide insights to Microsoft as they intend to venture into box office movie production sector.

## Results
### - Distribution of Numerical Columns
The distribution of the 'popularity’ scores of movies in the dataset.
![image](https://github.com/Leila-Nyambura/phase_1_project/assets/164230963/61e22cb0-91f4-47da-8ea4-4342d8772a84)

The distribution of average vote ratings given to movies.
![image](https://github.com/Leila-Nyambura/phase_1_project/assets/164230963/d9eb1b55-7be6-4fcd-a6ed-63d62a5278fb)

The distribution of the number of votes received by movies.
![image](https://github.com/Leila-Nyambura/phase_1_project/assets/164230963/ca108257-bdb7-4f16-bcc6-610c8d98a516)

### - Correlation Analysis
A correlation heatmap to graphical representation how closely related the different variables are within the dataset.
- Darker colors represent stronger correlations.
- Lighter colors indicate weaker correlations.

![image](https://github.com/Leila-Nyambura/phase_1_project/assets/164230963/c50510e3-bda6-4eb3-9592-b2fe778b81fb)

The heatmap generated shows the correlation matrix for three numerical features: ‘popularity’, ‘vote_average’, and ‘vote_count’. Analyzing the specific correlations:
- ‘popularity’ and ‘vote_count’ have a high positive correlation of approximately 0.69 (indicated by a darker shade).
- Both ‘popularity’ and ‘vote_count’ have very low positive correlations with ‘vote_average’, as shown by their respective coefficients of 0.067 and 0.088 (represented by much lighter shades).

## Recommendation
This analysis leads to three recommendations for Microsoft's success during their venture into box office movie production:  

- <b>Focus on Action and Adventure Genres:</b> These genres are consistently popular and engaging. Creating movies that blend Action with Adventure, Science Fiction, and Fantasy is likely to attract a large audience.

- <b>Incorporate Elements of Science Fiction and Fantasy:</b> These genres, especially when combined with Action and Adventure, have high popularity and engagement. Sci-fi and fantasy elements can add an exciting and imaginative dimension to films.

- <b>Consider Documentaries and Serious Drama:</b> While not the most popular in terms of vote counts, documentaries and dramas are highly rated. Producing high-quality content in these genres can cater to a niche audience that values depth and factual storytelling.

## Next Steps
Box office movie production budgets were not reviewed in this analysis but further analyses on this will yield additional insights to further improve Microsoft's success factoring in production budget, domestic gross, and worldwide gross for optimal financial performance:

- <b>Conduct Market Research to Determine Optimal Budget Ranges</b>

<b>Analysis:</b> Examine the historical data on production budgets, domestic gross, and worldwide gross to identify the optimal budget range that maximizes profitability. This will help in understanding the sweet spot for investment where the return on investment (ROI) is highest.

<b>Action:</b> Perform a regression analysis or similar statistical method to find the correlation between production budgets and gross revenues. Use this information to set budget guidelines for different types of films (e.g., Action, Adventure, Sci-Fi).

<b>Impact:</b> By allocating the right amount of budget, the company can balance quality and expenditure, leading to higher gross revenues without overspending.
- <b>Invest in High-Grossing Genres and Market-Driven Content</b>

<b>Analysis:</b> Given the high popularity and vote counts of Action, Adventure, and Science Fiction genres, the company should prioritize these genres for their film slate. Additionally, incorporating elements of Fantasy can further enhance appeal.

<b>Action:</b> Develop a strategic plan to produce a slate of films primarily in the identified high-grossing genres. This should include securing rights to popular intellectual properties, hiring renowned directors and actors, and ensuring high production quality.

<b>Impact:</b> By focusing on genres with proven box office success, the company can increase its chances of hitting high domestic and worldwide gross figures, leading to higher overall profitability.
- <b>Optimize Marketing and Distribution Strategies</b>

<b>Analysis:</b> Successful box office performance often depends not just on the movie itself but also on how well it is marketed and distributed. Analyze past marketing campaigns and distribution strategies of top-grossing films to identify best practices.

<b>Action:</b> <b>1. Marketing:</b> Develop a comprehensive marketing plan that includes traditional advertising, digital marketing, social media campaigns, and strategic partnerships. Focus on building hype and anticipation through teasers, trailers, and exclusive content releases. <b>2. Distribution:</b> Plan for a wide release strategy, including international markets where specific genres (e.g., Sci-Fi, Action) tend to perform well. Consider partnerships with streaming platforms for post-theatrical releases to maximize revenue.

<b>Impact:</b> Effective marketing can significantly boost opening weekend revenues, while strategic distribution ensures that the film reaches the maximum audience, both domestically and internationally.
