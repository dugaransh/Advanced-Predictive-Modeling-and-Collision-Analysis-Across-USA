# Advanced-Predictive-Modeling-and-Collision-Analysis-Across-USA
Through this project, we have aimed to answer the following three main questions:
1. Are there any geographic hotspots or any other patterns in collisions?
2. How do vehicle brands, their safety equipment, and their year of manufacturing affect collisions?
3. What is the best time of the year for US Government to do construction so that the collision occurring on a particular road is of least severity?

We have analyzed two datasets, the first dataset, titled <b>"Collisions"</b>, helped to understand geographic hotspots, vehicle related patterns, and promoting pedestrian and driver caution. The second dataset, titled **"Collisions with Parties Involved"**, provided insights into the specifics of each collision event, detailing parties, vehicles, and their involvement. We acquired both of these datasets from https://catalog.data.gov/

<H2>Packages Used</H2>
<ul>
  <li>pandas</li>
<li>numpy</li>
<li>matplotlib</li>
<li>seaborn</li>
<li>folium</li>
<li>re</li>
<li>datetime</li>
<li>sklearn</li>
<li>train_test_split</li>
<li>OneHotEncoder</li>
<li>StandardScaler</li>
<li>ColumnTransformer</li>
<li>Pipeline</li>
<li>RandomForestClassifier</li>
<li>xgboost</li>
<li>classification_report</li>
<li>GridSearchCV</li>
<li>roc_curve</li>
<li>roc_auc_score</li></ul>

<H2>Data Exploration (Exploratory Data Analysis or EDA)</H2>
The goal here was to find out more about the data and become a subject matter expert on the data we were working with:
<ul>
  <li>What questions are we trying to solve?</li>
<li>What kind of data do we have and how do we treat different datatypes?</li>
<li>What is missing from the data and how do we deal with it?</li>
<li>How can we add, change or remove features to get more out of our data?</li></ul>

<H2>Data Processing</H2>
After loading both data sets, we cleaned the data by:
<ul>
  <li>Dropping unnessecary columns that were not relevant for our analysis</li>
<li>Renaming columns</li>
<li>Eliminating duplicates</li>
<li>Transforming the data to cater towards our analysis</li>
<li>Extracting unique features from our data set</li></ul>

<H2>Data Analysis</H2>
<ul>
  <li>Mapping hotspots for collisions using Heatmap</li>
<li>Discovering the relationship between the year of manufacturing of vehicle and year of collisions using Barchart</li>
<li>Trend analysis of collisions over time using Linechart</li>
<li>Bar Plot to visualize collisions for the Top 5 vehicle makes and Top 5 safety equipment types</li>
<li>Histogram showcasing the frequency of collisions for different vehicle years</li>
<li>Constructing a data pipeline and deploying an XGBoost ML model to predict collision severity with 95.92% accuracy</li></ul>

<H2>Conclusion</H2>
<ul>
  <li>The Heatmap's output indicates that San Francisco's central regions see a high number of collisions. This conclusion has implications for how the government should plan or carry out preventive measures to ensure that collisions don't occur in the same places twice. Redesigning the roads, updating the traffic systems, and stepping up enforcement in high-traffic areas such as the downtown of San Francisco are a few preventive measures.</li>
<li>One of our conclusions is the quantity of fatalities and injuries resulting from collisions, broken down by vehicle type and equipment deployment analysis. The outcome is significant because automakers can now introduce cutting-edge technologies to raise the bar for driver safety. Both automakers and consumers may find it helpful to know which particular car brands have safety concerns. Since cars are among the most necessary personal items for human life, prospective car buyers can use this information to make well-informed decisions before making a purchase.</li>
<li>Manufacturers of automobiles have the ability to produce more safe vehicles and add more modern safety features. For instance, they could install more AI cameras with sharp vision to detect possible incidents and protect drivers in the event of a collision. It is difficult to protect all parties involved in the collision, including pedestrians, and it can only protect drivers of motor vehicles. As a result, since it is difficult to control outside factors like the weather and because car and safety parts are less certain, humans themselves are the most important resource for saving lives. All users of the road are required to abide by the laws and guidelines. According to one of our analyses, speeding too fast and running red lights have resulted in numerous deaths and injuries. In California, driving too fast is the primary cause of auto accidents. Decreased speed can improve road safety for vehicles, pedestrians, cyclists, and wildlife. In California, where the streets are poorly maintained, it is especially everyone's duty to share the road. Not only does sharing save lives, but it also has numerous advantages. For instance, if someone wants to use our lane, please slow down and give them space to travel in a way that calms the rest of us down.
</li>
<li>Modelling findings will help the government to make the right decisions and to address, for example, the slippery road issue as we found this result in our model so that it can reduce serious collisions due to this issue. Collision is influenced by many factors based on our findings and all business organizations, governments, and all individuals require to collaborate and thus creating safer environment for the future.</li></ul>

