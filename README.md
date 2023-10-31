# Final-Project-Tableau

## Project Goals
The overarching objectives of this project are
* Learning how to turn data into visual insights using Tableau
* Learning how to communicate insights using the appropriate visualizations.

To achieve the above broad objectives, several datasets relating to real estate prices and
housing affordability in Canada were collected, explored, and visualized
to communicate relevant insights. The deliverables for this project includes
* A Tableau Workbook file containing several worksheets, dashboards, and a story
section located in Submissions/Workbook,
* A 10-slide PowerPoint file located in Submissions/Presentations, and
* A Jupyter notebook containing detailed procedural steps and observations
located in Submissions/Notebook.

## Process
The detailed steps undertaken to complete this project includes
* Collecting relevant Canadian-specific datasets with information about residential house prices,
office building prices, average weekly earnings, inflation measures in form
of Consumer Price Index (CPI) information, and housing construction starts.
* Exploring the datasets to provide initial insights and develop questions
and hypotheses for further visualization
* Providing appropriate visualizations in Tableau to communicate the insights
gleaned from the datasets

## Results
Option 1 project type was selected and questions relating to real estate
prices and affordability in Canada were explored and visualized. Detailed procedures about the
question generation, answers, and steps leading to the visualization can be found in 
the notebook located in Submissions/Notebook. An abridged, and distilled, subset of the questions explored is
provided below.

### 1. Should you wait to buy a house?
Since trend information are better captured with line charts, a line chart
showing data about residential house prices, office real estate prices, and the overall housing
index was used in this visualization. To aid clarity, all data were normalized using
2005 as the reference year. The percent change since the selected reference year was then
used to give the datasets a common base. Results show that real estate prices have
been consistently trending upwards, with residential house prices in particular accelerating in recent years.

### 2. Are house price differences between selected cities increasing?
Both a heatmap and a diverging bar chart were used in visualizing an answer to this question. From the results,
it was gleaned that, interestingly, the price differences between the selected cities have been decreasing, as prices
in the cheaper cities catch up to the overall average.

### 3. Are house more affordable than in the past?
A line chart was used in visualizing an answer to this question. The result showed
that house prices have been growing faster than the rate of increase in salaries/wages. Hence,
house prices are increasingly becoming less affordable.

### 4. Do people stop building houses when the economy gets bad?
Annotations using reference bands/lines were used to highlight notable events, including recessions,
on the trend plot of housing construction starts. The results showed that recessions that affect
the broader economy lead to reduction in housing starts. Conversely, events
isolated to specific sectors, like the Dot com Bubble, are less impactful
on housing starts.

Details on more explored questions together with the associated Tableau visualizations
can be found in the deliverables under the Submissions folder.
## Challenges 
Overall, the project was undertaken relatively smoothly. The main challenges were
with the datasets and the time limitation. Of note, the provided weekly earnings
json file was unusable, and I had to re-source the file from the Open Data repository.

## Future Goals
With more time, it would be interesting to enrich the present dataset and get more
geographic granularity into the house prices across Canada.
