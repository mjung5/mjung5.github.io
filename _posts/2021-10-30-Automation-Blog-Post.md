Min-Jung Jung
10/29/2021

The [project 2](https://mjung5.github.io/online-news-prediction/)
[(github repo)](https://github.com/mjung5/online-news-prediction) was a
group project working with a partner to create models to predict the
number of shares of articles published in Mashable in a period of two
years and to automate Markdown reports using 6 different channel
variables.

Beginning with manipulating data, we performed an Exploratory Data
Analysis on several interesting variables, like the number of images and
videos, and created various graphs and summary statistics. Next, we fit
two linear regression models and two ensemble tree-based models (a
random forest models and a boosted tree model), and then we compared the
RMSE scores of each model fit and found the best model with the lowest
RMSE score.

What would you do differently?

Deciding on the variables for the EDA was very challenging because many
variables were unknown. Therefore, David and I decided on starting the
EDA with the variables that are familiar, then adding more later. As we
read more articles using [Online News Popularity Data
set](https://archive.ics.uci.edu/ml/datasets/online+news+popularity), we
learned more about some variables, like positive and negative polarity,
and added those variables into our EDA. In the end, we had to change the
codes so many times. In the future, I would pick a set of variables and
stick with the variables for the EDA to save time.

What was the most difficult part for you?

I fit the random forest model and struggled so much running the code
chunk because of the running time. It took me almost 2-3 hours to
render. However, I found out that I was not the only one to struggle
with this, and I was able to get some suggestions and advice through the
discussion board, the office hours, and the slack channel. Eventually, I
was able to use chunk option catch=TRUE, and was able to reduce time
after rendering the first time.

What are your big take-aways from this project?

I am so glad I was able to practice how to set up automation and produce
automated markdown reports. Thankfully, David helped me a lot on
understanding the process of setting up the automation, and we shared
lots of ideas. I am so excited about using this method for different
data analyses. Also, working with a partner using github was
surprisingly pleasant. We communicated more to avoid merge conflicts and
saved more time not dealing with emailing back and forth with revised
files.

Here are the links to [github
pages](https://mjung5.github.io/online-news-prediction/) and [github
repo](https://github.com/mjung5/online-news-prediction).
