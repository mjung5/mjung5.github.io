Min-Jung Jung
10/5/2021

## COVID19 API

I used the COVID19 API to complete [project
1](https://mjung5.github.io/covid-vignette-api/) ([github
repo](https://github.com/mjung5/covid-vignette-api)).

### Vignette project

I created several functions to contact the COVID19 API and generate data
for exploratory data analysis. Even though I was able to choose many
different countries to compare, I specifically chose the US for this
vignette and compared death cases to confirmed cases at the national
level, state level, and county level. At first, the results came to me
as mere numbers and graphs, but as I dealt with the information more, I
realized that the numbers mean a lot. Especially, when I looked at the
information on Wake County, It felt much more real to look at the data
and see that more than 120,000 people were found to be COVID19 positive,
and worst of all, over 800 people around me died from this disease. It
is not easy to wear masks everywhere we go and keep more distance from
each other. However, with the high number of deaths, I more strongly
realized that I have a responsibility to follow the guidelines and
should not think lightly about what I need to do to prevent the spread
of COVID.

#### what was the most difficult part of the logic and programming? What I do differently in approaching a similar project in the future?

In fact, I chose the COVID19 API because I was able to understand the
data better than the other APIs, but the data from the COVID19 API is
mostly numerical. Therefore, I had to create categorical variables to
complete the exploratory data analysis. Creating categorical variables
was surprisingly difficult for me because simply cutting the data and
making it as categorical variables didn’t give me much information. I
ended up creating risk categories based on the confirmed cases and death
rates.

However, the criteria I used are subjective, and I did not incorporate
the population numbers for each region when creating the criteria. For
example, California and Texas have larger populations than North
Carolina, so viewing cases by population size may reveal that they are
not as bad as the initial categories suggest. I know that I just cannot
simply make the risk categories only by confirmed case numbers. For this
project, my goal was to create categorical variables to explain the
existing data, but I would like to combine population data with the
COVID19 API in the future to make more accurate results.

I created many graphs and tables first before I understood what the
results of the graphs and tables truly meant. At the end, I had to
delete several tables and graphs that I spent a lot of time working on
because the results were not meaningful. In the future, I will focus on
analyzing the data and creating tables in a stepwise manner, such as
writing one or two tables first, interpreting the results, and then
moving on to making the next tables/graphs.
