# Hypothesis Testing Project 

In this project, we demonstrate the essential skills involved in hypothesis testing. 
We aim to answer 10 hypothesis questions and also provide additional statistical analysis relevant for building recommendation logic. 
To do so, we will use a real dataset that stems from a replication attempt of published research [(Wallisch & Whritner, 2017)](https://github.com/NBeibarys/Project-Hypothesis-Testing-of-MovieRatings-Using-Python/blob/main/project_guidelines/Wallisch%20%26%20Whritner%202017%20Movies%20-%20Copy.pdf).

To answer hypothesis testing questions and to cut down false positives, we set the per-test significance level 𝛼 to 0.005 (as per Benjamin et al., 2018).

## Questions: 
1) Are movies that are more popular (operationalized as having more ratings) rated higher than movies that are less popular? 
2) Are movies that are newer rated differently than movies that are older?
3) Is enjoyment of ‘Shrek (2001)’ gendered, i.e. do male and female viewers rate it differently? 
4) What proportion of movies are rated differently by male and female viewers? 
5) Do people who are only children enjoy ‘The Lion King (1994)’ more than people with siblings? 
6) What proportion of movies exhibit an “only child effect”, i.e. are rated differently by viewers with siblings vs. those without? 
7) Do people who like to watch movies socially enjoy ‘The Wolf of Wall Street (2013)’ more than those who prefer to watch them alone? 
8) What proportion of movies exhibit such a “social watching” effect? 
9) Is the ratings distribution of ‘Home Alone (1990)’ different from that of ‘Finding Nemo (2003)’? 
10) There are ratings on movies from several franchises ([‘Star Wars’, ‘Harry Potter’, ‘The Matrix’, ‘Indiana Jones’, ‘Jurassic Park’, ‘Pirates of the Caribbean’, ‘Toy Story’, ‘Batman’]) in this dataset. How many of these are of inconsistent quality, as experienced by viewers? 

## Project Structure: 
- `analyses` - Jupyter notebook with code and analysis done.
- `data` - main dataset and additional data used for analysis.
- `project_guidelines` - project guidelines and scientific papers used for analysis.
- `src` - additional functions used during the analysis.
  
## Key Insights (in-progress): 
- Identified statistically significant gender-based differences in median ratings for 50 of 400 movies (12.5%) using the Mann-Whitney U test, revealing audience preference patterns that inform targeted advertising and audience segmentation.

## Tools, Technologies, and Statistics:
- **Python**
- **Jupyter Notebook**
- **Non-parametric testing** (Mann-Whitney U, Kruskal-Wallis, Kolmogorov-Smirnov tests)
- **EFfect size analysis** [(Cliff's delta)](https://github.com/NBeibarys/Project-Hypothesis-Testing-of-MovieRatings-Using-Python/blob/main/project_guidelines/Using%20Cliff%E2%80%99s%20Delta%20as%20a%20Non-Parametric%20Effect%20Size%20Measure.pdf)
  
## Project Members
1. Joseph Tadros
2. Beibarys Nyussupov
3. Luke Ducker
