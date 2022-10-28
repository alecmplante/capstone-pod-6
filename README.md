# Computer Vision Film Proposal: Pod 8

### Summary

Our team was tasked to evaluate trends in the film indistry to identify actionable recommendations to our client, **Computing Vision**. We used datasets from [Box Office Mojo](https://www.boxofficemojo.com/), [IMDB](https://www.imdb.com/), [Rotten Tomatoes](https://www.rottentomatoes.com/), [The Movie DB](https://www.themoviedb.org/), and [The Numbers](https://www.the-numbers.com/) to determine these recommendations. After reviewing metrics such as genres, timing of releases, critic reviews, budgets, and income of different movies, we identified the following recommendations:
- Focus on Release Month
    - Release high budget films in the summer or winter
    - Release lower budget films in "dump months"
- Do not focus on Critical Approval
    - Critic reviews have little to no correlation with income on a film
    - Focus on audience reviews and quality of critics' reviews
- Explore the Science Fiction Fantasy Genre
    - Sci-Fi Fantasy movies bring a significantly higher profit than the average film
    - In this case, the higher cost of production is worht the resulting income

### Data Science Steps

**Data Cleaning**
    The first step of data science is cleaning the data so that it is in a usable format. To do this, we deleted duplicate rows, changed strings to number types when necessary, changed dates to the date time type, and conducted feature engineering to change genres into a usable format.
    
**Data Exploration**
    In the data exploration step, we came up with business questions and hypotheses to guide our exploration. For example, we hypothesized that there might be a correlation between release month and profit. In this case, we did feature engineering to create an (ROI) column and then made several visualizations to see the relationship. Then, we conducted statistical tests, including t tests, z tests, and ANOVA tests to further prove our hypotheses.

**Statistical Analysis**
    As we explored the data and found points of interest, we conducted statistical tests, including t tests, z tests, and ANOVA tests to further prove our hypotheses.

**Visualization**
    Once we felt confident that in our business recommendations, we produced final visualizations for our presentation. These were primarily produced using the Seaborn library.

### Packages Used

| Package | Version |
| ----------- | ----------- |
| Pandas | 1.1.3 |
| NumPy | 1.18.5 |
| SQLite3 | 3.33.0 |
| Matplotlib | 3.3.1 |
| Seaborn | 0.11.0 |
| SciPy | 1.5.0 |
| StatsModels | 0.12.0 |
| NLTK | 3.5 |

### Relevent Links

**Data Set Sources**
- [Box Office Mojo](https://www.boxofficemojo.com/)
- [IMDB](https://www.imdb.com/)
- [Rotten Tomatoes](https://www.rottentomatoes.com/)
- [The Movie DB](https://www.themoviedb.org/)
- [The Numbers](https://www.the-numbers.com/)

[**Presentation**](CapstonePresentation.pdf)


### Navigating the Repository

- The main file that shows all of our exploration and analysis is [index.ipynb](index.ipynb)
- The cleanedData contains the cleaned versions of the data sets after the data cleaning step in our process while data contains the original versions and zippedData contains the zipped versions of the data files