# Critique by Design: A Look at Housing and Renovation Costs


## Inspirational Visualization and Critique

The original data visualization that inspired this project comes from Angi's "Economy of Everything Home" Report. Each year, Angi interviews its customers about home improvements done that year to get a picture of the home renovation trends for that year. My husband and I have used home renovation sites extensively over the past year as we renovate our house, and I've even contributed to some of the answers found in the report. As I was reading the report, the visualization below caught my attention. It communicates a large amounts of data across states in a single visualization:

<img src="https://user-images.githubusercontent.com/79218366/140960534-88bdb79b-2d49-4058-8bf8-6eae88882c8f.png" style = "width:800px;"/>

Source: [Angi's Economy of Everything Report](https://www.angi.com/research/reports/market/) (2)

### Critiquing the Visualization:

Based on the visualization and the method of critique established by Stephen Few (1), I rated the visualization according to 7 metrics as shown below:

<img src="https://user-images.githubusercontent.com/79218366/140968961-ec538903-48ff-47f9-9235-8bfaf8a59b17.png" style = "width:800px;"/>

The things about the visualization I would keep is the use of size and color. The visualization allows you to make snap judgements about the states that are highlighted such as the highest home values come from DC, California, and Hawaii. Older homes are concentrated on the East coast which is easy to tell because of both the colors and the positioning on the graph.

A few things that didn't work well are the use of red and green (not condusive to the color blind), the repetition of variables (home age is represnted on the x-axis as well as color), and the inclusion of Washington D.C. in the data. Although it is a state, it is a concentrated, urban area that will naturally have a higher rental rate than states with rural and urban areas. Therefore, I don't think the visualization benefits from including it. 

One of the main things I would change is the placement of variables. By putting home age on the x-axis and home ownership rate on the y-axis, the reader will want to draw correlations between the two (for example, as home age increases, home ownership rate decreases). However, this is not a meaningful statistic or relationship for people looking to buy a home. Therefore, the main areas of the visualization to change is the placement of variables to make it more perceptible to the reader, cleaning up the labeling and aesthetics to allow the reader to more easily draw conclusions, and only including relevant data that people would need to know when looking to buy or renovate a home in a particular area to increase the completeness of the visualization. 

In terms of re-design, although I thought the bubble chart was effective at communicating multiple variables, I was curious to explore how other types of visualizations could communicate the data, particularly if some sort of map could be incorporated because the data is highly geographic in nature. 


## Sketches and Brainstorming

I chose to start with Figma for the sketches to try and capture multiple variables, colors, and techniques. To start, I did a bubble chart similar to the original visualization. Instead of home ownership rate, I incorporated the average cost per improvement project in order to target an audience looking to buy or renovate a home. I chose not to change the changes in bubble size corresponding to home value, and the color was changed to represent home ownership rate (to still include the information). The data from this and the second sketch comes from [House Method,](https://housemethod.com/home-warranty/median-home-age-us/) [iPropertyManagement, ](https://ipropertymanagement.com/research/homeownership-rate-by-state) [Experian, ](https://www.experian.com/blogs/ask-experian/research/median-home-values-by-state/) and [ProRemodeler](https://www.proremodeler.com/improvement-spending-state) (3, 4, 5, 6).

**State Level Bubble Wireframe**

<img src="https://user-images.githubusercontent.com/79218366/140959353-9ad08001-52c1-4121-adb9-e04f7d0909ab.png" style = "width:800px;"/>

The second sketch tries to take similar data and overlay it on a map of the United States. This particular sketch doesn't incorporate cost per improvement process, and just shows the three variables shown in the original visualization. 

**State Level Map Wireframe**

<img src="https://user-images.githubusercontent.com/79218366/140959430-00dd4f13-539c-4adc-bcc2-f7b770313f97.png" style = "width:800px;"/>

After soliciting some initial feedback from my husband, his first impression is that the audience is too much of a niche population (typically people looking at real estate data at a national level are transient populations or large real estate investors). Therefore, to narrow the population down to people trying to buy or renovate a house in the Pittsburgh area, I incorporated a third sketch. The data for this sketch comes from [Western Pennsylvania Regional Data Center](https://data.wprdc.org/dataset/city-of-pittsburgh-building-permit-summary) (7). For this sketch, I wanted to focus on building a relationship between the variables, so I show in the sketch the correlation between the 5-year % increase of home values versus the current median home value. 

**Local Pittsburgh Wireframe**

<img width="800" alt="IMG_4598" src="https://user-images.githubusercontent.com/79218366/140959500-d72ec72c-4015-4c66-9fce-3fffa5d601e8.png">


## Soliciting Feedback

I got feedback on the wireframes from my husband, my parents, and my friend (Kate, a veteran of TSWD). 

Here's what they had to say about the sketches ...

**State Level Bubble Wireframe**
* insert feedback here
* insert feedback here

**State Level Map Wireframe**
* insert feedback here
* insert feedback here

**Local Pittsburgh Wireframe**
* insert feedback here
* insert feedback here

This led to the following changes to my wireframes as I was building the final design:
* insert change here

## Final Visualizations

To start, I wanted to experiment with a way to summarize the data with a comparison to states' locations geographically. To reduce the amount of data on the graph and to prime the reader for the visualizations that follow, I opted to just show median housing prices around the country. This allows the reader to draw comparisons within and between regions before adding complexities such as home age and home improvement costs.

<div class="flourish-embed flourish-map" data-src="visualisation/7777152"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Below is the recreated visualization of the original. I opted to simplify the variables, and show more of the natural relationship between home age and average improvement project cost in that state.

<div class="flourish-embed flourish-scatter" data-src="visualisation/7774805"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Below is the visualization for the Pittsburgh area:

<div class="flourish-embed flourish-scatter" data-src="visualisation/7774462"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Future Applications / Work

Due to a substantial amount of time to pull and process data from multiple sources, I didn't get to incorporate a time aspect to any of the visualizations or data sets. However, I think this would be interesting and a peice of data about homes that potential buyers would find interesting. For example, 

*References:*

(1) Few, Stephen. "Data Visualization Effectiveness Profile." March 2017.

(2) "The Economy of Everything Home." *Angi*. 2021.

(3) Cusick, David. "The Median Age of Homes in the United States by Build Year." *House Method.* July 18, 2020. 

(4) "Homeownership Rate by State." *iPropertyManagement.* 

(5) Stolba, Stefan Lombo. "Median Home Values by State." *Experian.* November 18, 2019. 

(6) McClister, James. "Improvement Spending by State." *ProRemodeler.* July 2, 2019. 

(7) "City of Pittsburgh Permit Summary." *Western Pennsylvania Regional Data Center.* Sepetember 2021.
