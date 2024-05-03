# Exploratory Analysis on Automobile Dataset
Visualization using Python on Automobile dataset.<br>
Explored seaborn library to create visualizations for exploring the inbuilt automobile dataset.

<h2>Introduction:</h2>
<p>The main aspect of this dataset is to determine which car has the highest mileage based on the other factors such as the cylinders, weight, displacement and horsepower etc. American manufacturers started producing lighter, less powerful, four-cylinder vehicles instead of the heavier, more powerful six and eight-cylinder vehicles that had bad gas mileage. To make the cars more fuel efficient, global auto industry decided to increase miles per gallon. In this dataset of cars and their associated price & features that are manufactured between 1970-82 in USA, Europe., and Japan, we get to see the factors affecting the mileage of different cars. The goal of this project is to identify the factors that affects the mileage of the cars.</p>

<h2>Dataset description:</h2>
<p>This dataset contains specifications of each car model.</p>
<ol><li>mpg -> Miles driven by 1 gallon of gasoline (1 galon = 3.7 L , 1 mil = 1.6 Km)(9–46.6)</li>
<li>cylinders -> The number of cylinders in the car (3–8)</li>
<li>displacement -> Engine capacity (68–455)</li>
<li>horsepower -> Horse power (46–230)</li>
<li>weight -> Weight (1613–5140)</li>
<li>acceleration -> Time to reach speed 0–100 km / h in seconds (8–24.8)</li>
<li>model_year -> Car model year (1970–1982)</li>
<li>origin -> Production place of the car</li>
<li>name -> Model name of the car</li></ol>

<h2>What I learnt:</h2>
<ol><li>We peform pandas profiling to get the complete understanding of the data.</li>
<li>We get detailed analysis of each of the 9 variables. It highlights the distinct and missing values in each variable.</li>
<li>Further, we deplict nullity correlation by using missingno library. Nullity correlation ranges from -1 to 1. Zero indicates the variables do not have any correlation. - 1 indicates a strong negative correlation where +1 indicates a strong positive correlation (think of it as the direction of slope)</li>
<li>Moving ahead in EDA, pair plot provides us with relationships between variables within a dataset. This creates a  visualisation and helps us understand the data by summarising a large amount of data in a single figure.</li>
<li>Next, jointplot provides a convenient interface to the class of joint grid by using several types of points.Here, in our case we see positive relation between accelaration and mpg.</li>
<li>Distribution of the mileage, gives the range of the mileage in the dataset. We infer it is that right skewed normal distribution.</li>
<li>Now we display the scatter plot and then plot the linear regression equation between acceleration and mpg and weight and mpg. We conclude that if a user is looking for a faster car then user has to ensure a high mileage per gallon at the same time it should be a lighter body weight vehicle.</li></ol>

<h2>References:</h2>
[1] <a href="https://seaborn.pydata.org/examples/index.html#">Seaborn pack</a><br>
[2] <a href="https://seaborn.pydata.org/tutorial.html">Seaborn tutorial</a><br>
[3] <a href="https://rubikscode.net/2020/07/12/ultimate-python-data-visualization-guide">Seaborn tutorial with Dataset</a><br>
