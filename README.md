[![Open the analysis paper](https://img.shields.io/badge/Open%20as-PDF-red.svg?logo=adobeacrobatreader)](https://github.com/NBeibarys/Project-Hypothesis-Testing-of-MovieRatings-Using-Python/blob/main/analyses/project_paper.pdf)
[![Open Notebook](https://img.shields.io/badge/Open-Jupyter-orange.svg?logo=jupyter)](https://github.com/NBeibarys/Project-Hypothesis-Testing-of-MovieRatings-Using-Python/blob/main/analyses/project_code.ipynb)

# Hypothesis Testing Project 
In this project, I demonstrate core skills of hypothesis testing using real-world data. I aim to answer 10 hypothesis questions about movie enjoyment patterns across different groups of viewers and to extend the analysis by evaluating additional statistical insights relevant to recommendation and audience segmentation. The dataset used is a replication attempt of published research [(Wallisch & Whritner, 2017)](https://github.com/NBeibarys/Project-Hypothesis-Testing-of-MovieRatings-Using-Python/blob/main/project_guidelines/Wallisch%20%26%20Whritner%202017%20Movies%20-%20Copy.pdf), in which participants rated a list of movies on an ordinal scale. Because the data is survey-based, observational, and strictly ordinal (0-4), non-parametric testing methods are used throughout the analysis.

To answer hypothesis-testing questions and reduce false positives, I set the per-test significance level 𝛼 to 0.005 (as per Benjamin et al., 2018).

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
- `analyses` - Jupyter notebook with code and analysis done, and project [paper](https://github.com/NBeibarys/Project-Hypothesis-Testing-of-MovieRatings-Using-Python/blob/main/analyses/project_paper.pdf).
- `data` - main dataset used for analysis. 
- `project_guidelines` - project guidelines and scientific papers used for analysis.
- `src` - additional functions used during the analysis.
  
## Tools, Technologies, and Statistics:
- **Python**
- **Jupyter Notebook**
- **Non-parametric testing** (Mann-Whitney U, Kruskal-Wallis, Kolmogorov-Smirnov tests)
- **Effect size analysis** [(Cliff's delta)](https://github.com/NBeibarys/Project-Hypothesis-Testing-of-MovieRatings-Using-Python/blob/main/project_guidelines/Using%20Cliff%E2%80%99s%20Delta%20as%20a%20Non-Parametric%20Effect%20Size%20Measure.pdf)

## How to Run
1. Clone the repository. 
2. Install dependencies with `pip install -r requirements.txt`
3. Open `analyses\project_code.ipynb`
4. Run all cells before Q1. This includes imports, helper functions, data loading, and preprocessing.
5. After step 4, each question is independent.
6. For any question QX, run all cells in that section starting from the cell that defines qX_df. Skipping that first cell breaks the rest of the section.

## Project Members
1. Beibarys Nyussupov
2. Joseph Tadros
3. Luke Ducker
