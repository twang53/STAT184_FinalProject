# STAT184_FinalProject
You can find the Final Project Report [HERE](file:///C:/Users/GuaiGuai/Documents/R/STAT184_FinalProject/Final%20Project.nb.html)

This is my final project for STAT 184. It requires multiple steps, starting with Preliminary EDA and ending with a report and presentation.

## Preliminary EDA
Based on the given instructions and rubric, below are some things I kept in mind while going through this phase of my project.

### Guiding Question (research question):
Have a single guiding/research question that will drive my analysis. It should be phrase as a question that I can try to investigate.

### Become acquainted with my data sources:
- where did it come from?
- who collected/maintains them?
- when & why were they originally collected?
- what does a case represent in each data source, & how many total cases are available?
- what are some of the variables that I plan to use?
**NOTE:** The R Notebook will contain R code chunks and output, as well as narrative for the questions above.

### Explore intuition related to the research question
- create informative plots & summary statistics
- describe preliminary observations & intuition about the research question

### Data Sources (at least two)

**Primary data:** Main data source that includes at least hundreds (preferably many thousands) of cases as well as many variables, including a mixture of both categorical & quantitative variables. This is not loaded from an R package.

**Other data sources:** This can be from an R package or somewhere else.


## Final Report
The final project analysis should be an HTML produced by an R Notebook with embedded Rmd. This can be submitted by itself (with the data source) OR via a URL to a github.io wepage for the project repository OR via a URL to a public GitHub Repository.   
The report is self contained, so the entire analysis should be able to be rerun by someone else without any errors (therefore includes access to the source ddata).   
The accompaning **Final Project Check Sheet** will also be turned in (it is contained in the same repository).

### Below are some descriptions taken from the rubric for reference:

#### Data Access
(1) Analysis includes at least two different data sources.
(2) Primary data source may NOT be loaded from an R package--though supporting data may.
(3) Access to all data sources is contained within the analysis.
(4) Imported data is inspected at beginning of analysis using one or more R functions: e.g., str, glimpse, head, tail, names, nrow, etc

#### Data Wrangling
Students need not use every function and method introduced in STAT 184, but clear demonstration of proficiency should include proper use of 5 out of the following 8 topics from class:

- general data wrangling using various data verbs like filter, mutate, summarise, arrange, group_by, etc.
- joins for multiple data tables.
- spread & gather--or similar--to stack/unstack variables
- regular expressions
- reduction and/or transformation functions like mean, sum, max, min, n(), rank, pmin, etc.
- user-defined functions
- loops and control flow
- exploratory machine learning

#### Data Visualization
Students need not use every function and method introduced in STAT 184, but clear demonstration of proficiency should include a range of useful of data visualizations that are (*1*) relevant to stated research question for the analysis, (*2*) are neat with professional appearance including titles, axis labels, guides, etc (*3*) include at least one effective display of many--at least 3--variables, and (*4*) include 3 of the following 5 visualization techniques learned in STAT 184:

- use of multiple geoms such as points, density, lines, segments, boxplots, bar charts, histograms, etc
- use of multiple aesthetics--not necessarily all in the same graph--such as color, size, shape, x/y position, facets, etc
- layered graphics such as points and accompanying smoother, points and accompanying boxplots, overlaid density distributions, etc
- leaflet maps
- decision tree and/or dendogram displaying machine learning model results

#### Code Quality
Code formatting is consistent with Style Guide Appendix of DataComputing eBook. Specifically, all code chunks demonstrate proficiency with:   

(1) meaningful object names
(2) proper use of white space especially with respect to infix operators, chain operators, commas, brackets/parens, etc
(3) use of `<-` assignment operator throughout
(4) use of meaningful comments

#### Narrative Quality
The narrative text--sentences and paragraphs:   

(1) clearly states one guiding question or research question for your investigation
(2) explains why this topic is important and/or interesting to investigate
(3) clearly describes one significant technical challenge encountered during the investigation and how you did or did not overcome it
(4) explains one or more significant findings or conclusions of your investigation that is clearly related to the guiding/research question
(5) is completely free of errors in spelling and grammar